# Semânticas


Em HTML é possível definir blocos de código especificos por fim de organizar melhor sua página:

````<div>```` -> utilizado para criar um contâiner de elementos para formatá-los de maneira individual, é possível indentificá-las  usando o atributo class ou id.

---
## Convenções 
Afim de padronizar alguns usos e facilitar sua indentificação no código, algumas divs específicas foram incluídas com o advento do HTML5:

````<header>```` -> define o cabeçalho da página

````<footer>```` -> define o rodapé da página

````<aside>```` -> define um espaço lateral na página, normalmente utiliza-se esse espaço para anúncios ou informações não relacionadas ao foco da página

````<nav>```` -> define um espaço de navegação na página, pode-se utilizar links para navegação de seções dentro ou para outras páginas 

````<section>```` -> cria uma sessão ná página, dentro dela é possível criar tags de cabeçalhos e rodapé

````<article>```` -> cria um espaço para artigos na página, nele é possível definir parágrafos e outras tags de texto

---
## Estilização:

É possivel estilizar a página através do uso de CSS, tanto dentro da tag ````<style>```` ou em um arquivo externo .CSS. No caso de usar um arquivo externo, pode se estilizar uma ou mais tags diretamente ao escrevê-las dentro do arquivo.

Exemplo:

````
tag1, tag2, tag3, tag4, ...{
    <elemento 1>;
    <elemento 2>;
    .
    .
    .
}
````

Pode-se também atribuir uma classe a várias tags diferentes e estilizar em um único bloco de CSS

Exemplo:

````<<tag> class="<nome_classe>">```` ->atribui uma classe à tag

agora é possível estilizar as tags atribuídas à classe utilizando CSS, indicando no código um ponto "." antes do nome da classe

Exemplo:
````
.nome_classe{
    <elemento1>;
    <elemento2>;
    .
    .
    .
}
````




