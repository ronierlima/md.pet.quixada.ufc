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
## 1. Títulos (`<h1>` a `<h6>`)

Para marcar um título, você vai usar **#** a quantidade de vezes que irá representar o nível do título. Exemplo:

### Markdown | ``HTML``

 - \# Título nível 1 | ``<h1>Título nível 1\</h1> ``

 - \#\# Título nível 2 | ``<h2>Título nível 2</h2>``

 - \#\#\# Título nível 3 | ``<h3>Título nível 3</h3``

 - \#\#\#\# Título nível 4 | ``<h4>Título nível 4</h4>``

 - \#\#\#\#\# Título nível 5 | ``<h5>Título nível 5</h5>``

 - \#\#\#\#\#\# Título nível 6 | ``<h6>Título nível 6</h6>``


## 2.  Ênfase

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


## 3. Citações em bloco

Para criar uma citação em bloco, adicione um `>` na frente de um parágrafo.

    > O Campus Quixadá é o mais lindo da UFC.

A saída renderizada fica assim:

> O Campus Quixadá é o mais lindo da UFC.

## 4. Citações em bloco aninhada

Para criar uma citação em bloco aninhada, adicione dois `>>` na frente de um parágrafo.

    >Somos do PET - Sistemas de Informação
    >>O Campus Quixadá é o mais lindo da UFC.

A saída renderizada fica assim:

>Somos do PET - Sistemas de Informação
>>O Campus Quixadá é o mais lindo da UFC.

## 5. Código

Para denotar uma palavra ou frase como código, coloque-a em backticks (`).

    No prompt de comando, digite `nano`.

A saída renderizada fica assim:

No prompt de comando, digite `nano`.

## 6. Blocos de código

A sintaxe básica do Markdown permite criar blocos de código recuando linhas por quatro espaços ou uma guia. Se você achar isso inconveniente, tente usar blocos de códigos protegidos. Dependendo do seu processador ou editor do Markdown, você usará três reticulares ( ```) ou três retângulos ( ~~~) nas linhas antes e depois do bloco de código. A melhor parte? Você não precisa recuar nenhuma linha!

    ```
    printf("hello world");
    ```


A saída renderizada fica assim:

```
  printf("hello world");
```

### Realce de sintaxe

    ```c
    printf("hello world");
    ```


A saída renderizada fica assim:

```c
  printf("hello world");
```

## 7. Listas 

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
    1. Segundo item
    1. Terceiro item
   
A saída renderizada fica assim:

1. Primeiro item  
1. Segundo item
1. Terceiro item

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

## 8. Links

Para criar um link, coloque o texto do link entre colchetes  e siga-o imediatamente com o URL entre parênteses.

    [Este é meu GitHub](https://github.com/RonierLima)

A saída renderizada fica assim:

[Este é meu GitHub](https://github.com/RonierLima)

### Adicionando títulos

Opcionalmente, você pode adicionar um título para um link. Isso aparecerá como uma dica de ferramenta quando o `usuário passar o mouse sobre o link`. Para adicionar um título, coloque-o entre parênteses após o URL.


    [Este é meu GitHub](https://github.com/RonierLima "Ronier Lima - GitHub")

A saída renderizada fica assim:

[Este é meu GitHub](https://github.com/RonierLima "Ronier Lima - GitHub")

### URLs e endereços de email

Para transformar rapidamente um URL ou endereço de email em um link, coloque-o entre colchetes angulares.

    <https://www.markdownguide.org>
    <ronier@email.com>

A saída renderizada fica assim:

<https://www.markdownguide.org>

<ronier@email.com>

## 8. Imagens

Para adicionar uma imagem, adicione um ponto de exclamação ´!´, seguido de texto alternativo entre colchetes e o caminho ou URL do recurso de imagem entre parênteses. Opcionalmente, você pode adicionar um título após o URL entre parênteses.

    ![Yaktocat](assets/img/yaktocat.png "Yaktocat é uma versão do Octocat do GitHub")

A saída renderizada fica assim:

![Yaktocat](assets/img/yaktocat.png "Yaktocat é uma versão do Octocat do GitHub")

### Imagens com link

Para adicionar um link a uma imagem, coloque o Markdown da imagem entre colchetes e, em seguida, adicione o link entre parênteses.

    [![Yaktocat](assets/img/yaktocat.png "Yaktocat é uma versão do Octocat do GitHub")](https://octodex.github.com/yaktocat/)

A saída renderizada fica assim:

[![Yaktocat](assets/img/yaktocat.png "Yaktocat é uma versão do Octocat do GitHub")](https://octodex.github.com/yaktocat/)

# Referências

- <https://www.markdownguide.org>