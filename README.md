# **Python**

Python é uma linguagem de programação de alto nível, interpretada, orientada a objetos e de propósito geral. Ela é utilizada em uma ampla variedade de aplicações, desde desenvolvimento de software, automação de tarefas, inteligência artificial, análise de dados e desenvolvimento web, entre outros.

## **Variáveis**

Em programação, as variáveis são usadas para armazenar dados na memória do computador. Elas têm um nome e um tipo de dados associado, que determina o que pode ser armazenado nelas.

### **Variáveis básicas**

#### 1. **Variáveis númericas**
+ **int:** corresponde aos números inteiros, positivos ou negativos. Por exemplo: 1, -3, 0, 18.
+ **float:** os pontos flutuantes são números com parte fracionária. Por exemplo: 0.75, -2.0, 1.0, 3.14.

#### 2. **Variáveis booleanas**
+ **bool:** representando as expressões lógicas *verdadeiro* ou *falso* (*True* ou *False*).

#### 3. **Variáveis de texto**
+ **str:** strings são sequências de caracteres, como palavras ou frases.

### **Variáveis compostas**

#### 4. **Variáveis de lista**
+ **list:** listas são coleções ordenadas de valores, que podem ser de diferentes tipos. As listas são definidas utilizando colchetes **[]**, onde os elementos são separados por vírgulas.

#### 5. **Variáveis de tupla**
+ **tuple:** são semelhantes às listas, mas são imutáveis. As tuplas são definidos utilizando parênteses **()**. 

#### 6. **Variáveis de dicionário**
+ **dict:** dicionários são coleções de pares chave-valor, onde cada chave é única e possui um valor correspondente. São definidos utilizando chaves **{}**, com cada par chave-valor sendo separado por vírgula.

## Inicialização de variáveis

A inicialização de uma variável é feita ao atribuir um valor a ela usando o operador de atribuição (=):

~~~
inteiro = 42
ponto_flutuante = 3.14
booleana = True
texto = "Olá, mundo!"
lista = [-4, 1, 6, 2, 0]
tupla = (-4, 1, 6, 2, 0)
dicionário = {'chave1': valor1, 'chave2': valor2}
~~~

## Noções básicas sobre entrada e saída de dados

### Saída

Para exibir uma mensagem ao usuário, utiliza-se a função "print()":

~~~
texto = "Olá, mundo!"
print(texto)
~~~

### Entrada

A entrada de dados em Python é feita utilizando a função "input()" — que recebe como parâmetro uma string.

~~~
entrada = input()
~~~

Para solicitar os dados ao usuário exibindo uma mensagem, deve-se inserir a mensagem entre duas aspas na função "input()" — as aspas podem ser simples ou duplas. Mas é importante manter um padrão de escrita: sempre usar ou aspas simples ou aspas duplas.

~~~
entrada = input(‘Digite algo: ’)
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

