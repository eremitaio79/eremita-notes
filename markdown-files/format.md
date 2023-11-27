# Formatações em arquivos Markdown (.MD)

### Títulos
<h1>Título H1</h1>
<h2>Título H2</h2>
<h3>Título H3</h3>
<h4>Título H4</h4>
<h5>Título H5</h5>
<h6>Título H6</h6>

### Parágrafos
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sed massa non purus molestie dapibus. Donec vehicula cursus metus id pretium. Maecenas quis nunc ut ante eleifend sollicitudin eu laoreet lorem. Duis porta lorem in nunc ultricies accumsan. Phasellus volutpat purus est, eget mollis libero malesuada at. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam at diam venenatis, suscipit nisi eget, aliquam libero.</p>

### Quebra de Linhas
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sed massa non purus molestie dapibus.<br>Donec vehicula cursus metus id pretium. Maecenas quis nunc ut ante eleifend sollicitudin eu laoreet lorem.<br>Duis porta lorem in nunc ultricies accumsan. Phasellus volutpat purus est, eget mollis libero malesuada at.<br>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam at diam venenatis, suscipit nisi eget, aliquam libero.</p>

### Negrito
<p>Lorem <strong>ipsum dolor</strong> sit amet, consectetur <strong>adipiscing</strong> elit.</p>

### Itálico
<p>Italicized text is the <em>cat's meow</em>.</p>

### Negrito e Itálico
<p>This text is <em><strong>really important</strong></em>.</p>

### Underline
Some of these words <ins>will be underlined</ins>.

### Centralizar
<center>This text is centered.</center>

### Cores em Textos
<font color="red">This text is red!</font>

### Alertas
> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.

### Citações
> Dorothy followed her through many of the beautiful rooms in her castle.

### Citações com Múltiplos Parágrafos
> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Citações Mescladas
> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Citações com outros Elementos
> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits <em>were higher</em> than ever.
>
>  *Everything* is going according to **plan**.

### Listas Numeradas
<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
  <li>Fourth item</li>
</ol>

1. First item
2. Second item
3. Third item
4. Fourth item

<ol>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item
    <ol>
      <li>Indented item</li>
      <li>Indented item</li>
    </ol>
  </li>
  <li>Fourth item</li>
</ol>

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

### Listas com Símbolos
<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
  <li>Fourth item</li>
</ul>

- First item
- Second item
- Third item
- Fourth item

<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item
    <ul>
      <li>Indented item</li>
      <li>Indented item</li>
    </ul>
  </li>
  <li>Fourth item</li>
</ul>

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

<ul>
  <li>1968. A great year!</li>
  <li>I think 1969 was second best.</li>
</ul>

- 1968\. A great year!
- I think 1969 was second best.

### Adicionando Elementos em uma Lista - Parágrafos
* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.

### Adicionando Elementos em uma Lista - Citações
* This is the first list item.
* Here's the second list item.

    > A blockquote would look great below the second list item.

* And here's the third list item.

### Blocos de Códigos
1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>

3. Update the title to match the name of your website.

### Imagens
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Millenium Falcon](/assets/img/falcon.jpg)

3. Close the file.

![The best starship in Star Wars](/assets/img/falcon.jpg "San Juan Mountains")

### Imagens com Links
[![Millenium Falcon](/assets/img/falcon.jpg "The best staship in Star Wars")](https://github.com/eremitaio79)

### Tamanhos de Imagens
<img src="/assets/img/falcon.jpg" width="200" height="100">

### Imagens com Legendas
<figure>
    <img src="/assets/img/falcon.jpg"
         alt="Millenium Falcon">
    <figcaption>The best starship in Star Wars.</figcaption>
</figure>

![Albuquerque, New Mexico](/assets/img/falcon.jpg)
*The best starship in Star Wars.*

### Linhas Horizontais
***

---

_________________

### Links
My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

### URLs e Endereços de E-mail
<https://www.markdownguide.org>
<fake@example.com>

### Formatando Links
I love supporting the **[EFF](https://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*.
See the section on [`code`](#code).

### Tabelas
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

### Alinhamento em Tabelas
| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

### Caracteres de Escape
\* Without the backslash, this would be a bullet in an unordered list.

Character	Name
\	backslash
`	backtick (see also escaping backticks in code)
*	asterisk
_	underscore
{ }	curly braces
[ ]	brackets
< >	angle brackets
( )	parentheses
#	pound sign
+	plus sign
-	minus sign (hyphen)
.	dot
!	exclamation mark
|	pipe (see also escaping pipe in tables)

### Listas de Tarefas
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Emojis
Gone camping! :tent: Be back soon.
That is so funny! :joy:

- Lista de Códigos de Emojis
Excelente página com códigos Emoji [rxaviers](https://gist.github.com/rxaviers/7360908).

### Highlight
I need to highlight these ==very important words==.

### Subscript
H~2~O

### Superscript
X^2^

### Símbolos
- Copyright (©) — &copy;
- Registered trademark (®) — &reg;
- Trademark (™) — &trade;
- Euro (€) — &euro;
- Left arrow (←) — &larr;
- Up arrow (↑) — &uarr;
- Right arrow (→) — &rarr;
- Down arrow (↓) — &darr;
- Degree (°) — &#176;
- Pi (π) — &#960;

### Vídeos do Youtube
[![Less Than Jake — Scott Farcas Takes It On The Chin](https://img.youtube.com/vi/PYCxct2e0zI/0.jpg)](https://www.youtube.com/watch?v=PYCxct2e0zI)

[![Escavadores do Tempo](/assets/img/falcon.jpg)](https://vimeo.com/69913592)
