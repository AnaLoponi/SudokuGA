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

Cruzamento -> Crossover single-point
dois cromossomos geram dois cromossomos
caso haja crossover, filhos substituem os pais, caso contrário, os pais passam para a geração seguinte

[

Para resolver o problema de resolução do Sudoku, utilizamos o método dos algorítmos genéticos. 

]

Troca hill climbbing será realizada em um local onde melhorará o fitness do indivíduo, 2 bits serão trocados de lugar.

## Visão geral

Este projeto tem como objetivo resolver o jogo de Sudoku utilizando algoritmos genéticos. O Sudoku é um jogo de quebra-cabeças popular que requer preencher uma grade 9x9 com dígitos de 1 a 9, obedecendo a certas restrições (não repetir um mesmo algarismo em uma coluna, linha ou sub-grade). Problemas como esse, para nós humanos, são relativamente fáceis e lógicos, mas passar essa lógica para um código e executá-lo de forma eficiente na máquina é um desafio extremamente complexo, sendo até mesmo classificado como NP-Completo (isso será discutido mais adiante). Mesmo que o universo de jogos possíveis para o Sudoku seja finito, o número é extremamente grande. De acordo com um trabalho realizado por Felgenhauer e Jarvis em 2006, no Sudoku convencional (9x9), existem cerca de 6,67x10²¹ possibilidades.

## Algoritmos genéticos

Algoritmos genéticos são técnicas de otimização inspiradas no processo de evolução biológica. Eles funcionam criando uma população inicial de soluções candidatas e aplicando seleção, recombinação e mutação para evoluir essa população ao longo de várias gerações. As soluções mais aptas têm maior probabilidade de serem selecionadas para reprodução, permitindo a combinação de suas características promissoras. Com o tempo, esses algoritmos convergem para soluções cada vez melhores, encontrando aproximadamente a melhor solução possível para um determinado problema, assim como os organismos que se adaptam melhor ao ambiente têm mais sucesso no meio natural. Quando se fala em algoritmos genéticos, devemos pensar em otimização

## Aplicando no sudoku

## Problemas NP e NP compostos



