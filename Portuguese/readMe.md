# 30 Dias de JavaScript

| # Dia |                                                                       Tópicos                                                                        |
| ----- | :-------------------------------------------------------------------------------------------------------------------------------------------------: |
| 01    |                                                             [Introdução](./readMe.md)                                                             |
| 02    |                                               [Tipos de Dados](./02_Day_Data_types/02_day_data_types.md)                                                |
| 03    |                             [Booleanos, Operadores, Data](./03_Day_Booleans_operators_date/03_booleans_operators_date.md)                             |
| 04    |                                            [Condicionais](./04_Day_Conditionals/04_day_conditionals.md)                                             |
| 05    |                                                     [Arrays](./05_Day_Arrays/05_day_arrays.md)                                                      |
| 06    |                                                       [Loops](./06_Day_Loops/06_day_loops.md)                                                       |
| 07    |                                                 [Funções](./07_Day_Functions/07_day_functions.md)                                                 |
| 08    |                                                    [Objetos](./08_Day_Objects/08_day_objects.md)                                                    |
| 09    |                             [Higher Order Functions](./09_Day_Higher_order_functions/09_day_higher_order_functions.md)                              |
| 10    |                                           [Sets and Maps](./10_Day_Sets_and_Maps/10_day_Sets_and_Maps.md)                                           |
| 11    |                      [Destructuring and Spreading](./11_Day_Destructuring_and_spreading/11_day_destructuring_and_spreading.md)                      |
| 12    |                                  [Expressões Regulares](./12_Day_Regular_expressions/12_day_regular_expressions.md)                                  |
| 13    |                             [Método Console Objeto](./13_Day_Console_object_methods/13_day_console_object_methods.md)                              |
| 14    |                                         [Tratamento de Errors](./14_Day_Error_handling/14_day_error_handling.md)                                          |
| 15    |                                                    [Classes](./15_Day_Classes/15_day_classes.md)                                                    |
| 16    |                                                        [JSON](./16_Day_JSON/16_day_json.md)                                                         |
| 17    |                                            [Armazenamento na Web](./17_Day_Web_storages/17_day_web_storages.md)                                             |
| 18    |                                                  [Promises](./18_Day_Promises/18_day_promises.md)                                                   |
| 19    |                                                   [Closure](./19_Day_Closures/19_day_closures.md)                                                   |
| 20    |                                  [Escrevendo Código Limpo](./20_Day_Writing_clean_codes/20_day_writing_clean_codes.md)                                   |
| 21    |                                                          [DOM](./21_Day_DOM/21_day_dom.md)                                                          |
| 22    |                            [Manipulando DOM Objetos](./22_Day_Manipulating_DOM_object/22_day_manipulating_DOM_object.md)                            |
| 23    |                                        [Event Listeners](./23_Day_Event_listeners/23_day_event_listeners.md)                                        |
| 24    |                             [Mini Projeto: Sistema Solar](./24_Day_Project_solar_system/24_day_project_solar_system.md)                              |
| 25    | [Mini Projeto: Visualização de Dados de Paises do mundo](./25_Day_World_countries_data_visualization_1/25_day_world_countries_data_visualization_1.md) |
| 26    | [Mini Projeto: Visualização de Dados de Paises do mundo 2](./26_Day_World_countries_data_visualization_2/26_day_world_countries_data_visualization_2.md) |
| 27    |                             [Mini Projeto: Portfólio](./27_Day_Mini_project_portfolio/27_day_mini_project_portfolio.md)                             |
| 28    |                          [Mini Projeto: Leaderboard](./28_Day_Mini_project_leaderboard/28_day_mini_project_leaderboard.md)                          |
| 29    |             [Mini Projeto: Caracteres Animados](./29_Day_Mini_project_animating_characters/29_day_mini_project_animating_characters.md)             |
| 30    |                                     [Projetos Finais](./30_Day_Mini_project_final/30_day_mini_project_final.md)                                      |

🧡🧡🧡 HAPPY CODING 🧡🧡🧡

<div>
<small>Dê suporte ao <strong>Autor</strong> para criar mais materiais educacionais</small> <br />  
<a href = "https://www.paypal.me/asabeneh"><img src='/images/paypal_lg.png' alt='Paypal Logo' style="width:10%"/></a>
</div>

<div align="center">
  <h1> 30 Dias de JavaScript: Introdução</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>

<sub>Autor:
<a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a><br>
<small> Janeiro, 2020</small>
</sub>

