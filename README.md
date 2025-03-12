Projeto: Tabuleiro

Descrição

Este projeto implementa um tabuleiro 10x10 em C, onde são aplicadas habilidades especiais em forma de matrizes de efeito. O programa posiciona navios no tabuleiro e sobrepõe as áreas afetadas pelas habilidades, exibindo o resultado no console.

Funcionalidades

Definição de um tabuleiro 10x10.

Implementação de três habilidades com áreas de efeito diferentes:

Cone: Expande-se para baixo a partir de um ponto de origem.

Cruz: Cobre uma área em forma de cruz com um ponto central.

Octaedro: Forma um losango centrado no ponto de origem.

Sobreposição das habilidades no tabuleiro.

Exibição do tabuleiro atualizado no console.

Regras de Representação

Água: 0

Navio: 3

Área afetada pela habilidade: 5

Estrutura do Código

Inicialização do Tabuleiro: Configura todas as células como 0 e posiciona um navio de teste.

Definição das Matrizes de Habilidades: Matrizes fixas representam as áreas afetadas.

Aplicação das Habilidades: Centraliza a matriz de efeito no ponto de origem e altera o tabuleiro conforme necessário.

Exibição do Tabuleiro: Utiliza printf para mostrar o estado atual do tabuleiro.

Como Executar

Compile o código com:

gcc habilidades_tabuleiro.c -o habilidades_tabuleiro

Execute o programa:

./habilidades_tabuleiro

O tabuleiro atualizado será exibido no terminal.

Exemplo de Saída

0 0 5 0 0 0 0 0 0 0
0 5 5 5 0 0 0 0 0 0
5 5 5 5 5 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0
0 0 5 0 0 3 0 0 0 0
0 0 5 0 0 3 0 0 0 0
0 0 5 0 0 5 0 0 0 0
0 0 0 0 0 5 0 0 0 0
0 0 0 0 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0

Melhorias Futuras
