---
title: Using HTML
module: topic-03
permalink: /topic-03/dom-html/
categories: html
tags: elements, markdown, paragraph, tags
---

<div class="divider-heading"></div>


The most widely-used markup language is HTML or **HyperText Markup Language.**

<div class="row">
  <div class="col-lg-12">
    <img src="../img/berners-lee.png" alt="Tim Berners-Lee" title="Tim Berners-Lee" style="width: 250px; float:right; margin-top: 0;"/>

    <p>HTML is the standard markup language for creating web pages and web applications. Web browsers use HTML to interpret and compose text, images, and other material into visual or audible web pages.</p>

    <p>HTML was first proposed in 1990 by Tim Berners-Lee, then a contract physicist at <a href="https://home.cern/topics/birth-web" targe="_blank">CERN</a>.</p>
  </div>
</div>


<div class="divider-pg"></div>


## HTML Elements
An HTML document is composed of a tree of HTML elements. An **element** is an individual component of an HTML document. Elements denote to the processor structure and semantic meaning of the document. Elements may also be nested or encapsulated within other elements.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<p>This is a paragraph element.</p>
<p>This is another paragraph element.</p>
```

Compare this to Markdown:

<div class="code-heading">
  <span class="md">Markdown</span>
</div>
```markdown
This is a paragraph.

This is another paragraph.
```

## HTML Tags
Elements are identified in a document through tags. A **tag** is code that is syntactically unique from the text content of the document. In HTML, all tags include a less-than (**<**) and greater-than (**>**) sign, with the tag typed between.

Most elements include an “opening” and “closing” tag that the processor uses to identify the beginning and end of the element with. Closing tags are identical to opening tags, except that they contain a forward-slash (**/**) between the less-than (**>**) sign and the tag text.


<div id="code-heading">HTML</div>
```html
<p>This is a paragraph element.</p>
<p>This element is created with an opening "<p>" tag and a closing "</p>" tag. We call this "wrapping."</p>
```

Compare this to Markdown:

<div id="code-heading" style="margin-top: 0 !important;">Markdown</div>
```markdown
This is a paragraph.

In markdown, paragraphs requires no extra markup to signify it as such. An empty line between text blocks signifies a new paragraph.
```
