# Algoritmos para Iniciantes

Este guia irá compor as ferramentas para ensino de Algoritmos e Programação de Computadores, onde os alunos aprendem alguma linguagem de programação sem necessidade de um conhecimento prévio.

Esta página é uma coleção de exercícios progressivamente mais difíceis que são adequados para pessoas que tem interesse em aprender Lógica de Programação. Os exercícios, em sua maioria, são algorítmicos e devem/podem ser solucionados sem o uso de bibliotecas. A dificuldade dos exercícios, claro, depende da linguagem de programação que você usa, como por exemplo C, que não têm suporte integrado à listas. Alguns exemplos serão resolvidos em javaScript.

## Nota dos autores
Favor responda o questionário antes da leitura do material que se sucede. Não será necessário se identificar, porém responda com sinceridade. Sua resposta possui extrema importância para o desenvolvimento de ferramentas mais completas e voltadas as suas dificuldades.

[Link para a pesquisa](https://forms.gle/fbXVkcyrXpTkoC3F7).

Após o estudo do material haverá uma nova pesquisa para saber sua percepção sobre o mesmo. Para esse estudo são feitas as mesmas considerações referentes ao estudo acima.

## Começando

Aprender a programar significa aprender a resolver problemas usando código. Conceitualmente, não é muito difícil escrever um programa que resolva um problema que você possa resolver sozinho. A habilidade que você precisa adquirir é pensar precisamente sobre como você resolve o problema e o divide em etapas tão simples que um computador pode executá-las. Encorajo-vos a resolver primeiro algumas instâncias de um problema à mão e pensar sobre o que você fez para encontrar a solução. Por exemplo, se a tarefa estiver classificando listas, classifique algumas listas curtas você mesmo. Um método razoável seria encontrar o menor elemento, anotá-lo e retirá-lo da lista original e repetir esse processo até que você tenha classificado toda a lista. Então você tem que ensinar o computador 1) como encontrar o menor elemento, 2) como escrevê-lo, 3) como atravessá-lo, e envolvê-lo em um loop. Em seguida, continue com o processo de detalhamento da tarefa até ter certeza de que você sabe como escrever o programa necessário.


