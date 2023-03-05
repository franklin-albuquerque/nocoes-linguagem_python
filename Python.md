# **Python**

## **Variáveis**

+ **int:** números inteiros
+ **float:** pontos flutuantes (números reais)
+ **string:** cadeia de caracteres alfanuméricos
+ **list:** listas
+ **tuple:** tuplas
+ **dict:** dicionários

## Leitura de dados

A leitura de dados em Python é feita utilizando a função embutida “input”:

~~~
variável = input()
~~~

É possível adicionar uma mensagem para ser exibida na solicitação dos dados de entrada. Para isso, deve-se colocar duas aspas dentro da função “input” — as aspas podem ser simples ou duplas. O importante é manter o mesmo padrão de escrita, ou seja, sempre utilizar aspas simples ou aspas duplas.

~~~
variável = input(‘Digite algo: ’)
~~~

## Conversão de variáveis

Por padrão, a variável lida sempre é do tipo “string”. Então, para fazer a conversão para outro tipo de variável, é necessário adicionar o nome do tipo da variável desejada seguida de parênteses e dentro dos parênteses o nome da variável lida:

## variável = int(variável)

Também é possível fazer a conversão durante a leitura dos dados de entrada:

~~~
x = int(input(‘Digite um número: ‘))
~~~

Se for feita uma tentativa de conversão para um tipo de dado diferente daquele que foi solicitado, será exibido um erro de valor — “ValueError”.

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
