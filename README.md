# Markdown - Sintaxe


# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

# Parágrafo
Para fazer um paragrafo como este, basta digitar normalmente.  
Mas para quebrar a linha entre um parágrafo, é necessário inserir dois espaços.

Caso queira uma quebra de linha maior, para iniciar outro parágrafo, é necessário dois enters.



# Ênfase

## Negrito 1
Para usar **Negrito** bastar adicionar dois asteriscos (*) no início e no final da palavra ou sentença.


## Negrito 2
Outra forma de utilizar o __negrito__ seria utilizando dois underlines (_) no início e no final da palavra.


## Itálico 1
Para usar *Itálico* bastar adicionar um asteriscos (*) no início e no final da palavra ou sentença.


## Itálico 2
Outra forma de utilizar o _itálico_ seria utilizando um underlines (_) no início e no final da palavra ou sentença.


## Negrito e Itálico
Para usar ***Negrito*** e ***Itálico*** bastar adicionar três asteriscos (*) no início e no final da palavra ou sentença.


## Negrito e Itálico 2
Outra forma de utilizar **_Negrito_** e __*Itálico*__ seria mesclando os underlines (_) e asteriscos (*) no início e no final da palavra ou sentença.


## Riscado
Para colocar um ~~riscado~~ na palavra ou sentença bastar adicionar dois tis (~) no início e no final da palavra ou sentença.


## Citação
> Para fazer um **comentário** _(citação)_, basta colocar um simbolo de maior (>) no início da sentença.



# Linhas horizontais
Para utilizar linhas horizontais, deve-se colocar a partir de três asteriscos (*), três traços (-) ou três underlines (-), juntos ou sepados.
***
---
___
* * * * *
- - - - -
_________



# Listas

## Lista não ordenada
Para se criar uma lista não ordenada, utiliza-se um asterisco (*), um traço (-) ou um sinal de mais (+) na frente de cada sentença.

* Item 01
* Item 02
* Item 03
- Item 04
- Item 05
- Item 06
+ Item 07
+ Item 08
+ Item 09

Para destacar Sub-itens na lista basta dar um Tab nos sub-itens.

* Item 01
    * Sub-Item 01
    * Sub-Item 02
* Item 02



## Lista ordenada
Para se criar uma lista ordenada, utiliza-se numeros seguido de um ponto (.), veja que o que leva a ordenação da lista é o primeiro número utilizado para ordena-la, independente do número usado após o primeiro.

1. Item 01
1. Item 02
1. Item 03

__

8. Item 01
4. Item 02
1. Item 03

__

Para não identificar uma lista como lista ordenada, mesmo utilizando um valor seguido de um ponto (.) (como no exemplo os países que ganharam a copa e o ano em que foi ganha), é necessário colocar uma barra invertida (\\) antes do ponto (.), e para fazer a quebra de linha utiliza-se dois espaços após.

1194\. Brasil  
1998\. França  
2002\. Brasil  



# Links
Para transformar textos em links utiliza-se colchetes [ ] e parênteses ( ). Dentro dos colchetes [ ] coloca-se o texto que deseja mostrar, e dentro dos parênteses ( ) coloca-se o endereço do link que deseja acessar. Não há espaço entre o colchete e o parêntese.

