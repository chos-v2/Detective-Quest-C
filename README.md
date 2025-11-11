# Detective-Quest-C

Este módulo implementa o sistema de mapa da mansão e a funcionalidade de coleta de pistas, utilizando duas estruturas de dados distintas e integradas: a Árvore Binária para o mapa (Sala) e a Árvore Binária de Busca (BST) para as pistas coletadas (PistaNode).

Histórico de Commits
1. Commit Inicial: feat: Simulação de Mapa com Árvore Binária para Navegação
Foco: Criação da estrutura base do mapa.

Funcionalidade: O jogador pode navegar interativamente pela mansão (escolhendo 'e' ou 'd') a partir do "Hall de Entrada" (nó raiz) até atingir um nó-folha (sala sem saída).

Estrutura: Usa a struct Sala com ponteiros esquerda e direita para modelar os cômodos e seus caminhos.

2. Commit Atual: feat: Integração de BST para Coleta e Ordenação de Pistas
Foco: Expansão das funcionalidades do mapa para incluir a coleta de dados ordenados.

Funcionalidade: Adiciona uma pista a cada cômodo da mansão. Quando o jogador visita uma sala com pista, ela é automaticamente inserida em uma BST.

Visualização: Ao finalizar a exploração ('s'), o programa exibe um relatório com todas as pistas coletadas, organizadas em ordem alfabética através de uma travessia in-order na BST.

Estrutura Adicional: Introdução da struct PistaNode para a BST.

