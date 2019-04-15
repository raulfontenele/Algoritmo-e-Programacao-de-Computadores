# Algorítmos para Iniciantes

Este guia irá compor as ferramentas para ensino de Algoritmos e Programação de Computadores, onde os alunos aprendem alguma linguagem de programação sem necessidade de um conhecimento prévio.

Esta página é uma coleção de exercícios progressivamente mais difíceis que são adequados para pessoas que tem interesse em aprender Lógica de Programação. Os exercícios, em sua maioria, são algorítmicos e devem/podem ser solucionados sem o uso de bibliotecas. A dificuldade dos exercícios, claro, depende da linguagem de programação que você usa, como por exemplo C, que não têm suporte integrado à listas. Alguns exemplos serão resolvidos em javaScript.

## Começando

Aprender a programar significa aprender a resolver problemas usando código. Conceitualmente, não é muito difícil escrever um programa que resolva um problema que você possa resolver sozinho. A habilidade que você precisa adquirir é pensar precisamente sobre como você resolve o problema e o divide em etapas tão simples que um computador pode executá-las. Encorajo-vos a resolver primeiro algumas instâncias de um problema à mão e pensar sobre o que você fez para encontrar a solução. Por exemplo, se a tarefa estiver classificando listas, classifique algumas listas curtas você mesmo. Um método razoável seria encontrar o menor elemento, anotá-lo e retirá-lo da lista original e repetir esse processo até que você tenha classificado toda a lista. Então você tem que ensinar o computador 1) como encontrar o menor elemento, 2) como escrevê-lo, 3) como atravessá-lo, e envolvê-lo em um loop. Em seguida, continue com o processo de detalhamento da tarefa até ter certeza de que você sabe como escrever o programa necessário.


Este [vídeo](https://www.youtube.com/watch?v=8mei6uVttho) é um ótimo início para nossa jornada, leve o tempo que precisar, assista, pause, reveja quantas vezes achar nescessário.

[![Algoritmos: Primeiro contato](https://img.youtube.com/vi/8mei6uVttho/0.jpg)](https://www.youtube.com/watch?v=8mei6uVttho)


### Pré-requisitos

*[NotePad++](https://notepad-plus-plus.org/download/v7.6.6.html) - O editor de texto/código utilizando pelos autores. Fique a vontade de utilizar outras opções dispoíveis.
*Precisaremos também de um navegador capaz de compilar javaScript, como [Google Chrome](https://www.google.com/intl/pt-BR_ALL/chrome/) ou [Firefox](https://www.mozilla.org/pt-BR/firefox/new/).



## Input/Output

### Input
Funções de input são funções que permitem receber dados informados pelo usuário.
As principais funções de input são: prompt e confirm.

As estruturas básicas são:
 
	var leitura = prompt("Mensagem que será mostrada ao usuário pedindo algo","Resposta padrão"(opcional));
 


- É importante lembrar de atribuir o retorno do prompt há alguma variável para que a informação não seja perdida.
- A mensagem que virá do prompt será tratada como uma string. Caso queira que seja tratada como um número inteiro, é necessário o uso da função parseInt().

	var leitura = confirm("Mensagem para perguntar se ele deseja confirmar");

 - A função confirm atribui true caso o usuário clique em "Ok" ou atribui false caso o usuário clique em "Cancelar"

### Output
Funções de output são funções que permitem informado dados ao usuário que foram obtidos com o programa.
As principais funções de output são: document.write e alert.

As estruturas básicas são:
``
alert("Mensagem a ser mostrada ao usuário em uma janela pop up" + variável_a_ser_exibida_caso_necessário);
``

- O alert abrirá uma caixa pop up com a mensagem ou variável que será colocada entre os parênteses.

``
document.write("Mensagem a ser mostrada da seção document da página html" + variável_a_ser_exibida_caso_necessário);
``

- O document.write exibirá na parte "document" da página web a mensagem ou variável que será colocada entre os parênteses.

### Problema proposto
FAÇA UM PROGRAMA QUE LEIA UMA FRASE DIGITADA PELO USUÁRIO. APÓS ISSO, PEÇA QUE ELE CONFIRME QUE DIGITOU A MENSAGEM. CASO ELE CLIQUE EM OK, MOSTRE A MENSAGEM DIGITADA CASO ELE CLIQUE EM CANCELAR, DIGA QUE NÃO FOI POSSÍVEL IDENTIFICAR A MENSAGEM DIGITADA.

[Link para vídeo-aula de resolução](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Input_Output/exemplo_input_output.html)

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
		bloco de código para o caso no qual a condição testada seja verdadeira;
	}
	else if(segunda_condição_a_ser_testada)
	{
		Bloco de código que será executado caso a condição dentro do else if seja verdadeira;
		//Não existe a obrigatoriedade de existir, mas o mesmo só pode existir após um if.
	}
	else{
		Bloco de código que será caso nem a primeira nem a segunda condição sejam verdadeiras;
		//Não existe a obrigatoriedade de existir, mas o mesmo só pode existir após um if.
	}

### Problema proposto:
Escreva um programa que peça ao usuário que digite um número e mostre na tela -1 caso o número digitado seja negativo, mostre 0 caso o número digitado seja igual a 0 ou mostre na tela 1 caso o número digitado seja positivo.

[Link para vídeo-aula de resolução](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Input_Output/exemplo_input_output.html)

[Link para baixar o código](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_If_Else/Exemplo_If_Else.html)

### Questões:
1) Escreva um programa que receba um número digitado pelo usuário e mostre na tela 0 caso ele seja par ou 1 caso ele seja impar.

2) Escreva um programa que receba dois números digitados pelo usuário e mostre qual o maior número.

3) Escreva um programa que receba dois números inteiros, e retorne 1 caso o primeiro seja divisível pelo
segundo e 0 caso contrário.

4) Escreva um programa que leia um número real e mostre o inteiro mais próximo.

