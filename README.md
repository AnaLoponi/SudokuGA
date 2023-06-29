<p align="center">
# SudokuGA 🔢

  <img src="https://www.somatematica.com.br/curiosidades/sudoku.gif">

Algoritmo genético desenvolvido por alunos da ILUM-Escola de Ciências, como conclusão da disciplina de Redes Neurais e Algoritmos Genéticos, sob orientação do [Prof. Daniel Cassar](https://github.com/drcassar). 

</p>

> Status: Projeto em Desenvolvimento

### 🔎 Objetivo 
- Este trabalho tem como objetivo solucionar o Sudoku de tamanho 9x9 e 4x4 utilizando técnicas evolutivas, selecionando soluções ótimas ao longo de múltiplas gerações.

### ❓ Mas, como o Sudoku funciona?

O Sudoku é um jogo de lógica que consiste em preencher uma grade de 9x9 com números de 1 a 9, de forma que cada linha, coluna e região de 3x3 contenha todos os números de 1 a 9 sem repetição. O jogo começa com algumas células já preenchidas, e o objetivo é preencher as células vazias com os números que faltam, seguindo as regras acima. Para resolver um Sudoku, é necessário usar a lógica e a dedução para determinar qual número deve ser colocado em cada célula vazia. Existem várias técnicas que podem ser usadas para resolver Sudokus, desde as mais simples até as mais avançadas. Algumas das técnicas mais simples incluem:

- Verificar as linhas, colunas e regiões de 3x3 para determinar quais números já foram usados e quais ainda faltam.
- Usar a técnica "apenas um candidato", que consiste em verificar cada célula vazia e determinar qual número pode ser colocado nela com base nos números que já foram usados nas linhas, colunas e regiões de 3x3 correspondentes.
- Usar a técnica "apenas um lugar", que consiste em verificar cada número que ainda falta em uma linha, coluna ou região de 3x3 e determinar em qual célula ele deve ser colocado com base nas outras células já preenchidas.
  
À medida que o jogo progride e mais células são preenchidas, as técnicas de resolução podem se tornar mais avançadas e complexas.

Em 2005, Bertram Felgenhauer e Frazer Jarvis utilizaram computadores e algoritmos especiais, como __algoritmos genéticos__, para determinar o número total de grades completas de Sudokus 9x9. O resultado obtido foi um número extremamente grande, aproximadamente 6.670.903.752.021.072.936.960, ou seja, 6,67 x 10^21. Para ilustrar a magnitude desse número, vamos supor que todos os habitantes do planeta, cerca de 7 bilhões de pessoas, resolvessem um Sudoku por segundo. Mesmo assim, levaria aproximadamente 30.200 anos para completar essa tarefa. Até o momento, não existe uma demonstração matemática para calcular esse valor sem a ajuda de computadores.

### 🧬 E o que são algoritmos genéticos?

`Algoritmos genéticos` são técnicas de otimização inspiradas no processo de evolução biológica. Eles funcionam criando uma população inicial de soluções candidatas e aplicando seleção, recombinação e mutação para evoluir essa população ao longo de várias gerações. As soluções mais aptas têm maior probabilidade de serem selecionadas para reprodução, permitindo a combinação de suas características promissoras. Com o tempo, esses algoritmos convergem para soluções cada vez melhores, encontrando aproximadamente a melhor solução possível para um determinado problema, assim como os organismos que se adaptam melhor ao ambiente têm mais sucesso no meio natural. Quando se fala em algoritmos genéticos, devemos pensar em otimização de processos.

### 🧮 O que são problemas NP e NP completos?

Problemas NP (não polinomiais) são problemas que não podem ser resolvidos por algoritmos polinomiais, ou seja, não podem ser resolvidos em tempo razoável à medida que o tamanho do problema aumenta. Problemas NP-completos são um subconjunto de problemas NP que são considerados os mais difíceis de resolver, pois qualquer problema NP pode ser reduzido a um problema NP-completo em tempo polinomial. Isso significa que, se um problema NP-completo pudesse ser resolvido em tempo polinomial, todos os problemas NP poderiam ser resolvidos em tempo polinomial. Os problemas NP-completos são importantes porque muitos problemas do mundo real são NP-completos, como o problema do caixeiro-viajante e o problema da mochila, e encontrar soluções eficientes para esses problemas pode ter implicações significativas em áreas como ciência da computação, matemática e engenharia.

### 📖 Guia Rápido 

* Sudoku 4x4
> <sub> Resolução do Sudoku 4x4. [Sudoku_4](https://github.com/AnaLoponi/SudokuGA/blob/main/Sudoku_4.ipynb)</sub>
* Sudoku 9x9
> <sub> Resolução do Sudoku 4x4. [Sudoku_9](https://github.com/AnaLoponi/SudokuGA/blob/main/Sudoku_9.ipynb)</sub>
* .gitignore
> <sub>Arquivo texto que indica regras ao Git sobre quais arquivos ou pastas ele deve ignorar em um projeto. [Saiba Mais](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files)</sub>
* Poster
> <sub>Poster de apresentação do projeto. [Veja](https://github.com/AnaLoponi/SudokuGA/blob/main/poster_SudokuGA.pdf)</sub>
* README.md
> <sub>Onde estão armazenadas todas as informações que você acabou de ler ✔️</sub>
