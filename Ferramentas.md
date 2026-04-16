# Ferramentas que serão utilizadas no processo de análise.
 Será utilizado a Linguagem Python com a biblioteca python-chess que junto ao módulo chess.pgn é amplamente utilizada para analisar partidas de xadrez em formato PGN(Portable Game Notation).  
 
### A biblioteca utiliza bitboards para representar o estado do tabuleiro, se divide em subpacotes : 
 - chess(core) : inclui geração de movimentos, validação, detecção de repetições.
 - chess.pg : le e escreve pgn, suporta cabeçalhos, comentários, NAGs(anotações numéricas) e uma árvore de variações.
 - chess.engine : implementa uma abstração para jogar movimentos e analisar posições com engines UCIe XBoard.
 - chess.polyglot : le livros de aberturas em formato Polyglot binário.
 - chess.gaviota : permitem consultar tablebases de finais de jogo.
