---
title: 1. Logical or Linear Ordering
module: topic-05
permalink: /topic-05/ordering/
categories: development
tags: best-practice, code, organize
---

<div class="divider-heading"></div>

Most languages read and process top-to-bottom, so its important to list these elements linearly and/or logically down the page.


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
<!DOCTYPE html>

<html>
  <body>

    <!-- This is improper ordering of blocks! -->
    <!-- The footer should come after the main content. -->
    <footer>
      <p>(C) Justine Evans</p>
    </footer>

    <main>
      <h1>"Debt"</h1>
      <h2>A sonnet about student loans.</h2>
    </main>

  </body>
</html>
```
