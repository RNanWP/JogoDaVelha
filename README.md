<<<<<<< HEAD
# Jogo da Velha (Tic-Tac-Toe)

Este é um jogo simples de **Jogo da Velha** (ou Tic-Tac-Toe), onde você joga contra o computador. O objetivo do jogo é formar uma linha, coluna ou diagonal com três símbolos consecutivos, sendo o "X" controlado pelo computador e o "O" controlado pelo jogador.

## Como Jogar

1. **Início do Jogo**: O jogo começa com uma grade 3x3 numerada de 1 a 9. O computador coloca um "X" no centro da grade e o jogador coloca um "O" nas casas restantes.
   
2. **Movimentos**: O jogador escolhe um número de 1 a 9 para fazer sua jogada, e o computador escolhe uma posição livre aleatoriamente para sua jogada.

3. **Vencedor**: O jogo termina quando um jogador (humano ou computador) consegue alinhar três símbolos consecutivos na horizontal, vertical ou diagonal, ou quando todas as casas estiverem preenchidas, resultando em empate.

## Requisitos

- Python 3.x

## Como Executar

1. Clone o repositório ou baixe o arquivo de código.

2. Abra o terminal ou prompt de comando e navegue até o diretório onde o código foi salvo.

3. Execute o código com o seguinte comando:

   ```bash
   python tictactoe.py

O jogo será executado no terminal. Basta seguir as instruções para fazer suas jogadas.
Estrutura do Código
Funções:
display_board(board): Exibe o tabuleiro do jogo no formato de uma grade 3x3.

enter_move(board): Permite que o jogador insira sua jogada, garantindo que o movimento seja válido (número de 1 a 9 e a célula não esteja ocupada).

make_list_of_free_fields(board): Cria uma lista das células livres no tabuleiro.

victory_for(board, sgn): Verifica se o jogador (ou o computador) venceu, checando linhas, colunas e diagonais para três símbolos iguais consecutivos.

draw_move(board): O computador escolhe uma célula livre aleatória para colocar o "X".

Exemplo de Jogo
Aqui está um exemplo de uma possível execução do jogo:

diff
Copiar código
+-------+-------+-------+
|       |       |       |
|   1   |   2   |   3   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   4   |   5   |   6   |
|       |       |       |
+-------+-------+-------+
|       |       |       |
|   7   |   8   |   9   |
|       |       |       |
+-------+-------+-------+

Digite seu movimento: 5
Resultado
O jogo terminará com uma das mensagens:

"You won!" se o jogador vencer.
"I won" se o computador vencer.
"Tie!" se houver empate.
=======
# JogoDaVelha
Desenvolvi um jogo da velha, onde o "computador" joga com você selecionando os quadrados com números
>>>>>>> 3b95457e7ec3505bc78e2d80db8bc83fe3bd4fed
