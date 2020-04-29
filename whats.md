# O que é Markdown?

* O markdown é uma maneira de estilizar o texto na web.
* Com ele é possível você marcar títulos, listas, tabelas, etc., de forma muito mais limpa, legível e precisa, do que se fosse fazer com HTML.

## Onde usar Markdown ?

* Existem vários lugares que você pode usar Markdown: No Github mesmo, você pode usar no README.md, que é um arquivo que fica na raiz do seu projeto, e é renderizado pelo Github abaixo da lista de arquivos. Aquele texto que você lê quando acessa um repositório é um arquivo README.md, escrito em Markdown.
  
  * Ainda no Github, você pode usar Markdown no texto das issues, no texto de um pull request e na wiki.
  * Também a maior parte dos geradores de estáticos (Hexo, Jekyll, HarpJS, Docpad, etc.), permitem escrever em Markdown! 
  * **.md** ou **.markdown**, são as extensões de arquivos **Markdown** 

## Porque aprender e usar Markdown ?

* HTML é muito verboso! 
* Markdown é mais legível, mais fácil de ler e interpretar.

---
## Títulos (`<h1>` a `<h6>`)

Para marcar um título, você vai usar **#** a quantidade de vezes que irá representar o nível do título. Exemplo:

Markdown | HTML | Saída Renderizada
---------| -----|------------------
\# Título nível 1 | \<h1> Título nível 1 \</h1> | <h1>Título nível 1</h1>
\## Título nível 2 | \<h2> Título nível 2 \</h2> | <h2>Título nível 2</h2>
\### Título nível 3 | \<h3> Título nível 3 \</h3> | <h3>Título nível 3</h3>
\#### Título nível 4 | \<h4> Título nível 4 \</h4> | <h4>Título nível 4<h4>
\##### Título nível 5 | \<h5>  Título nível 5 \</h5> | <h5> Título nível 5 </h5>
\##### Título nível 6 | \<h6> Título nível 6 \</h6> | <h6>Título nível 6</h6>

## Sintaxe alternativa

Como alternativa, na linha abaixo do texto, adicione qualquer número de == caracteres para o nível 1 do cabeçalho ou -- caracteres para o nível 2 do cabeçalho.

Markdown | HTML | Saída Renderizada
---------| -----|------------------
Título nível 1 <br> \=============== | \<h1> Título nível 1 \</h1> | <h1>Título nível 1</h1>
Título nível 2 <br> \------------------------------ | \<h2> Título nível 2 \</h2> | <h2>Título nível 2</h2>
 
