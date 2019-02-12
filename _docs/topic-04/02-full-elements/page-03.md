---
title: Paragraphs
module: topic-04
permalink: /topic-04/two-tags-paragraphs/
categories: html
tags: break, elements, markdown, paragraphs, preformatted, tags
---

<div class="divider-heading"></div>

Almost all non-heading text will be placed within a paragraph element in a web document. Paragraphs are defined with the `<p>` tags, and the element is written as `<p>...</p>`.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<p>This is a paragraph element.</p>
```


Compare this to Markdown:


<div class="code-heading">
  <span class="md">Markdown</span>
</div>
```markdown
This is a paragraph.

In markdown, a paragraph requires no extra markup to signify it as such. An empty line between text blocks signifies a new paragraph.
```





<div class="divider-heading"></div>

Any text between the paragraph tags `<p>...</p>` belongs to the same paragraph. This is the most common way of writing paragraphs in HTML pages.

You'll notice that when using Markdown, empty lines create paragraphs and provide cushion between one paragraph and the next. This is not true of HTML.

With HTML, paragraphs are made with tags, and browsers automatically add cushion above and below paragraph elements.


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="Wgqroy" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="Basic HTML Paragraphs" class="codepen"></p>
</div>





<div class="divider-heading"></div>

By default, browsers will remove empty spaces from paragraph element blocks. This is true of spaces and extra empty lines. You need to be aware that you cannot change the output of your rendered HTML code by adding extra spaces or lines unless you code for them; simply pressing space bar or return won't cut it.

You can see this below, where the first several paragraphs display as single lines. One way we can combat this is to use a **line break**, or the `<br />` tag. This will drop create a new line within a paragraph element.


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="qXwEbW" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Paragraphs and Line Breaks" class="codepen"></p>
</div>





<div class="divider-heading"></div>

You can use the **preformatted text** element (`<pre>...</pre>`) to tell a browser to render spaces and text exactly as you've typed.

This tag usually displays the contents of the element in a fixed-width font, as it is primarily used for preformatted code. However, it can also be used for preformatted text.


<div class="external-embed">
  <p data-height="400" data-theme-id="30567" data-slug-hash="QQGWGX" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Paragraphs and Preformatted Text" class="codepen">See the Pen <a href="https://codepen.io/Media-Ed-Online/pen/QQGWGX/"></p>
</div>