Este [vídeo](https://www.youtube.com/watch?v=8mei6uVttho) é um ótimo início para nossa jornada, leve o tempo que precisar, assista, pause, reveja quantas vezes achar nescessário.

[![Algoritmos: Primeiro contato](https://img.youtube.com/vi/8mei6uVttho/0.jpg)](https://www.youtube.com/watch?v=8mei6uVttho)


### Pré-requisitos
*[NotePad++](https://notepad-plus-plus.org/download/v7.6.6.html) - O editor de texto/código utilizando pelos autores. Fique a vontade de utilizar outras opções dispoíveis como o [Visual Studio Code](https://code.visualstudio.com/Download).

*Precisaremos também de um navegador capaz de compilar javaScript, como [Google Chrome](https://www.google.com/intl/pt-BR_ALL/chrome/) ou [Firefox](https://www.mozilla.org/pt-BR/firefox/new/).



## Input/Output

### Input
Funções de input são funções que permitem receber dados informados pelo usuário.
A principal função de input é o prompt.

As estruturas básicas são:
 
	var leitura = prompt("Mensagem que será mostrada ao usuário pedindo algo","Resposta padrão"(opcional));
 

- É importante lembrar de atribuir o retorno do prompt há alguma variável para que a informação não seja perdida.
- A mensagem que virá do prompt será tratada como uma string. Caso queira que seja tratada como um número inteiro, é necessário o uso da função parseInt().


### Output
Funções de output são funções que permitem informado dados ao usuário que foram obtidos com o programa.
As principais funções de output são: document.write e alert.

As estruturas básicas são:

	alert("Mensagem a ser mostrada ao usuário em uma janela pop up" + variável_a_ser_exibida_caso_necessário);

- O alert abrirá uma caixa pop up com a mensagem ou variável que será colocada entre os parênteses.

``	
document.write("Mensagem a ser mostrada na seção document da página html" + variável_a_ser_exibida_caso_necessário);
``	

- O document.write exibirá na parte "document" da página web a mensagem ou variável que será colocada entre os parênteses.

### Problema proposto
Faça um programa que leia uma frase digitada pelo usuário e mostre na tela a mensagem digitada.

[Link para vídeo-aula de resolução](https://www.youtube.com/watch?v=uXybP0kbXD4)

[![Algoritmos: Resolução Input](https://img.youtube.com/vi/uXybP0kbXD4/0.jpg)](https://www.youtube.com/watch?v=uXybP0kbXD4)

[Link para baixar o código](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Input_Output/exemplo_input_output.html)


### Questões
1) Escreva um programa que imprima "Hello World" na tela.

2) Escreva um programa que peça ao usuário seu nome e cumprimente-o com seu nome.

3) Escreva um programa que leia dois números e mostre sua soma.

4) Escreva um programa que leia uma temperatura em graus Celsius e exiba a
temperatura na escala Fahrenheit.

5) Escreva um programa que leia um número real e mostre o inteiro mais próximo.

## If/Else
As funções if, else if e else são funções condicionais. O que quer dizer que elas permitem que determinada parte do código seja executado caso uma condição seja verdadeira.

Estrutura básica:

	if (primeira_condição_a_ser_testada)
	{
		Bloco de código para o caso no qual a condição testada seja verdadeira;
	}
	else if(segunda_condição_a_ser_testada)
	{
		Bloco de código que será executado caso a segunda condição testada seja verdadeira;
		//Não existe a obrigatoriedade de existir, mas o mesmo só pode existir após um if.
		//Podem existir quantos blocos de "else if" o desenvolvedor achar necessário.
	}
	else{
		Bloco de código que será caso nem a primeira nem a segunda condição sejam verdadeiras;
		//Não existe a obrigatoriedade de existir, mas o mesmo só pode existir após um if.
	}

### Problema proposto:
Escreva um programa que peça ao usuário que digite um número e mostre na tela -1 caso o número digitado seja negativo, mostre 0 caso o número digitado seja igual a 0 ou mostre na tela 1 caso o número digitado seja positivo.

[Link para vídeo-aula de resolução](https://www.youtube.com/watch?v=X9SoaG2IL2A)

[![Algoritmos: Resolução If](https://img.youtube.com/vi/X9SoaG2IL2A/0.jpg)](https://www.youtube.com/watch?v=X9SoaG2IL2A)

[Link para baixar o código](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_If_Else/Exemplo_If_Else.html)

### Questões:
1) Escreva um programa que receba um número digitado pelo usuário e mostre na tela 0 caso ele seja par ou 1 caso ele seja impar.

2) Escreva um programa que receba dois números digitados pelo usuário e mostre qual o maior número.

3) Escreva um programa que receba dois números inteiros, e retorne 1 caso o primeiro seja divisível pelo
segundo e 0 caso contrário.

4) Escreva um programa que leia um número real e mostre o inteiro mais próximo.

6) Escreva um programa realize o jogo do pedra, papel ou tesoura. O programa deve pedir uma das três opções para dois jogadores. Ao final deve ser mostrado na tela qual jogador ganhou ou se houve empate.

5) Um caixa eletrônico possui cédulas de 2, 5, 10, 20, 50 e 100 reais. Escreva um programa que leia o valor a ser sacado e mostre a quantidade de cada cédula a ser utilizada de modo que o mínimo de notas seja retirado.

## While
A função for é uma estrutura de repetição. Ela permite repetir uma determinada parte do código quantas vezes forem necessárias. É usada de forma de forma majoritária quando não se tem uma quantidade de repetições definida e é necessário continuar a executar enquando uma determiada condição for verdadeira.

