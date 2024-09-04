# LabirintoShrek
Shrek Maze Adventure. Esse código cria um simples jogo de labirinto no terminal onde o jogador controla o Shrek para encontrar a saída do labirinto.
Como Funciona:
Gerar o Labirinto:

A função generateMaze cria um labirinto aleatório com paredes (#) e caminhos ( ). A posição inicial de Shrek é marcada como S e a saída do labirinto como E.
Imprimir o Labirinto:

A função printMaze exibe o labirinto no terminal. Se a posição atual for a mesma que a de Shrek, ele é mostrado como S.
Movimentação de Shrek:

A função moveShrek recebe a direção de movimento (w, a, s, d) e atualiza a posição de Shrek se o movimento for válido (ou seja, se não for uma parede).
Interação com o Usuário:

No loop principal do main, o jogo imprime o labirinto, captura a entrada do usuário para mover o Shrek e verifica se ele alcançou a saída.
Observações:
Esse código é básico e pode ser melhorado com recursos adicionais, como níveis de dificuldade, mais itens colecionáveis, ou até inimigos que se movem.
No Linux, substitua _getch() por getchar() e remova o #include <conio.h>.
