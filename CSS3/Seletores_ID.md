# Seletro Id e Filho

Já vimos como selecionar elementos no CSS usando simplesmente o nome da tag:

```
p {
color: red;
}
```

Apesar de simples, é uma maneira muito limitada de selecionar. Às vezes não queremos pegar todos
os parágrafos da página, mas apenas algum determinado.
Existem, portanto, maneiras mais avançadas de selecionarmos um ou mais elementos do HTML
usando os seletores CSS. Vamos ver seletores CSS quase que ao longo do curso todo, inclusive alguns
bem avançados e modernos do CSS3. Por enquanto, vamos ver mais 2 básicos além do seletor por nome
de tag.
É possível aplicar propriedades visuais a um elemento selecionado pelo valor de seu atributo id .
Para isso, o seletor deve iniciar com o caractere "#" seguido do valor correspondente.
```
#cabecalho {
color: white;
text-align: center;
}
```
## Seletor Hierarquico

O seletor acima fará com que o elemento do nosso HTML que tem o atributo id com valor
"cabecalho" tenha seu texto renderizado na cor branca e centralizado. Note que não há nenhuma
indicação para qual tag a propriedade será aplicada. Pode ser tanto uma <div> quanto um <p> , até
mesmo tags sem conteúdo como uma <img> , desde que essa tenha o atributo id com o valor
"cabecalho".
Como o atributo id deve ter valor único no documento, o seletor deve aplicar suas propriedades
declaradas somente àquele único elemento e, por cascata, a todos os seus elementos filhos.

Podemos ainda utilizar um seletor hierárquico que permite aplicar estilos aos elementos filhos de um
elemento pai:
#rodape img {
margin-right: 30px;
vertical-align: middle;
width: 94px;
}
No exemplo anterior, o elemento pai rodape é selecionado pelo seu id . O estilo será aplicado
apenas nos elementos img filhos do elemento com id=rodape .