Estrutura básica:

	while(CONDIÇÃO VERDADE)
	{
		BLOCO DE CÓDIGO A SER EXECUTADO ATÉ QUE A CONDIÇÃO DESCRITA ENTRE PARÊNTESES SEJA FALSA;
	}
	
### Problema proposto:
Faça um programa que leia 5 números inteiros que deverão ser informados pelo usuário e retorne o valor da soma dos números.

[Link para vídeo-aula de resolução](https://www.youtube.com/watch?v=qb4qNCpHoUY)

[![Algoritmos: Resolução While](https://img.youtube.com/vi/qb4qNCpHoUY/0.jpg)](https://www.youtube.com/watch?v=qb4qNCpHoUY)

[Link para baixar o código](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_While/Exemplo_While.html)

### Questões:
1) Escreva um programa que leia 10 números digitados pelo usuário e mostre na tela a média deles.

2) Escreva um programa que peça ao usuário o número de interações a serem realizado. Em cada interação, o usuário deve informar um número e ao final delas o programa deverá informar a média deles.

3) Escreva um programa que peça ao usuário o número de interações a serem realizado. Em cada interação, o usuário deve informar um número e ao final delas o programa deverá informar o maior número entre os digitados.

4) Escreva um programa que peça ao usuário o número de interações a serem realizado. Em cada interação, o usuário deve informar um número e ao final delas o programa deverá informar quantos desses números são positivos, quantos são negativos, qual o maior e o menor número entre os digitados.

5) Escreva que peça digite um número e continue a pedir enquanto o número digitado não for igual a zero. Ao final informe quantos números foram digitados.

6) Escreva que peça digite um número e continue a pedir enquanto o número digitado não for igual a zero. Ao final o programa deverá informar quantos desses números são positivos, quantos são negativos, qual o maior e o menor número entre os digitados.

7) Escreva um programa que sortei 10 números aleatórios entre 0 e 10 e mostre na tela os números sorteado, a média deles e qual o maior e o menor número entre eles.

8) Escreva um programa que sorteie 10 números aleatórios entre -10 e 10 e mostre na tela os números sorteado, quantos deles são positivos, quantos são positivos, quantos são negativos e qual o maior e o menor número entre eles.

9) Escreva um programa que sorteie 10 números aleatórios entre 0 e 10, a cada sorteio o usuário deverá digitar um número. Ao final do sorteio o programa deverá informar quantos acertos o usuário obteve. Cada acerto só será contabilizado caso o usuário acerte o número que foi sorteado naquela rodada.

8) Escreva um programa que peça ao usuário um número positivo ao usuário. Ao final, informe o valor do fatorial do número digitado.

10) Escreva um programa que peça uma base e um expoente, positivos, ao usuário. No final informe o valor da base elevada ao expoente.

11) Escreva um programa que peça uma base e um expoente, que podem ser positivos ou negativos, ao usuário e ao final informe o valor da base elevada ao expoente.

12) Escreva um programa que peça ao usuário um valor e informe se o mesmo é primo ou não.

13) Escreva um programa que mostre na tela os 10 primeiros termos da série de Fibonacci.

14) Escreva peça na tela um número N e mostre na tela os N primeiros termos da série de Fibonacci.

## For
A função for é uma estrutura de repetição. Ela permite repetir uma determinada parte do código quantas vezes forem necessárias. É usada de forma de forma majoritária quando se tem uma quantidade de repetições definida.

Estrutura básica:

	for(CONDIÇÃO INICIAL;CONDIÇÃO FINAL; INCREMENTO/DECREMENTO)
	{
		BLOCO DE CÓDIGO A SER EXECUTADO ATÉ QUE A CONDIÇÃO INICIAL SEJA IGUAL A FINAL;
	}
	
### Problema proposto:
Faça um programa que leia 5 números inteiros que deverão ser informados pelo usuário e retorne o valor da soma dos números.

