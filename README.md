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
string = input()
~~~

É possível adicionar uma mensagem para ser exibida na solicitação dos dados de entrada. Para isso, deve-se inserir duas aspas dentro da função “input()” — as aspas podem ser simples ou duplas. O importante é manter o mesmo padrão de escrita: sempre usar ou aspas simples ou aspas duplas.

~~~
string = input(‘Digite algo: ’)
~~~

## Conversão de variáveis

Por padrão, as variáveis lidas sempre são do tipo string. Então, para converter uma string em outro tipo de variável, é preciso inserir o nome dado à váriável lida dentro da função de conversão desejada. Por exemplo:

Para converter uma string em número inteiro, é necessário usar a função "int()":

~~~
string = "123"
número_inteiro = int(string)
~~~

Para converter uma string em um ponto flutuante, é necessário usar a função "float()":

~~~
string = "7.2"
ponto_flutuante = float(string)
~~~

Também é possível fazer a leitura e conversão dos dados simultaneamente:

~~~
número = int(input(‘Digite um número: ‘))
~~~

No exemplo acima, se for inserido um valor que não seja um número inteiro, será exibida a seguinte mensagem de erro:

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

