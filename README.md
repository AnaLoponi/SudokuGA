# SudokuGA
O sudoku é um jogo de quebra cabeça, originalmente constituído de uma matriz 9x9, dividida em 9 matrizes 3x3. Cada linha, coluna e matriz deve conter números de 1 a 9 e sem repetir.
<dt>
Algoritmo genético desenvolvido por alunos da ILUM-Escola de Ciências, como conclusão da disciplina de Redes Neurais e Algoritmos Genéticos, sob orientação do Prof. Daniel Cassar. Este trabalho tem como objetivo solucionar o Sudoku usando técnicas evolutivas, selecionando soluções ótimas ao longo de múltiplas gerações.

*  **funcoes_sudoku** Neste arquivo, colocamos as funções de algorítmos genéticos que vamos importar para o notebook geral, "sudoku".
*  **sudoku** Aqui será onde realizaremos de fato a geração e a simulação na evolução dos nossos indivíduos. O arquivo onde tudo será executado.

## Abordagem:

* Gerar indivíduos com genes indo do número 1 a 9, para cada matriz. Sendo assim, um indivíduo vai ser composto de 81 genes dividios em 9 cromossomos (9 genes por cromossomo)
* Selecionar os indivíduos que menos repetem números nas colunas, linhas e matrizes
* Geração após geração, menos repetições.