[Link para vídeo-aula de resolução](https://www.youtube.com/watch?v=bWxTuL7EHFY)

[![Algoritmos: Resolução For](https://img.youtube.com/vi/bWxTuL7EHFY/0.jpg)](https://www.youtube.com/watch?v=bWxTuL7EHFY)

[Link para baixar o código](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_For/Exemplo_For.html)

### Questões
1) Escreva um programa que leia 10 números digitados pelo usuário e mostre na tela a média deles.

2) Escreva um programa que peça ao usuário o número de interações a serem realizado. Em cada interação, o usuário deve informar um número e ao final delas o programa deverá informar a média deles.

3) Escreva um programa que peça ao usuário o número de interações a serem realizado. Em cada interação, o usuário deve informar um número e ao final delas o programa deverá informar o maior número entre os digitados.

4) Escreva um programa que peça ao usuário o número de interações a serem realizado. Em cada interação, o usuário deve informar um número e ao final delas o programa deverá informar quantos desses números são positivos, quantos são negativos, qual o maior e o menor número entre os digitados.

5) Escreva um programa que sortei 10 números aleatórios entre 0 e 10 e mostre na tela os números sorteado, a média deles e qual o maior e o menor número entre eles.

6) Escreva um programa que sortei 10 números aleatórios entre -10 e 10 e mostre na tela os números sorteado, quantos deles são positivos, quantos são positivos, quantos são negativos e qual o maior e o menor número entre eles.

7) Escreva um programa que sortei 10 números aleatórios entre 0 e 10, a cada sorteio o usuário deverá digitar um número. Ao final do sorteio o programa deverá informar quantos acertos o usuário obteve. Cada acerto só será contabilizado caso o usuário acerte o número que foi sorteado naquela rodada.

8) Escreva um programa que peça ao usuário um número positivo ao usuário. Ao final, informe o valor do fatorial do número digitado.

9) Escreva um programa que peça uma base e um expoente, positivos, ao usuário. No final informe o valor da base elevada ao expoente.

10) Escreva um programa que peça uma base e um expoente, que podem ser positivos ou negativos, ao usuário e ao final informe o valor da base elevada ao expoente.

11) Escreva um programa que peça ao usuário um valor e informe se o mesmo é primo ou não.

12) Escreva um programa que mostre na tela os 10 primeiros termos da série de Fibonacci.

13) Escreva peça na tela um número N e mostre na tela os N primeiros termos da série de Fibonacci.



## Function
Function permite a criação de funções que podem ser chamadas durante o código. As functions são importântes porque permitem a utilização do mesmo trecho do código, podendo mudar os parâmetros de entrada, sem a necessidade de reescrevê-los. As functions podem ter um retorno ou simplesmente fazerem modificações internas.

Estrutura básica:

	function NOME_DA_FUNÇÃO(PARÂMETROS DA FUNÇÃO)
	{
		CÓDIGO A SER EXECUTADO DENTRO DA FUNÇÃO;
		return VALOR_A_SER_RETORNADO;  --> CASO EXISTA ALGUM VALOR A SER RETORNADO
	}

### Problemas propostos:
1) Escreva uma função que receba um número inteiro e positivo e retorne 0 caso o mesmo seja par ou 1 caso o mesmo seja impar.
2) Escreva uma função que receba dois números e retorne a soma deles.

[Link para vídeo-aula de resolução](https://www.youtube.com/watch?v=sB5gISgLbfg)

[![Algoritmos: Resolução Function](https://img.youtube.com/vi/sB5gISgLbfg/0.jpg)](https://www.youtube.com/watch?v=sB5gISgLbfg)

[Link para baixar o código](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Fuction/Exemplo_Function.html)

### Questões:
1) Fazer uma função que receba um número inteiro e retorne 1 caso seja par e 0 caso seja impar.

2) Fazer uma função que receba dois números inteiros, e retorne 1 caso o primeiro seja divisível pelo
segundo e 0 caso contrário.

3) Fazer uma função que retorne a quantidade de divisores de um número inteiro, fornecido para a
função.

