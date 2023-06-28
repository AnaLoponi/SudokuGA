

<img align="center"  src="https://www.somatematica.com.br/curiosidades/sudoku.gif">


# SudokuGA
O sudoku é um jogo de quebra cabeça, originalmente constituído de uma matriz 9x9, dividida em 9 matrizes 3x3. Cada linha, coluna e matriz deve conter números de 1 a 9 e sem repetir.
<dt>
Algoritmo genético desenvolvido por alunos da ILUM-Escola de Ciências, como conclusão da disciplina de Redes Neurais e Algoritmos Genéticos, sob orientação do Prof. Daniel Cassar. Este trabalho tem como objetivo solucionar o Sudoku usando técnicas evolutivas, selecionando soluções ótimas ao longo de múltiplas gerações.

* <a href = "https://github.com/AnaLoponi/SudokuGA/blob/main/Sudoku_4.ipynb" > Sudoku_4 </a><br> Código com reoslução do sudoku 4x4
* <a href = "https://github.com/AnaLoponi/SudokuGA/blob/main/Sudoku_9.ipynb" > Sudoku_9 </a><br> Código com resolução do sudoku 9x9


## Visão geral

Este projeto tem como objetivo resolver o jogo de Sudoku utilizando algoritmos genéticos. O Sudoku é um jogo de quebra-cabeças popular que requer preencher uma grade 9x9 com dígitos de 1 a 9, obedecendo a certas restrições (não repetir um mesmo algarismo em uma coluna, linha ou sub-grade). Problemas como esse, para nós humanos, são relativamente fáceis e lógicos, mas passar essa lógica para um código e executá-lo de forma eficiente na máquina é um desafio extremamente complexo, sendo até mesmo classificado como `NP-Completo` (isso será discutido mais adiante). Mesmo que o universo de jogos possíveis para o Sudoku seja finito, o número é extremamente grande. De acordo com um trabalho realizado por Felgenhauer e Jarvis em 2006, no Sudoku convencional (9x9), existem cerca de 6,67x10²¹ possibilidades.



## Algoritmos genéticos

`Algoritmos genéticos`são técnicas de otimização inspiradas no processo de evolução biológica. Eles funcionam criando uma população inicial de soluções candidatas e aplicando seleção, recombinação e mutação para evoluir essa população ao longo de várias gerações. As soluções mais aptas têm maior probabilidade de serem selecionadas para reprodução, permitindo a combinação de suas características promissoras. Com o tempo, esses algoritmos convergem para soluções cada vez melhores, encontrando aproximadamente a melhor solução possível para um determinado problema, assim como os organismos que se adaptam melhor ao ambiente têm mais sucesso no meio natural. Quando se fala em algoritmos genéticos, devemos pensar em otimização.


## Aplicando no sudoku

Para aplicar os algorítmos genéticos no problema de sudoku, não vai haver mudanças na estrutura em si do código (criar os genes;indivíduos;população;geração;fitness;seleção, etc)
Como os AG podem ser aplicados em vários problemas para otimização, detalhes em operadores como cruzamento são alterados, para se adequar no contexto e problema trabalhado. Em nosso caso aplicado no sudoku, o cruzamento utilizado se chama "Cross Over".

Clique aqui para acessar os códigos para mais detalhes:
 <a href = "https://github.com/AnaLoponi/SudokuGA/blob/main/Sudoku_4.ipynb" > Sudoku_4 </a><br>
 <a href = "https://github.com/AnaLoponi/SudokuGA/blob/main/Sudoku_9.ipynb" > Sudoku_9 </a><br>
 Os códigos estão comentados.


## Problemas NP e NP completos

Os problemas de NP e NP-completos são distintos dos outros porblemas de programação. Os NP tem elevados custos computacionais e não tem soluções que sejam EFICIENTES para resolve-los. Estes tipos de problema são definidos como não determinísticos polinomiais (a solução candidata pode ser verificada em tempo polinomial)

O sudoku por exemplo, se trata de um problema NP-completo. Ao resolver um problema NP-completo de forma eficiente, todos os outros problemas de NP tornam-se possíveis de serem solucionados, pois a base deles a problemática principal, é a mesma. Abrindo espaço assim para um grande salto computacional. Estudar estes temas é importantíssimo para a computação.



