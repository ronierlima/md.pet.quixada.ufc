![Markdown](assets/img/markdown.png)

# O que é Markdown?

* O markdown é uma maneira de estilizar o texto na web.
* Com ele é possível você marcar títulos, listas, tabelas, etc., de forma muito mais limpa, legível e precisa, do que se fosse fazer com HTML.

## Onde usar Markdown ?

* Existem vários lugares que você pode usar Markdown: No Github mesmo, você pode usar no README.md, que é um arquivo que fica na raiz do seu projeto, e é renderizado pelo Github abaixo da lista de arquivos. Aquele texto que você lê quando acessa um repositório é um arquivo README.md, escrito em Markdown.
  
  * Ainda no Github, você pode usar Markdown no texto das issues, no texto de um pull request e na wiki.
  * Também a maior parte dos geradores de estáticos (Hexo, Jekyll, HarpJS, Docpad, etc.), permitem escrever em Markdown! 
  * **.md** ou **.markdown**, são as extensões a  de arquivos **Markdown** 

## Porque aprender e usar Markdown ?

* HTML é muito verboso! 
* Markdown é mais legível, mais fácil de ler e interpretar.

---
## Títulos (`<h1>` a `<h6>`)

Para marcar um título, você vai usar **#** a quantidade de vezes que irá representar o nível do título. Exemplo:

### Markdown | ``HTML``

 - \# Título nível 1 | ``<h1>Título nível 1\</h1> ``

 - \#\# Título nível 2 | ``<h2>Título nível 2</h2>``

 - \#\#\# Título nível 3 | ``<h3>Título nível 3</h3``

 - \#\#\#\# Título nível 4 | ``<h4>Título nível 4</h4>``

 - \#\#\#\#\# Título nível 5 | ``<h5>Título nível 5</h5>``

 - \#\#\#\#\#\# Título nível 6 | ``<h6>Título nível 6</h6>``


## Ênfase

Você pode dar ênfase, colocando o tex to em negrito ou itálico.

### Negrito

Para negrito, adicione dois asteriscos ou sublinhados antes e depois de uma palavra ou frase. Para destacar em negrito o meio de uma palavra, adicione dois asteriscos sem espaços ao redor das letras.

Markdown | HTML | Saída Renderizada
---------| -----|------------------
Eu gosto do texto em \*\*negrito\*\*. |  Eu gosto do texto em \<strong>negrito\</strong>. | Eu gosto do texto em **negrito**.

### Itálico

Para colocar o texto em itálico, adicione um asterisco ou sublinhado antes e depois de uma palavra ou frase.

Markdown | HTML | Saída Renderizada
---------| -----|------------------
Prefiro o texto em \*itálico\*. |  Prefiro o texto em \<em>itálico\</em>. | Prefiro o texto em *itálico*.

### Negrito e Itálico

Para enfatizar o texto com negrito e itálico ao mesmo tempo, adicione três asteriscos ou sublinhados antes e depois de uma palavra ou frase.

Markdown | HTML | Saída Renderizada
---------| -----|------------------
Uso \*\*\*itálico e negrito\*\*\*. |  Uso \<em>\<strong>itálico e negrito\</strong>\</em> com \<strong>negrito\</strong>. | Uso ***itálico e negrito***..


## Citações em bloco

Para criar uma citação em bloco, adicione um `>` na frente de um parágrafo.

    > O Campus Quixadá é o mais lindo da UFC.

A saída renderizada fica assim:

> O Campus Quixadá é o mais lindo da UFC.

## Citações em bloco aninhada

Para criar uma citação em bloco aninhada, adicione dois `>>` na frente de um parágrafo.

    >Somos do PET - Sistemas de Informação
    >>O Campus Quixadá é o mais lindo da UFC.

A saída renderizada fica assim:

>Somos do PET - Sistemas de Informação
>>O Campus Quixadá é o mais lindo da UFC.


## Listas 

Você pode organizar itens em listas ordenadas e não ordenadas.

### Lista ordenada

Para criar uma lista ordenada, adicione itens de linha com números seguidos por pontos. Os números não precisam estar em ordem numérica, mas a lista deve começar com o número um.

    1. Primeiro item  
    2. Segundo item
    3. Terceiro item
   
A saída renderizada fica assim:

1. Primeiro item  
2. Segundo item
3. Terceiro item
   
---

    1. Primeiro item  
    2. Segundo item
    3. Terceiro item
   
A saída renderizada fica assim:

1. Primeiro item  
2. Segundo item
3. Terceiro item

### Lista não ordenada 

Para listas não ordenadas, você pode usar `*`, `+` ou `-`. Veja:

      + Primeiro item  
      * Segundo item
      - Terceiro item

A saída renderizada fica assim:

+ Primeiro item  
* Segundo item
- Terceiro item

### Lista aninhada

Recue um ou mais itens para criar uma lista aninhada.

    - Item 1
      - Item 1.1
        -  Item 1.1.1

A saída renderizada fica assim:

- Item 1
  - Item 1.1
    -  Item 1.1.1
  

https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open