4)  Fazer uma função que receba três números, A, B e C de uma equação do segundo grau (Ax2+Bx+C=0), e
retorne 1 caso tenha duas raízes reais distintas, 0 caso tenha duas raízes reais iguais e –1 caso não
tenha raízes reais.

5) Faça uma função que recebe a idade de uma pessoa em anos, meses e dias e retorna essa idade expressa em dias.

6) Fazer uma função que receba um número inteiro e retorne o fatorial.

7) Fazer uma função que receba uma base e um expoente e retorne o valor da base elevado ao expoente.

8) Fazer uma função que receba um número x e retorne o valor do sen(x) calculado pela série de Taylor.

9) Faça uma função que receba um número referente a uma posição retorne o elemento da série de Fibonacci que se encontra na posição recebida.

10) Faça uma função que receba um número e retorne se ele verdadeiro se ele é um elemento da série de Fibonacci ou falso caso não.

11) Faça uma função que receba dois número e retorne verdadeiro caso eles sejam elementos consecutivos da série de Fibonacci.

## Vetor
Um vetor é uma coleção de variáveis de mesmo tipo e acessíveis com um único nome. A individualização de cada variável de um vetor é feita através do uso de índices.

Estrutura básica:
Um vetor pode ser iniciado vazio ou valores previamente definidos. 

-Inicializando um vetor vazio e sem tamanho prévio.

	var vetor = [];
	
-Inicializando um vetor vazio e com tamanho prévio.

	var vetor = new Array(TAMANHO_DO_VETOR);
	
-Inicializando um vetor preenchido.

	var vetor = [Num1 Num2 ... NumN];
	
-Inicializando um vetor preenchido.

	var vetor = new Array(Num1 Num2 ... NumN);
	
Para acessar os elementos de um vetor basta usar o nome do vetor seguido de colchetes com o valor do índice em seu interior. É importante lembrar que a primeira posição de um vetor em JavaScript recebe o índice zero.
Exemplo:
      
	vetor[0]
	
Com esse comando é possível acessar o primeiro elemento do vetor.

### Problema proposto:
Faça um programa que leia 5 números inteiros que deverão ser informados pelo usuário e grave em um vetor. Ao final, percorra todo o vetor e mostre na tela os elementos armazenados no vetor.

[Link para vídeo-aula de resolução](https://www.youtube.com/watch?v=e0QLYC8VYfM)

[![Algoritmos: Resolução Vetor](https://img.youtube.com/vi/e0QLYC8VYfM/0.jpg)](https://www.youtube.com/watch?v=e0QLYC8VYfM)

[Link para baixar o código](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Vetor/Exemplo_Vetor.html)

### Questões
1) Escreva um programa que leia 10 números digitados pelo usuário e grave-os em um vetor. Ao final, mostre o vetor de trás para frente.

2) Escreva um programa que leia 10 números digitados pelo usuário. Grave os 5 primeiros números em um vetor e os 5 últimos em um segundo vetor. Troque todos os elementos do primeiro vetor com os elementos do segundo vetor e ao final mostre todos os elementos dos dois vetores.

3) Escreva um programa que leia 10 números digitados pelo usuário e grave-os em um vetor. Após isso, peça para o usuário digitar um décimo primeiro número que deverá ser procurado. Percorra todo o vetor inicial e informe na tela quantas vezes o décimo primeiro número aparece no vetor.

4) Escreva um programa que leia 10 números digitados pelo usuário. Grave os 5 primeiros números em um vetor e os 5 últimos em um segundo vetor. Percorra os dois vetores e mostre na tela a soma do maior elemento do primeiro vetor com o menor elemento do segundo vetor.