6) Escreva um programa realize o jogo do pedra, papel ou tesoura. O programa deve pedir uma das três opções para dois jogadores. Ao final deve ser mostrado na tela qual jogador ganhou ou se houve empate.

5) Um caixa eletrônico possui cédulas de 2, 5, 10, 20, 50 e 100 reais. Escreva um programa que leia o valor a ser sacado e mostre a quantidade de cada cédula a ser utilizada de modo que o mínimo de notas seja retirado.

## For
A função for é uma estrutura de repetição. Ela permite repetir uma determinada parte do código quantas vezes forem necessárias. É usada de forma de forma majoritária quando se tem uma quantidade de repetições definida.

Estrutura básica:

	for(CONDIÇÃO INICIAL;CONDIÇÃO FINAL; INCREMENTO/DECREMENTO)
	{
		BLOCO DE CÓDIGO A SER EXECUTADO ATÉ QUE A CONDIÇÃO INICIAL SEJA IGUAL A FINAL;
	}
	
### Problema proposto:
Faça um programa que leia 5 números inteiros que deverão ser informados pelo usuário e retorne o valor da soma dos números.

[Link para vídeo-aula de resolução](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Input_Output/exemplo_input_output.html)

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

## While
A função for é uma estrutura de repetição. Ela permite repetir uma determinada parte do código quantas vezes forem necessárias. É usada de forma de forma majoritária quando não se tem uma quantidade de repetições definida e é necessário continuar a executar enquando uma determiada condição for verdadeira.

Estrutura básica:
	while(CONDIÇÃO VERDADE)
	{
		BLOCO DE CÓDIGO A SER EXECUTADO ATÉ QUE A CONDIÇÃO DESCRITA ENTRE PARÊNTESES SEJA FALSA;
	}
	
### Problema proposto:
Fça um programa que leia 5 números inteiros que deverão ser informados pelo usuário e retorne o valor da seoma dos números.

[Link para vídeo-aula de resolução](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_Input_Output/exemplo_input_output.html)

[Link para baixar o código](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_While/Exemplo_While.html)

### Questões:
1) Escreva um programa que leia 10 números digitados pelo usuário e mostre na tela a média deles.

2) Escreva um programa que peça ao usuário o número de interações a serem realizado. Em cada interação, o usuário deve informar um número e ao final delas o programa deverá informar a média deles.

3) Escreva um programa que peça ao usuário o número de interações a serem realizado. Em cada interação, o usuário deve informar um número e ao final delas o programa deverá informar o maior número entre os digitados.

4) Escreva um programa que peça ao usuário o número de interações a serem realizado. Em cada interação, o usuário deve informar um número e ao final delas o programa deverá informar quantos desses números são positivos, quantos são negativos, qual o maior e o menor número entre os digitados.

5) Escreva que peça digite um número e continue a pedir enquanto o número digitado não for igual a zero. Ao final informe quantos números foram digitados.

6) Escreva que peça digite um número e continue a pedir enquanto o número digitado não for igual a zero. Ao final o programa deverá informar quantos desses números são positivos, quantos são negativos, qual o maior e o menor número entre os digitados.

7) Escreva um programa que sortei 10 números aleatórios entre 0 e 10 e mostre na tela os números sorteado, a média deles e qual o maior e o menor número entre eles.

8) Escreva um programa que sortei 10 números aleatórios entre -10 e 10 e mostre na tela os números sorteado, quantos deles são positivos, quantos são positivos, quantos são negativos e qual o maior e o menor número entre eles.

9) Escreva um programa que sortei 10 números aleatórios entre 0 e 10, a cada sorteio o usuário deverá digitar um número. Ao final do sorteio o programa deverá informar quantos acertos o usuário obteve. Cada acerto só será contabilizado caso o usuário acerte o número que foi sorteado naquela rodada.

8) Escreva um programa que peça ao usuário um número positivo ao usuário. Ao final, informe o valor do fatorial do número digitado.

10) Escreva um programa que peça uma base e um expoente, positivos, ao usuário. No final informe o valor da base elevada ao expoente.

11) Escreva um programa que peça uma base e um expoente, que podem ser positivos ou negativos, ao usuário e ao final informe o valor da base elevada ao expoente.

12) Escreva um programa que peça ao usuário um valor e informe se o mesmo é primo ou não.

13) Escreva um programa que mostre na tela os 10 primeiros termos da série de Fibonacci.

14) Escreva peça na tela um número N e mostre na tela os N primeiros termos da série de Fibonacci.
