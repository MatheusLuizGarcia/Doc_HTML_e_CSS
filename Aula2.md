# Tabelas HTML

É possível criar tabelas em html utilizando os seguintes comandos:

````<table border="1">```` -> indica a presença de uma tabela, "border" define a largura em px da borda da tabela

````<th>```` -> define uma linha título, em negrito por padrão 

````<tr>```` -> define uma linha

````<td>```` -> define uma coluna

---
### Exemplo:

````html
<table border="1">
            <tr>
                <td>primeira coluna</td>
                <td>segunda coluna</td>
            </tr>
            <tr>
                <td>Segunda linha<td>
                <td>Segunda linha, segunda coluna<td>
            </tr>
         </table>
````
---
## Tabelas mescladas

É possivel mesclar entradas de uma tabela utilando o seguinte elemento:

````<td colspan="2">```` -> define a largura da coluna como 2 entradas

````<td rowspan="2">```` -> define a altura da linha como 2 entradas


---
# Formulário

Para trabalhar com espaços para inserçã de informações (como num formulário por exemplo), podemos utilizar várias tags dependendo do tipo e uso de informação:

````
<label for="<dado>">
<input type="<tipo_de_dado>">
````
cria um espaço para inserção de um tipo de texto e atribui essa informação a um dado

````<input type="radio" name="<grupo>">```` ->cria uma opção de escolha única num grupo do tipo rádio, é possível assinalar vários rádios se os grupos forem diferentes

````<option value="<valor>">```` ->cria uma opção de escolha múltipla e atribui um valor para ele, é possível atribuir valores iguais para várias opções

````<input type="checkbox">```` ->cria uma caixa de checagem com valores de falso(unchecked) e verdadeiro (checked)

````
<input type="button" name="botao" value="Botão">
<input type="submit" name="enviar" value="Enviar">
<input type="reset" name="reset" value="Limpar">
````
cria botões simples de interação com alguns comandos pré-determinados, assimila eles à um nome de dado através do name e informa sua função através do value 