5) Escreva um programa que leia 10 números digitados pelo usuário. Grave os 5 primeiros números em um vetor e os 5 últimos em um segundo vetor. Mostre na tela um terceiro vetor que será igual a concatenação dos dois vetores.

6) Escreva um programa que leia 10 números digitados pelo usuário e grave-os em um vetor. Ao final, mostre o vetor em ordem crescente.

7) Escreva um programa que leia 2 palavras digitadas pelo usuário. Ao final, mostre as palavras em ordem alfabética.

8) Escreva um programa que leia 10 números digitados pelo usuário. Grave os 5 primeiros números em um vetor e os 5 últimos em um segundo vetor. Mostre na tela um terceiro vetor que será a ordenação dos dois outros vetores em ordem crescente.

9) Escreva um programa que leia 10 números digitados pelo usuário. Grave os 5 primeiros números em um vetor e os 5 últimos em um segundo vetor. Mostre na tela um terceiro vetor que será a ordenação dos dois outros vetores em ordem crescente excluindo os valores repetidos.


## Matriz
Uma matriz consiste em um vetor em que cada elemento é constituido por um vetor.

Estrutura básica:

-Inicialização de vetor de n linhas com a quantidade de colunas indefinidas.

	var vetor_matriz = [];
	vetor_matriz[0] = [];
	      .
	      .
	      .
	vetor_matriz[n] = [];
	
-Inicialização de vetor de n linhas com a quantidade de colunas definidas.

	var vetor = [Num1 Num2 ... NumN];
	vetor_matriz[0] = [Num1 Num2 ... NumN];
	vetor_matriz[1] = [Num1 Num2 ... NumN];
	             .
		     .
		     .
	vetor_matriz[n] = [Num1 Num2 ... NumN];
	
-Acessando uma posição da matriz.
	
	matriz[0][0]
	
Com esse comando o programa acessa o elemento presente na primeira linha e na primeira coluna da matriz.

## Problema proposto:
Faça um programa que preencha uma matriz de N linhas por M colunas. O preenchimento da matriz deve ser feito a partir do número inicial zero e a cada índice, esse número deverá ser incrementado em 5. 

Exemplo:

Para uma matriz 3x2, a saída deve ser:

0  5

10 15

20 25

Note que a impressão na tela deve ser feita da mesma maneira como no exemplo acima.


[Link para vídeo-aula de resolução](https://www.youtube.com/watch?v=nwh1Fr40pSs)

[![Algoritmos: Resolução Vetor](https://img.youtube.com/vi/nwh1Fr40pSs/0.jpg)](https://www.youtube.com/watch?v=nwh1Fr40pSs)

[Link para baixar o código](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Matriz/Exemplo_Matriz.html)

### Questões:

1) Faça um programa que preencha uma matriz de N linhas por M colunas. O preenchimento da matriz deve ser feito a partir de números que deverão ser pedidos para o usuário. Ao final percorra toda a matriz e mostre todos os elementos.

2) Faça um programa que preencha uma matriz de N linhas por M colunas. O preenchimento da matriz deve ser feito a partir de números que deverão ser pedidos para o usuário. Ao final, o programa deverá retornar a transposição da matriz informada.

3) Faça um programa que receba duas matrizes de N linhas por M colunas, cujo os elementos de cada uma das matrizes deverá ser informado pelo usuário. O programa deverá realizar a soma das duas matrizes e ao final exibir na tela a matriz resultante.

4) Faça um programa que receba duas matrizes, cuja as dimensões e os elementos de cada uma das matrizes deverão ser informados pelo usuário. O programa deverá realizar a multiplicação das duas matrizes e ao final exibir na tela a matriz resultante.

5) O professor de uma pequena sala de aula, dispõe as notas dos seus 5 alunos em cada
uma das 4 avaliações aplicadas em uma tabela conforme o modelo abaixo.

![Imagem2](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Matriz/Imagens_Quest%C3%B5es/Tabela_Quest%C3%A3o_2.JPG)

