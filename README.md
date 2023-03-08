# **Python**

Python é uma linguagem de programação de alto nível, interpretada, orientada a objetos e de propósito geral. Ela é utilizada em uma ampla variedade de aplicações, desde desenvolvimento de software, automação de tarefas, inteligência artificial, análise de dados e desenvolvimento web, entre outros.

## **Variáveis**

Em programação, as variáveis são usadas para armazenar dados na memória do computador. Elas têm um nome e um tipo de dados associado, que determina o que pode ser armazenado nelas.

### **Variáveis simples**
+ **Inteiros (int):** são números inteiros, positivos ou negativos, sem parte fracionária. Por exemplo: 1, -3, 0, 18.
+ **Números de ponto flutuante (float):** são números com parte fracionária, representado com um ponto decimal. Por exemplo: 0.75, -2.0, 1.0, 3.14.
+ **Booleanos (bool):** são expressões lógicas, cujo valor pode ser *verdadeiro* ou *falso* (*True* ou *False*).

### **Variáveis sequenciais**
+ **Strings (str):** strings são sequências de caracteres, como palavras ou frases.
+ **Listas (list):** listas são coleções ordenadas de valores, que podem ser de diferentes tipos. As listas são definidas utilizando colchetes **[]**, onde os elementos são separados por vírgulas.
+ **Tuplas (tuple):** são semelhantes às listas, mas são imutáveis. As tuplas são definidos utilizando parênteses **()**. 
+ **Dicionários (dict):** dicionários são coleções de pares chave-valor, onde cada chave é única e possui um valor correspondente. São definidos utilizando chaves **{}**, com cada par chave-valor sendo separado por vírgula.

### Inicialização de variáveis

A inicialização de uma variável é feita ao atribuir um valor a ela usando o operador de atribuição (=):

Por exemplo, para inicializar uma variável "x" com valor 42, digita-se o seguinte:

~~~
x = 42
~~~

Também é possível inicializar mais de uma variável de uma só vez:

~~~
a, b, c, d = 1, 2, 3, 4
~~~

## Noções básicas sobre entrada e saída de dados

### Saída

Para exibir uma mensagem ao usuário, utiliza-se a função "print()":

~~~
string = "Olá, mundo!"
print(string)
~~~

### Entrada

A entrada de dados em Python é feita utilizando a função "input()". Por padrão, o "input()" recebe como parâmetro uma string.

~~~
string = input()
~~~

Para solicitar os dados ao usuário exibindo uma mensagem, deve-se inserir a mensagem entre duas aspas na função "input()" — as aspas podem ser simples ou duplas. Mas é importante manter um padrão de escrita: sempre usar ou aspas simples ou aspas duplas.

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

Para saber o tipo de dados de um determinado valor, usa-se a função "type()". Essa função retorna o tipo da variável fornecida como parâmetro.

Por exemplo, para verificar o tipo de dados de uma variável chamada "x", digita-se o seguinte:

~~~
x = 42
print(type(x))
~~~

Será exibida a seguinte mensagem:

~~~
<class ‘int’>
~~~

