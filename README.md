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
> Para fazer um **comnetário** _(citação)_, basta colocar um simbolo de maior (>) no início da sentença.



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


