# DISPLAY GRID 

* Display grid trata-se de uma das formas de distribuir elementos em uma página;
* O seu diferencial é que distribuímos em grade, diferentemente do flex box por exemplo;
* Veja sites que têm várias colunas e que distribuem diferentes elementos tipos de conteúdos na página. Certamente ele usa o Display Grid;
* Veja abaixo os principais comandos desse recurso do CSS.

<p>Veja abaixo uma tabela com as propriedades e valores</p>

| Propriedades | Valor | resultado |
| :--------- | :------ | :-------
display | grid | habilita o display grid
grid-template-columns | (quantidade de parâmetros) | quantidade de colunas que serão criadas e seu valor na unidade passada 
row-gap | define a distância entre as linhas | espera-se que seja realizado a distância entre os elementos na unidade especificado
column-gap | define a distância entre as colunas | espera-se que seja realizado a distância etre os elemetos na unidade especificada.
grid-template-areas | identificador posto no html | aqui o usuário meio que vai "desenhar a coluna", podendo definir a quantidade de coluna e o tamanho de acordo com suas repetições.
<hr>
<p>A última linha não funcinoa sozinha! É importante ter uma outra propriedade e valor, a grid-area e seu valor deve ser correspondente ao valor de uma das colunas definidas no grid-template-areas.</p>

<p>Para ver um exemplo aplicado basta consultar o éxemplo03</p>
