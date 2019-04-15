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

`` 
var leitura = prompt("Mensagem que será mostrada ao usuário pedindo algo","Resposta padrão"(opcional));
`` 


- É importante lembrar de atribuir o retorno do prompt há alguma variável para que a informação não seja perdida.
- A mensagem que virá do prompt será tratada como uma string. Caso queira que seja tratada como um número inteiro, é necessário o uso da função parseInt().

``
var leitura = confirm("Mensagem para perguntar se ele deseja confirmar");
``
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


[Link para for](https://github.com/raulfontenele/Algoritmo-e-Programa-o-de-Computadores/blob/master/Exemplo_Quest%C3%B5es_For/Exemplo_For.html)