Escreva um programa que utilize uma matriz 5 x 4 para realizar cada uma das
seguintes tarefas:

a) Leia as notas dos alunos;

b) Informe a média do “Aluno 4” ao longo do semestre de acordo com os valores
constantes na matriz;

6) Uma fábrica de calçados é composta por trabalhadores classificados em três perfis de
produtividade de acordo com a quantidade de peças produzidas como mostra a tabela
abaixo.

![Imagem3](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Matriz/Imagens_Quest%C3%B5es/Tabela_Quest%C3%A3o_3.JPG)

Os trabalhadores da classe 1 recebem um salário mínimo de R$880,00 sem
adicional. Os da classe 2 recebem o salário mínimo mais um adicional de 2% deste
salário por cada peça produzida acima das 30 peças iniciais. Os da classe 3, recebem
o salário mínimo mais um adicional de 4% desse salário por cada peça produzida
acima das 30 peças iniciais. Escreva um programa em javascript que:

a) Leia pelo teclado e armazene na primeira coluna de uma matriz 5x3 a
quantidade de peças produzidas por 5 funcionários;

b) Calcule e armazene na segunda coluna dessa matriz o adicional recebido por
cada funcionário de acordo com seu perfil de produtividade;

c) Calcule e armazene na terceira coluna da matriz o salário recebido por cada
funcionário respectivamente;

d) Calcule e mostre na tela quanto a fábrica gastou com a folha salarial;

e) Calcule e mostre na tela a quantidade de peças produzidas.

c) Informe a média da turma na “NP2 Prática”;

d) Informe a média geral da turma em todas as provas.

7) A tabela abaixo mostra, para determinada região do Ceará, a distância em quilômetros
entre qualquer cidade e outras 4 cidades vizinhas:

![imagem4](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Matriz/Imagens_Quest%C3%B5es/Tabela_Quest%C3%A3o_4.JPG)

Escreva um programa que:

- Leia uma matriz que armazene as distâncias entre as cidades desta região
conforme o modelo acima;

- Calcule a maior distância entre duas cidades;

- Calcule e mostre as quais cidades guardam entre si a distância calculada no
item anterior;

- Calcule e mostre na tela a distância percorrida por um viajante que realiza o
seguinte trajeto, cidades: 0, 2, 3, 1 e 4.

- Leia em vetor um trajeto de 5 cidades escolhidas pelo usuário.

- Calcule e mostre a distância percorrida por um viajante que faça o trajeto lido
no item anterior.

8) Faça um programa que preencha uma matriz quadrada de N linhas. O preenchimento da matriz deve ser feito a partir de números que deverão ser pedidos para o usuário. Ao final o programava deverá retorna o determinante da matriz informada.

## Nota dos autores
Favor responda o questionário após da leitura do material que se sucedeu. Não será necessário se identificar, porém responda com sinceridade. Sua resposta possui extrema importância para o desenvolvimento de ferramentas mais completas e voltadas as suas dificuldades.

[Link para a pesquisa](https://forms.gle/CsjbfTev9xEgyBCh9)

## Bibliografia

ASCENCIO, Ana Fernanda Gomes;CAMPOS, Edilene Aparecida Veneruchi de. <b>Fundamentos da programação de computadores : algoritmos, pascal, c/c++ e java</b>. 3. ed. São Paulo: Pearson Education do Brasil, 2012.

FORBELLONE, Andre Luiz Vilar;EBERSPACHER, Henri Frederico. <b>Lógica de programação : a construção de algoritmos e estruturas de dados</b>. 3. ed. São Paulo: Pearson Education do Brasil, 2010.

PUGA, Sandra;RISSETTI, Gerson. <b>Logica de programacao e estruturas de dados com aplicacoes em java</b>. São Paulo: Pearson Education do Brasil;Prentice-Hall, 2004.

