# Arquitetura
## Inicialização do tabuleiro

* As funções relacionadas ao gerenciamento das casas do jogo da celha ficarão no módulo **jogovelha.py**.

* O estado de cada casa do jogo será representada por uma string: "." para casa vazia; "X" para casa ocupada pelo primeiro jogador; "O" para casa ocupada pelo segundo jogador.

* A função inicializar() retornará uma lista 3x3, onde cada posição conterá uma string para indicar o estado de uma casa do jogo. A função retornará todas as casas inicialmente vazias.

* A função jogar(jogador, linha, coluna) irá posicionar o **jogador** ("X" ou "O") na posicão definida por **linha** e **coluna**.


##Verificação da validade das jogadas
*Foram realizadas mudanças no módulo **Jogovelha.py** 
*A mudança consiste no acréscimo da string "X" e "O" na função jogar (jogador, linha, coluna)
*E de acordo com a regra do jogo da velha a string "X" ganha o jogo.
