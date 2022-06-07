# HTML e CSS

Prof Marcelo Petri

recomendação de site
https://www.w3schools.com ->básico de HTML, CSS, python, Javascript e mais

---
## Estrutura de um arquivo .HTML
---

HTML (HyperText Markup Language);

Linguagem de marcação;

Marcamos onde e como queremos que nossos elementos se comportem;

Utilização e tags;

### Demonstração:
```
<html>
    <head>
        <title>Isso é um título.</title>
    </head>
    <body>
         <h1>Isso é um cabeçalho.</h1>

         <p>Isso é um parágrafo.</p>

         <p>Isso é outro parágrafo.</p>
    </body>
</html>
```

---
## Tags importantes:
---
```<html>``` ->define a linguagem da página como html

```<head>``` ->cria um espaço para o título da página

```<body>``` ->cria o corpo para o texto

````<h1>, <h2>, ..., <h6>```` ->cria um cabeçalho, primário, secundário, etc...

````<p>```` ->cria um parágrafo

````<br>```` ->quebra a linha

````<!--   -->```` ->serve para fazer comentários no código

---
### Meta tags

A tag ````<meta>```` define metadados sobre um documento HTML. Metadados são dados (informações) sobre dados.

````<meta charset="UTF-8">```` -> define o conjunto de caracteres exibidos da página

````<meta name="description" content="Free Web tutorials">```` -> breve descrição da página

````<meta name="author" content="John Doe">```` -> autor da página

````<meta name="keywords" content="HTML, CSS, Javascript">```` ->palavras-chave que ajudam na busca da página

````<meta name="viewport" content="width=device-width, initial-scale=1.0">```` -> define o modelo de visualização da página

---
### Link tags
A tag ````<link>```` serve para conectar ou buscar um elemento para o lado do cliente (CSS).

````<link ref="stylesheet" href="estilo.css">```` ->define a estilização da página

````<a href="<site>"><texto></a>```` ->insere um link para outra página com o texto como hyperlink

````<a target="<alvo_do_hyperlink>">```` ->define em que página o link vai ser aberto

---
### Script tags
A tag ````<script>```` é usada para incorporar um script do lado do cliente (Javascript).

````<script>```` ->define o script a ser utilizado

````\\```` ->insere um comentário no script

---
## Elementos de formatação HTML
---
````<b>```` ->negrito

````<strong>```` ->o mesmo que negrito (padrão HTML5)

````<i>```` ->itálico

````<em>```` ->itálico (padrão HTML5)

````<mark>```` ->marca em destaque

````<small>```` ->menor

````<del>```` ->texto riscado

````<sub>```` ->texto abaixado

````<sup>```` ->texto elevado

````<font size="<numero>">```` ->define tamanho da fonte

---
## Imagens
---
````<img src="nome_da_imagem">```` ->insere uma imagem armazenada no arquivo na página

````<img width="<numero(px ou %)>">```` ->define uma largura para a imagem, para definir uma altura usar lenght no lugar de width

````<img alt="<texto>">```` ->caso a imagem não apareça, este texto serve para descrevê-la

---
## Listas
---
As listas HTML permitem que os desenvolvedores da Web criem listas para suas páginas

```<ul>``` ->define uma lista não ordenada, utlizando pontos

```<ol>``` ->define uma lista ordenada, numerando os itens

```<li>``` ->define um item da lista



