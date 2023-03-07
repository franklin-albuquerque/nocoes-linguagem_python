# **Python**

Python é uma linguagem de programação de alto nível, interpretada, orientada a objetos e de propósito geral. Ela é utilizada em uma ampla variedade de aplicações, desde desenvolvimento de software, automação de tarefas, inteligência artificial, análise de dados e desenvolvimento web, entre outros.

## **Variáveis**

Em programação, as variáveis são usadas para armazenar dados na memória do computador. Elas têm um nome e um tipo de dados associado, que determina o que pode ser armazenado nelas.

+ **int:** números inteiros
+ **float:** pontos flutuantes (números reais)
+ **string:** cadeia de caracteres alfanuméricos
+ **list:** listas
+ **tuple:** tuplas
+ **dict:** dicionários

## Leitura de dados

A leitura de dados em Python é feita utilizando a função “input()” — que recebe como parâmetro uma string:

~~~
string = input()
~~~

É possível exibir uma mensagem na solicitação dos dados de entrada. Para isso, deve-se inserir duas aspas dentro da função "input()" — as aspas podem ser simples ou duplas. Mas é recomendado manter um padrão de escrita: sempre usar ou aspas simples ou aspas duplas.

~~~
string = input(‘Digite algo: ’)
~~~

## Conversão de variáveis

Como mencionado anteriormente, os dados de entrada sempre são tratados como sendo strings. Assim, para converter essa string em outro tipo de variável, é necessário usar uma função de conversão. 

Para converter uma string em um número inteiro, usa-se a função "int()":

~~~
string = "123"
número_inteiro = int(string)
~~~

Para converter uma string em um ponto flutuante, usa-se a função "float()":

~~~
string = "7.2"
ponto_flutuante = float(string)
~~~

Também é possível fazer, simultaneamente, a leitura e conversão dos dados:

~~~
número = int(input(‘Digite um número: ‘))
~~~

No exemplo acima, caso o usuário informe um valor que não corresponda a um número inteiro, será exibida a seguinte mensagem de erro:

~~~
ValueError: invalid literal for int() with base 10
~~~

## Tipos de dados

Para verificar o tipo de uma variável "x", usa-se a função "type()":

~~~
x = 42
print(type(x))
~~~

Será exibida a seguinte mensagem:

~~~
<class ‘int’>
~~~

