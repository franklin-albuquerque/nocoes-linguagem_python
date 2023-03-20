# **Python**

Python é uma linguagem de programação de alto nível, interpretada, orientada a objetos e de propósito geral. Ela é utilizada em uma ampla variedade de aplicações, desde desenvolvimento de software, automação de tarefas, inteligência artificial, análise de dados e desenvolvimento web, entre outros.


## **Tipos de dados**

Em programação, as variáveis são usadas para armazenar valores temporários na memória do computador. Elas têm um nome e um tipo de dados associado.

### **Primitivos**

+ **int:** corresponde aos números inteiros, como: 1, -3, 0, 18, etc.
+ **float:** os pontos flutuantes são números com parte decimal. Por exemplo: 0.75, -2.0, 1.0, 3.14.
+ **bool:** são as expressões lógicas *verdadeiro* (*True*) ou *falso* (*False*).
+ **str:** strings são sequências de caracteres, como palavras ou frases.

### **Não-primitivos**

+ **list:** listas são coleções ordenadas e mutáveis de valores primitivos. As listas são delimitadas por colchetes __[]__, e seus elementos são separados por vírgulas.
+ **tuple:** tuplas também são coleções de valores primitivos, mas são imutáveis. As tuplas são são delimitadas por parênteses __()__; a separação de seus valores é feita usando vírgulas.
+ **dict:** dicionários são coleções mutáveis de pares chave-valor, onde cada chave é única e possui um valor correspondente. São delimitados por chaves __{}__, e cada par chave-valor é separado por vírgula.


## **Inicialização de variáveis**

Para inicializar uma variável, é necessário definir um nome e atribuir um valor a ele. Para fazer isso, deve-se usar o operador de atribuição (=).

~~~
x = 42
y = 3.14
a = True
b = "Olá, mundo!"
lista = [-4, 1, 6, 2, 0]
tupla = (-4, 1, 6, 2, 0)
dicionário = {'chave': valor, 'chave2': valor2}
~~~

Ao contrário de outras linguagens, Python não exige que o tipo de dados da variável seja declarado antes de inicializá-la. Na linguagem C, por exemplo, para inicializar algumas variáveis, o código ficaria assim:

~~~
int x = 42;
float y = 3.14;
bool a = True;
char b = "Olá, mundo!";
~~~

Algumas regras que devem ser seguidas para a declaração de variáveis:

+ O nome da variável não pode começar com um número.
+ Não pode existir espaços no nome da variável — a separação deve ser feita usando o caractere *underline* (_).
+ O nome não pode conter nenhum dos seguintes caracteres: *'", <> /? | \ ()! @ # $% ^ & * ~ - +*

Obs.: o guia de estilo [PEP8](https://peps.python.org/pep-0008/) recomenda que os nomes de variáveis sejam escritos com letras minúsculos.

## **Noções básicas sobre entrada e saída de dados**

### **Saída**

Para exibir uma mensagem ao usuário, utiliza-se a função __print()__:

~~~
texto = "Olá, mundo!"
print(texto)
~~~

### **Entrada**

A entrada de dados em Python é feita utilizando a função __input()__ — que recebe como parâmetro uma string.

~~~
entrada = input()
~~~

Para solicitar os dados ao usuário exibindo uma mensagem, deve-se inserir a mensagem entre duas aspas na função __input()__ — as aspas podem ser simples ou duplas. Mas é importante manter um padrão de escrita: sempre usar ou aspas simples ou aspas duplas.

~~~
entrada = input(‘Digite algo: ’)
~~~


## **Conversão de variáveis**

Como mencionado anteriormente, os dados de entrada sempre são tratados como sendo strings. Assim, para converter essa string em outro tipo de variável, é necessário usar uma função de conversão. 

Para converter uma string em um número inteiro, usa-se a função __int()__:

~~~
string = "123"
número_inteiro = int(string)
~~~

Para converter uma string em um ponto flutuante, usa-se a função __float()__:

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


## **Tipos de dados**

Para saber o tipo de dados de um determinado valor, usa-se a função __type()__. Essa função retorna o tipo da variável fornecida como parâmetro.

Por exemplo, para verificar o tipo de dados de uma variável chamada __x__, digita-se o seguinte:

~~~
x = 42
print(type(x))
~~~

Será apresentada a seguinte saída:

~~~
<class ‘int’>
~~~

