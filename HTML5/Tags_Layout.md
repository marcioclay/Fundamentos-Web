# HTML 5: Tags de Layout

Entre as várias mudanças que o HTML 5 traz para o desenvolvimento web, existem algumas novas tags para o código-fonte. Não são apenas novas regras para tags antigas, mas tags completamente novas que não existiam antes no HTML 4.01.

Entre estas novidades estão as tags chamadas de tags de layout. Elas servem para classificar seções de sua página Web como áreas de significado sem que você precise de uma <div> para defini-las. O cabeçalho da página pode ser encapsulado dentro da tag <header> (não confundir com <head>…) e sua navegação pode ser encapsulada pela tag <nav>, por exemplo.

Você provavelmente usará estas tags da mesma forma que já está usando uma <div>para estas áreas, com a principal diferença de que agora elas estão definidas para você e seu navegador, de forma que você não precisa mais utilizar um <id>para identificá-las e sistemas automatizados serão capazes de entender o seu contexto.

Mas existem outras diferenças e vamos dar uma olhada em cada uma delas agora.

## ARTICLE

<article> é um indicador de uma área de conteúdo do seu site, o núcleo de uma determinada página, a porção mais central e relevante da página.

Antes da sua existência, mecanismos de busca, como o Google não tinham como identificar a parte mais relevante de seu conteúdo. Tanto a navegação, quanto o topo da página ou o seu miolo tinham o mesmo peso, sendo analisados de baixo para cima e sua importância determinada pela ordem de aparição no código-fonte. Com esta tag, navegadores, buscadores e outros sistemas automatizados podem identificar facilmente o conteúdo principal.

De acordo com a especificação semântica, o elemento contido dentro de <article> está pronto para ser distribuído ou reutilizado de forma independente, sem precisar dos demais elementos da página para ser compreendido. Pode abranger uma postagem, um artigo, um comentário de usuário, um gadget etc.

## ASIDE

<aside> é um indicador de uma área de conteúdo paralelo, complementar ao conteúdo principal em sua página.

Existe uma interpretação equivocada das especificações que indica seu uso para “sidebars”. Não é o caso, o conteúdo contido nesta tag é “lateral” no sentido figurado, não no sentido estrito da palavra, uma vez que, assim como as outras tags de layout, ela não guarda em si nenhuma instrução de posicionamento para o navegador.

O elemento contido dentro de <aside> funciona como uma nota, um adendo, um esclarecimento ao conteúdo que a cerca. Sua formatação fica ao critério do designer responsável e do CSS implementado.

## FIGURE

<figure> é um indicador de uma área de conteúdo gráfico dentro da página, seja uma foto, uma ilustração, um gráfico, um diagrama. A tag também pode ser utilizada para especificar fragmentos de código-fonte.

Na prática, funciona como um container para img e code. A tag introduz um candidato a substituto para o antigo "legend": o "figcaption".

A função do "figcaption" é marcar um cabeçalho ou legenda para um ou mais elementos inseridos dentro de "figure".

## FOOTER

"footer" é um indicador de uma área de conteúdo que vem ao final de um conteúdo, popularmente chamado de “rodapé”.

Semanticamente, de acordo com as especificações seu uso não se restringe ao rodapé da página, mas pode ser aplicado ao final de uma seção ou área. Dentro deste elemento costumam vir informações como autor, contato, copyright, documentos relacionados etc.

## HEADER

"header" é um indicador de uma área de conteúdo que vem no começo de um conteúdo, popularmente chamado de “cabeçalho”.

Semanticamente, de acordo com as especificações, seu uso não se restringe ao topo do documento, mas pode ser aplicado ao início de uma seção ou área. Dentro deste elemento costumam vir informações introdutórias e navegação.

Embora a interpretação das tags "header" e "footer" pelos navegadores não atribua qualquer posicionamento visual no layout da página, a regra de bom uso determina que o primeiro apareça antes do conteúdo principal e o segundo venha após o conteúdo principal.

## NAV

"nav" é um indicador de uma área na página que contém majoritariamente links de navegação.

Nem todos os links de um documento precisam estar contidos dentro deste elemento, apenas aquelas áreas popularmente conhecidas como “menu” ou listas de links.

Semanticamente, sistemas automatizados como navegadores, mecanismos de busca ou leitores de tela não tinham como diferenciar links de navegação de conteúdo propriamente dito. Com a implementação da tag "nav", por exemplo, leitores de tela podem pular inicialmente este tipo de área no site para usuários com deficiências.

## SECTION

"section" é um indicador de seção, capítulo, divisão de um determinado capítulo, cujo conteúdo está agrupado pelo mesmo tema.

A princípio, esta é a tag que causa mais confusão entre os usuários. Mas não deveria. Semanticamente, ela define uma seção genérica do conteúdo, como o próprio nome sugere. Se "article" é o grande agrupador de conteúdo, "section" são os lugares onde antes você aplicaria um "h2, h3, h4" etc.

Somando-se a introdução e as definições de cada tag de layout do HTML 5, este artigo que você está lendo, por exemplo, poderia ser dividido facilmente em 8 "section" diferentes.

Entretanto, não se deve confundir "section" com "div". O primeiro agrupa conteúdo que compartilha o mesmo tema. O segundo representa uma ruptura genérica no fluxo da página. Em bom português, toda seção é uma divisão do conteúdo, mas nem toda divisão chega a formar uma seção.

