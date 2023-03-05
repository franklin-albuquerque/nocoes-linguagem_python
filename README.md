# **Python**

## **Variáveis**

+ **int:** números inteiros
+ **float:** pontos flutuantes (números reais)
+ **string:** cadeia de caracteres alfanuméricos
+ **list:** listas
+ **tuple:** tuplas
+ **dict:** dicionários

## Leitura de dados

A leitura de dados em Python é feita utilizando a função embutida “input()”:

~~~
variável = input()
~~~

É possível adicionar uma mensagem para ser exibida na solicitação dos dados de entrada. Para isso, deve-se inserir duas aspas dentro da função “input()” — as aspas podem ser simples ou duplas. O importante é manter o mesmo padrão de escrita: sempre usar ou aspas simples ou aspas duplas.

~~~
variável = input(‘Digite algo: ’)
~~~

## Conversão de variáveis

Por padrão, as variáveis lidas sempre são do tipo “string”. Então, para converter uma "string" em outro tipo de variável, é preciso inserir o nome dado à váriável lida dentro da função de conversão desejada. Por exemplo:

~~~
número = input('Digite um número: ')
número = int(número)
~~~

Também é possível fazer a leitura e conversão dos dados simultaneamente:

~~~
número = int(input(‘Digite um número: ‘))
~~~

No caso acima, se for inserido um valor que não seja um número inteiro, será exibida a seguinte mensagem de erro:

~~~
ValueError: invalid literal for int() with base 10
~~~

## Tipos de dados

Se uma variável “x” tiver um valor inteiro, pode-se usar a função “type” para verificar o tipo de “x”:

~~~
x = 42
print(type(x))
~~~

Será exibida a seguinte mensagem:

~~~
<class ‘int’>
~~~