[Texto Aqui](https://www.google.com/)


Para colocar um texto alternativo para aparecer quando deixar o mouse sobre o link, pasta inserir um expaço e adicionar o texto que deseja entre aspas, após o link.

[Texto Aqui](https://www.google.com/ "Página do Google")

Também pode utilizar variável para mostrar um link, basta atribuir uma variável utilizando seu nome entre colchetes [ ] seguido de dois pontos : e o link. Após isso utiliza-se dois pares de colchetes, um com o nome do link, e o outro com o nome da variável.

[site-url]: https://www.google.com/ "Página do Google"

[Texto Aqui][site-url]



# Imagens

Para colocar uma imagem basta inserir uma exclamação (!) seguida de um par de colchetes [ ] e parênteses ( ). Dentro dos colchetes [ ] coloca-se o texto que deseja exibir ao deixar o mouse sobre a imagem, e dentro dos parênteses ( ) coloca-se o endereço da imagem.

![Markdown](https://markdown-here.com/img/logo-2015/austin.png)
> Logo do site https://markdown-here.com


## Imagem com variável
Também pode utilizar variável para mostrar uma imagem, basta criar uma variável utilizando seu nome entre colchetes [ ] seguido de dois pontos : e o link. Após isso utiliza-se exclamação (!) seguido de dois pares de colchetes, um com o nome do link, e o outro com o nome da variável.

[imagem]: https://image.flaticon.com/icons/svg/25/25231.svg

![GitHub][imagem]


## Imagem com link
Para colocar uma imagem com o link, para quando o usuário clicar na imagem abrir o navegador no link desejado, basta você colocar entre colchetes [] a mesma sentença usada para colocar uma imagem normal, que é: exclamação (!) seguida de um par de colchetes [ ] e parênteses ( ). Dentro dos colchetes [ ] coloca-se o texto que deseja exibir ao deixar o mouse sobre a imagem, e dentro dos parênteses ( ) coloca-se o endereço da imagem. Após essa sentença você adiciona o link que deseta dentro de um par de parenteses ().

[![Angular](https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/21_Angular_logo_logos-512.png)](https://angular.io)

## Imagem com link e variável
Também pode utilizar imagem, link e variáveis para mostrar a imagem e direcionar a um site quando o usuário clicar na imagem. Para isso basta criar uma variável utilizando seu nome entre colchetes [ ] seguido de dois pontos : e o endereço da imagem. Em seguida, crie uma variável utilizando seu nome entre colchetes [ ] seguido de dois pontos : e o endereço da url que quer direcionar ao clicar. Após isso, coloque entre colchetes [ ] a seguinte sentença: exclamação (!) seguido de dois pares de colchetes, o primeiro com o nome que deseja aparecer ao deixar o mouse sobre a imagem, e o segundo com o nome da variável que contém o endereço da imagem. Após essa sentença e o fechamento do colchete superior, abra novamente um outro par de colchetes [ ] e coloque o nome da variável que contém a URL que deseja direcionar.

[endereco-imagem]: https://cdn2.iconfinder.com/data/icons/nodejs-1/512/nodejs-512.png

[endereco-node]: https://nodejs.org/en/

[![NodeJS][endereco-imagem]][endereco-node]



# Tabelas
Para criar tabela, utilizasse Pipe (|) para separar os campos, e é necessário fazer uma linha abaixo do cabeçalho da tabela, com Pipe (|), separando o Pipe (|) por traços (-) para o Markdown identificar como tabela. É necessário ter a mesma quantidade de separações do Pipe (|) com traços (-) na segunda linha, que tem em campos na primeira (cabeçalho). E para separar os valores em colunas, também se usa Pipe (|) entre os valores.
Obs: Por estética, pode se usar mais de um traço (-), fazendo a escrita do código fonte da tabela ficar uniforme. 

| Nome | Idade |
| ---- | ----- |
| João |  30   |
| Maria|  40   |

## Alinhamento da Tabela
Por padrão, o _alinhamento_ das células da tabela é a esquerda. O alinhamento é feito por dois pontos : na segunda coluna. Se colocar os dois pontos : a esquerda do traço (-), significa que o alinhamento ficará a esquerda. Se colocar os dois pontos : a esquerda e a direita do traço (-), significa que o alinhamento será centralizado. Se colocar os dois pontos : a direita do traço (-), significa que o alinhamento será a direita.

 ### Centralizado
| Nome | Idade | Profissão |
| :----: | :-----: | :---------: |
| Joao | 30    | Programador |
| Maria| 40    | Dentista |
| Marcio | 21  | Estudante |
| Guilherme | 25 | Marceneiro |

### A Direita
| Nome | Idade | Profissão |
| ----: | -----: | ---------: |
| Joao | 30    | Programador |
| Maria| 40    | Dentista |
| Marcio | 21  | Estudante |
| Guilherme | 25 | Marceneiro |


# Códigos

## Exemplo em linha
Para destacar palavras com fonte de código, basta utilizar craze (`) no início e no final da palavra ou sentença.

Exemplo: Informe o `Login` e a `Senha` para a função `login()`.

Ha alguns momentos em que a utilização da crase (`) prejudicará a escrita de um código completo no Markdown. Um exemplo é no JavaScript, onde a crase faz parte da sintaxe do código, e quando você utilizar para destacar esse código no Markdown, ficará prejudicada a elegibilidade da escrita.

Para contornar isso basta utilizar duas crases (`) no início, e duas no final da sentença. Assim será mostrado corretamente a crase onde estiver sendo usada no código.

Exemplo: ``const message = `Meu nome é ${nome}`;``

## Exemlpo em bloco
Pode-se destacar todo um bloco de código utilizando o TAB nesse bloco.

    // login.js

    const username = 'joaosilva';
    const password = 'secret';

    login (username, password);

Também pode destacar sem utilizar o TAB. Basta colocar três crases (```) no início e três no final do bloco.

```
// login.js

const username = 'joaosilva';
const password = 'secret';

login (username, password);
```

## Syntax Highlighting
Para "acender" o bloco de código, informando qual linguágem é a escrita do código, basta escrever o nome da linguágem ou um alias (js para JavaScript) após as três primeiras crases (```).

```JavaScript
// login.js

const username = 'joaosilva';
const password = 'secret';

login (username, password);
```

# Github

Truques que são aceitos escrevendo Markdown no Github

## Lista de itens com checkbox marcado ou descarmado.
Pode-se usar no Github um chekbox marcado ou desmarcado, como uma lista de itens. Basta criar uma lista com asterisco (*) na frente do item seguido de um par de colchetes [ ] (ha um espaço dentro desse par de colchetes), e o nome do item. Se colocar um X dentro dos colchetes em vez do espaço, o checkbox ficará marcado, caso deixe apenas com o espaço entre os colchetes, ficará desmarcado.

* [x] Item 01
* [ ] Item 01
* [X] Item 01

# Exemplos

[![NPM Version][npm-badge]][npm-url]
[![Downloads][npm-downloads-badge]][npm-downloads-url]
[![Travis Status][travis-badge]][travis-url]
[![CircleCI Status][circleci-badge]][circleci-url]
[![AppVeyor Status][appveyor-badge]][appveyor-url]
[![Coveralls Status][coveralls-badge]][coveralls-url]
[![License][license-badge]][license-url]


[npm-badge]: https://img.shields.io/npm/v/npm.svg
[npm-url]: https://github.com/npm/cli/releases/tag/v6.9.0
[npm-downloads-badge]: https://img.shields.io/npm/dt/localeval.svg
[npm-downloads-url]: https://www.npmjs.com
[travis-badge]: https://travis-ci.org/robertoachar/generator-oss-project.svg?branch=master
[travis-url]: https://travis-ci.org/robertoachar/generator-oss-project
[circleci-badge]: https://circleci.com/gh/robertoachar/generator-oss-project/tree/master.svg?style=shield
[circleci-url]: https://circleci.com/gh/robertoachar/generator-oss-project
[appveyor-badge]: https://ci.appveyor.com/api/projects/status/github/robertoachar/generator-oss-project?branch=master&svg=true
[appveyor-url]: https://ci.appveyor.com/project/robertoachar/generator-oss-project
[coveralls-badge]: https://coveralls.io/repos/github/robertoachar/generator-oss-project/badge.svg?branch=master
[coveralls-url]: https://coveralls.io/github/robertoachar/generator-oss-project?branch=master
[license-badge]: https://img.shields.io/github/license/robertoachar/generator-oss-project.svg
[license-url]: https://opensource.org/licenses/MIT