<div>

🇬🇧 [English](../readMe.md)
🇪🇸 [Spanish](../Spanish/readme.md)
🇮🇹 [Italian](../Italian/readMe.md)
🇷🇺 [Russian](../RU/README.md)
🇹🇷 [Turkish](../Turkish/readMe.md)
🇦🇿 [Azerbaijan](../Azerbaijani/readMe.md)
🇰🇷 [Korean](../Korea/README.md)
🇻🇳 [Vietnamese](../Vietnamese/README.md)
🇵🇱 [Polish](../Polish/readMe.md)
🇧🇷 [Portuguese](./readMe.md)

</div>

</div>
</div>

[Dia 2 >>](./02_Day_Data_types/02_day_data_types.md)

![Trinta Dias de JavaScript](/images/day_1_1.png)

- [30 dias de JavaScript](#30-days-of-javascript)
- [📔 Dia 1](#-day-1)
	- [Introdução](#introduction)
	- [Requisitos](#requirements)
	- [Setup](#setup)
		- [Instalação Node.js](#install-nodejs)
		- [Navegador](#browser)
			- [Instalando Google Chrome](#installing-google-chrome)
			- [Abrindo Google Chrome Console](#opening-google-chrome-console)
			- [Escrevendo Código no Browser Console](#writing-code-on-browser-console)
				- [Console.log](#consolelog)
				- [Console.log com Múltiplos Argumentos](#consolelog-with-multiple-arguments)
				- [Comentários](#comments)
				- [Sintaxe](#syntax)
			- [Aritimética](#arithmetics)
		- [Editor de Código](#code-editor)
			- [Instalando Visual Studio Code](#installing-visual-studio-code)
			- [Como usar o Visual Studio Code](#how-to-use-visual-studio-code)
	- [Adicionando JavaScript na Web Page](#adding-javascript-to-a-web-page)
		- [Script em Linha](#inline-script)
		- [Script Interno](#internal-script)
		- [Script Externo](#external-script)
		- [Multiplo Scripts Externos](#multiple-external-scripts)
	- [Introdução Tipo de Dados](#introduction-to-data-types)
		- [Números](#numbers)
		- [Strings](#strings)
		- [Booleanos](#booleans)
		- [Undefined](#undefined)
		- [Null](#null)
	- [Verificando Tipo de Dados](#checking-data-types)
	- [Novamente Comentarios](#comments-again)
	- [Variáveis](#variables)
- [💻 Dia 1: Exercícios](#-day-1-exercises)

# 📔 Dia 1

## Introdução

**Parabéns** Em decidir de participar desafio dos 30 dias de JavaScript. Neste desafio você aprenderá tudo que precisa para ser um programador JavaScript, e em general, todo o conceito de programação. No fim do desafio voce estará adquirindo o Certificado de conclusão do desafio 30DaysOfJavaScript. Em caso de precisar de ajuda ou se preferir ajudar outros você pode entrar no [Grupo Telegram](https://t.me/ThirtyDaysOfJavaScript).

**30DaysOfJavaScript** desafio é um guia tanto para iniciantes e Avançados JavaScript Desenvolvedores, Bem vindo ao JavaScript. JavaScript é a linguagem da internet. Eu me divirto em usar e ensinar JavaScript e eu acredito que voce fará tambem.

Neste passo a passo do desafio JavaScript, você aprenderá JavaScript, a mais popular linguagem de programação da história da humanindade.
JavaScript é usado **_para adicionar interatividade aos websites, desenvolvimento de mobile apps, desktop aplicações, jogos_** e nos dias de hoje JavaScript pode ser usado para **_machine learning_** e **_AI_**.
**_JavaScript (JS)_** Teve um aumento na popularidade nos últimos anos e segue como a linguagem de programação líder por seis anos consecutivos e é a linguagem de programação mais usada no GitHub

## Requisitos

Sem conhecimentos prévios de programação é exigido para seguir este desafio. Precisará apenas:
1. Motivação
2. Um computador
3. Internet
4. Um navegador
5. Um editor de Código

## Setup

Eu acredito que voce tem a motivação e o forte desejo de ser um desenvolvedor, um computador e internet. Se voce tem isso, então você tem tudo para iniciar.

## Instalando Node.js

Você pode não precisar do Node.js agora mas você precisará mais tarde. Instalação do [node.js](https://nodejs.org/en/).

![Node download](/images/download_node.png)

Depois do download click duplo no ícone e intalar

![Instalação node](/images/install_node.png)

Nós podemos verificar se o Node está instalador na nossa máquina local abrindo nosso terminal do dispositivo ou prompt de comando.

```sh
asabeneh $ node -v
v12.14.0
```

Enquanto fazia este tutorial eu estava usando a versão 12.14.0 do Node, mas agora a recomendada versão do Node.js para dowload é v14.17.6, pelo tempo que você usar este material pode haver versão mais atual do Node.js.

### Navegador

Existe muitos navegadores por ai, Entento, Eu fortemente recomento o Google Chrome.

#### Instalando Google Chrome

Instalar o [Google Chrome](https://www.google.com.br/chrome/) se você não tem um ainda. Nós podemos escrever um pequeno código de JavaScript no console do browser, mas nós não usamos o console do navegador para desenvolver aplicações.

![Google Chrome](/images/google_chrome.png)

#### Abrindo o Google Chrome Console

Você pode abrir o Google Chrome console por um ou outro clicando nos 3 pontos no topo do lado direito do navegador, selecionando _Mais ferramentas -> Ferramenta para desenvolvedores ou usando o atalho do teclado. Eu prefiro os atalhos.

![Abrindo o chrome](/images/opening_developer_tool.png)

Para abrir o console do Chrome usando o atalho do teclado.

```sh
Mac
Command+Option+J

Windows/Linux:
Ctl+Shift+J
```

![Abrindo o console](/images/opening_chrome_console_shortcut.png)

Depois de você abrir o console do Google Chrome, tente explorar os botões marcados. Nós vamos passar a maior parte do tempo no Console. O Console é o lugar onde vai seu código de JavaScript. O Console do Google Chrome V8 engine muda seu codigo de JavaScript para código de máquina.
Vamos escrever códigos de JavaScript no Google Chome console: 

![Escrevendo codigo no console](/images/js_code_on_chrome_console.png)

#### Escrevendo Código no console do Navegador

Nós podemos escrever qualquer código de JavaScript no console do Google Chrome ou qualquer outro console de navegador, para este desafio, nós vamos focar no Console do Google Chrome. Abra o Console usando: 

```sh
Mac
Command+Option+I

Windows:
Ctl+Shift+I
```

##### Console.log

Para escrever nosso primeiro código em JavaScript, vamos usar uma função built-it  **console.log()**. Nós passamos um argumento como dados de input, e a função mostra o output. Nós passamos `'Olá, Mundo!'` como dados de input ou argumento na função console.log(). 

```js
console.log('Olá, Mundo!')
```

##### Console.log com Múltiplos Argumentos

A funçao **`console.log()`** pode receber múltiplos parâmetros separados por vírgulas. A sintaxe é similar ao seguinte modo:**`console.log(param1, param2, param3)`** 

![console.log com Múltiplos Argumentos](/images/console_log_multipl_arguments.png)

```js
console.log('Olá', 'Mundo', '!')
console.log('Feliz', 'Ano', 'Novo', 2020)
console.log('Bem vindo', 'aos', 30, 'Dias', 'de', 'JavaScript')
```

Como você pode ver pelo trecho de código acima,  _`console.log()`_ pode receber múltiplos argumentos.

Parabéns! Você escreveu seu primeiro código de JavaScript usando _`console.log()`_.

##### Comentários

Nós podemos adicionar comentários para nosso código. Comentários são importantes para facilitar a leitura do código e deixar observações. O JavaScript não executa as partes com comentário no nosso código. No JavaScript, qualquer linha de texto começando com // é um comentário, e tudo anexo como isto `//` tambem é um comentário.

**Exemplo: Comentário de linha única**

```js
// Este é o primeiro comentário  
// Este é o segundo comentário
// Eu sou um comentário de linha única
```

**Exemplo: Comentários Várias Linhas**

```js
/*
  Isto é um comentário de várias linhas  
  Várias linhas de comentários.
  JavaScript é a Linguagem da Web
 */
```
##### Sintaxe

Linguagens de programação são similares com a linguagem humana. Portugês ou qualquer outra linguagem usa palavras, frases, orações, períodos, e outras mais para criar uma mensagem com significado. A definição em Português de sintaxe é _ Estrutura essencial para que frases, orações e períodos façam sentido e sejam de fácil compreensão por parte do leitor_. A definição técnica é a estrutura de declarações em uma linguagem de computador. Linguagens de programação tem sintaxes. JavaScript é uma linguagem de programação como outras linguagens de programação tem sua própria sintaxe. Se nós nao escrevermos uma sintaxe que JavaScript entenda, diferentes tipos de errors aparecerá. Nós iremos explorar diferentes tipos de errors no JavaScript depois. Por enquanto, vamos ver sintaxes de errors.

![Error](images/raising_syntax_error.png)

Eu fiz uma confusão proposital. Como resultado, criou vários errors. Na realidade, a sintaxe é muito informativa. Informa quais tipos de errors foi feito. lendo  as mensagens do feedback de error, nós podemos corrigir a sintaxe e resolver o problema. O processo de identificar e remover errors de um programa é chamado de Debugging. Vamos resolver os errors:

```js
console.log('Olá, Mundo!')
console.log('Olá, Mundo!')
```

Até agora, nós vimos como exibir texto usando o _`console.log()`_. Se estamos imprimindo texto ou string usando _`console.log()`_, o texto tem que estar dentro de uma aspa simples, aspas duplas, ou crase.

**Exemplo:**

```js
console.log('Olá, Mundo!')
console.log("Olá, Mundo!")
console.log(`Hello, World!`)
```

#### Aritimética

Agora, vamos praticar escrevendo mais códigos JavaScript usando _`console.log()`_ no console do Google Chrome para números e tipos de dados.
Em adição ao texto, nós podemos tamem fazer calculos matemáticos usando javaSCript. Vamos fazer calculos simples a seguir.
É possivel escrever códigos JavaScript no console do Google Chome diretamente sem o função **_`console.log()`_** Entretanto, está incluso nesta introdução porque maior parte deste desafio pode ocorrer no editor de texto onde o uso de funcões pode ser mantario. Você pode brincar diretamente com ins

![Arithmetic](/images/arithmetic.png)

```js
console.log(2 + 3) // Adição
console.log(3 - 2) // Subtração
console.log(2 * 3) // Muiltiplição
console.log(3 / 2) // Divisão
console.log(3 % 2) // Modulo - Resto da divisão
console.log(3 ** 2) // Exponenciação 3 ** 2 == 3 * 3
```

### Editor de Código

Nós podemos escrever nosso código no console do navegador. mas isso nao é usado para grandes projetos. No anbiente real de trabalho, desenvolvedores usam diferentes editores para escrever seus códigos. Neste desafio 30 dias de JavaScript, nós iremos utilizar o Visual Studio Code.

#### Instalando o Visual Studio Code

Visual Studio Code é editor de texto open-source muito popular. Eu poderia recomendar o [download Visual Studio Code](https://code.visualstudio.com/), mas se você está familiarizado com outro editor, sinta livre para seguir oque você tem.

![Vscode](/images/vscode.png)

Se você instalou o Visual Studio Code, Vamos começar usando-o.

#### Como Usar Visual Studio Code

Abra o Visual Studio Code clicando duas vezes com o mouse no ícone. Quando abrir, você terá esta interface. Tente interagir com os ícones rotulados.

![Vscode ui](/images/vscode_ui.png)

![Vscode add project](/images/adding_project_to_vscode.png)

![Vscode open project](/images/opening_project_on_vscode.png)

![script file](/images/scripts_on_vscode.png)

![Installing Live Server](/images/vsc_live_server.png)

![running script](/images/running_script.png)

![coding running](/images/launched_on_new_tab.png)

## Adicionando JavaScript Para uma Página na Web 

JavaScript pode ser adicionado para uma página na internet em três diferentes maneiras:

- **_Script em linha_**
- **_Script Interno_**
- **_Script Externo_**
- **_Múltiplos Scripts Externos_**

As diferentes sessões mostra diferentes maneiras de adicionar códigos JavaScript para sua página na web.

### Inline Script

Crie uma pasta do projeto no seu desktop ou em qualquer localização, nomeie de 30DaysOfJS e crie um **_`index.html`_** documento na sua pasta do projeto.
Então copie os seguintes códigos e abra-o no navegador, por exemplo [Chrome](https://www.google.com/chrome/).


```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>30DaysOfScript: Script em linha</title>
  </head>
  <body>
    <button onclick="alert('Welcome to 30DaysOfScript!')">Clique</button>
  </body>
</html>
```
Agora, você escreveu seu primeiro script em linha. Nós podemos criar uma mensagem pop up usando o _`alert()`_ função built-it

### Script Interno

O script interno pode ser escrito no _`head`_ ou _`body`_, mas é preferível colocar no body do documento HTML.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>30DaysOfScript: Script Interno</title>
    <script>
      console.log('Welcome to 30DaysOfJavaScript')
    </script>
  </head>
  <body></body>
</html>
```

Isto é como nós escrevemos scripts internos na maioria das vezes. Escrevemos o código de JavaScript na sessão body é a mais preferida opção. Abra o console do navegador e veja o output do `console.log()`.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>30DaysOfScript: Internal Script</title>
  </head>
  <body>
    <button onclick="alert('Welcome to 30DaysOfJavaScript!');">Click</button>
    <script>
      console.log('Welcome to 30DaysOfJavaScript')
    </script>
  </body>
</html>
```

Abra o console do navegador e veja o output do `console.log()`.

![js code from vscode](/images/js_code_vscode.png)

### Script Externo

Similar com o script interno, o link do script externo pode estar no header ou body, mas é mais indicado colocar no body do documento.
Primeiro, nós podemos criar scripts externos de JavaScript com a .js extensão. Todos os arquivos terminados com a .js extensão são JavaScript documentos. Crie uma pasta nomeada Introdução.js dentro do diretório do projeto e escreva o seguinte código e copie o link do arquivo .js no bottom do body.

```js
console.log('Welcome to 30DaysOfJavaScript')
```

Scripts Externo no _head_:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>30DaysOfJavaScript: Script Externo</title>
    <script src="introduction.js"></script>
  </head>
  <body></body>
</html>
```

Scripts Externo no _body_:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>30DaysOfJavaScript: Scripts Externo</title>
  </head>
  <body>
    

    <!-- JavaScript link externo pode estar no header ou no body --> 
    <!-- Antes do fechamento da tag do body é o lugar recomendado para colocar o script do JavaScript externo --> 
    <script src="introduction.js"></script>
  </body>
</html>
```

Abra o console do navegador para ver o output do `console.log()`.

### Múltiplos Scripts Externo

Nós tambem podemos colocar o link de vários arquivos externos de JavaScript em uma página web.
Crie um `helloworld.js` documento dentro da pasta 30DaysOfJS e escreva o seguinte código.

```js
console.log('Olá, Mundo!')
```

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Múltiplos Scripts Externo</title>
  </head>
  <body>
    <script src="./helloworld.js"></script>
    <script src="./introduction.js"></script>
  </body>
</html>
```

_Seu arquivo main.js deve estar abaixo de todos os outros scripts_. E isto é muito importante de relembrar

![Multiple Script](/images/multiple_script.png)

## Introdução a tipo de Dados

Em JavaScript e tambem em outras linguagens de programação, existem vários tipos de dados. Os seguintes são tipos de dados primitivos do JavaScript: _String, Number, Boolean, undefined, Null_, and _Symbol_.

### Number

- Integers: Inteiros (Negativo, zero e positivos) números
Examplo:
  ... -3, -2, -1, 0, 1, 2, 3 ...
- Float-point numbers: Números decimais.
  ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...

### Strings

Uma coleção de um ou mais caracteres entre duas aspas simples, aspas duplas, ou crase.

**Examplo:**

```js
'a'
'Asabeneh'
"Asabeneh"
'Finland'
'JavaScript is a beautiful programming language'
'I love teaching'
'I hope you are enjoying the first day'
`We can also create a string using a backtick`
'A string could be just as small as one character or as big as many pages'
'Any data type under a single quote, double quote or backtick is a string'
```

### Booleans

Um valor boleano ou é verdadeiro ou falso. Qualquer comparação retorna um valor booleano, que pode ser entre verdadeiro ou falso.

Um tipo de dado boleanno é verdadeiro ou um valor falso

**Examplo:**

```js
true // if the light is on, the value is true
false // if the light is off, the value is false
```

### Undefined

Em JavaScript, se nós não atribuirmos um valor a uma variável, o valor é undefined. Em adição a isto, se uma funcção não está retornando nada, ela retorna undefined

```js
let firstName
console.log(firstName) // undefined, because it is not assigned to a value yet
```

### Null

Null em JavaScript significa um valor vazio.

```js
let emptyValue = null
```

## Verificando Tipos de Dados

Para verificar o tipo de dado de uma determinada variavel, no usamos o operador **typeof**. Veja o seguinte exemplo.  

```js
console.log(typeof 'Asabeneh') // string
console.log(typeof 5) // number
console.log(typeof true) // boolean
console.log(typeof null) // object type
console.log(typeof undefined) // undefined
```

## Comentários de novo

Remember that commenting in JavaScript is similar to other programming languages. Comments are important in making your code more readable.
There are two ways of commenting:

- _Single line commenting_
- _Multiline commenting_

```js
// commenting the code itself with a single comment
// let firstName = 'Asabeneh'; single line comment
// let lastName = 'Yetayeh'; single line comment
```

Multiline commenting:

```js
/*
  let location = 'Helsinki';
  let age = 100;
  let isMarried = true;
  This is a Multiple line comment
*/
```

## Variables

Variables are _containers_ of data. Variables are used to _store_ data in a memory location. When a variable is declared, a memory location is reserved. When a variable is assigned to a value (data), the memory space will be filled with that data. To declare a variable, we use _var_, _let_, or _const_ keywords.

For a variable that changes at a different time, we use _let_. If the data does not change at all, we use _const_. For example, PI, country name, gravity do not change, and we can use _const_. We will not use var in this challenge and I don't recommend you to use it. It is error prone way of declaring variable it has lots of leak. We will talk more about var, let, and const in detail in other sections (scope). For now, the above explanation is enough.

A valid JavaScript variable name must follow the following rules:

- A JavaScript variable name should not begin with a number.
- A JavaScript variable name does not allow special characters except dollar sign and underscore.
- A JavaScript variable name follows a camelCase convention.
- A JavaScript variable name should not have space between words.

The following are examples of valid JavaScript variables.

```js
firstName
lastName
country
city
capitalCity
age
isMarried

first_name
last_name
is_married
capital_city

num1
num_1
_num_1
$num1
year2020
year_2020
```

The first and second variables on the list follows the camelCase convention of declaring in JavaScript. In this material, we will use camelCase variables(camelWithOneHump). We use CamelCase(CamelWithTwoHump) to declare classes, we will discuss about classes and objects in other section.

Example of invalid variables:

```js
  first-name
  1_num
  num_#_1
```

Let us declare variables with different data types. To declare a variable, we need to use _let_ or _const_ keyword before the variable name. Following the variable name, we write an equal sign (assignment operator), and a value(assigned data).

```js
// Syntax
let nameOfVariable = value
```

The nameOfVriable is the name that stores different data of value. See below for detail examples.

**Examples of declared variables**

```js
// Declaring different variables of different data types
let firstName = 'Asabeneh' // first name of a person
let lastName = 'Yetayeh' // last name of a person
let country = 'Finland' // country
let city = 'Helsinki' // capital city
let age = 100 // age in years
let isMarried = true

console.log(firstName, lastName, country, city, age, isMarried)
```

```sh
Asabeneh Yetayeh Finland Helsinki 100 true
```

```js
// Declaring variables with number values
let age = 100 // age in years
const gravity = 9.81 // earth gravity  in m/s2
const boilingPoint = 100 // water boiling point, temperature in °C
const PI = 3.14 // geometrical constant
console.log(gravity, boilingPoint, PI)
```

```sh
9.81 100 3.14
```

```js
// Variables can also be declaring in one line separated by comma, however I recommend to use a seperate line to make code more readble
let name = 'Asabeneh', job = 'teacher', live = 'Finland'
console.log(name, job, live)
```

```sh
Asabeneh teacher Finland
```

When you run _index.html_ file in the 01-Day folder you should get this:

![Day one](/images/day_1.png)

🌕 You are amazing! You have just completed day 1 challenge and you are on your way to greatness. Now do some exercises for your brain and muscle.

# 💻 Day 1: Exercises

1. Write a single line comment which says, _comments can make code readable_
2. Write another single comment which says, _Welcome to 30DaysOfJavaScript_
3. Write a multiline comment which says, _comments can make code readable, easy to reuse_
   _and informative_

4. Create a variable.js file and declare variables and assign string, boolean, undefined and null data types
5. Create datatypes.js file and use the JavaScript **_typeof_** operator to check different data types. Check the data type of each variable
6. Declare four variables without assigning values
7. Declare four variables with assigned values
8. Declare variables to store your first name, last name, marital status, country and age in multiple lines
9. Declare variables to store your first name, last name, marital status, country and age in a single line
10. Declare two variables _myAge_ and _yourAge_ and assign them initial values and log to the browser console.

```sh
I am 25 years old.
You are 30 years old.
```

🎉 CONGRATULATIONS ! 🎉

[Dia 2 >>](./02_Day_Data_types/02_day_data_types.md)
