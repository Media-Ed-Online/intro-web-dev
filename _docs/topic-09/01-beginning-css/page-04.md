---
title: Comments in CSS
module: topic-09
permalink: /topic-09/css-comments/
categories: css
tags: comment, testing
---

<div class="divider-heading"></div>

As with your HTML work, you should get in the habit of including comments in your CSS code.

These comments can be used to tell you what you are trying to do, leave yourself notes about what is happening and why, or be used to inform your instructors about what you were attempting.

<div class="row callout-columns status-warning">
  <div class="col-lg-3">
    <div class="icon">
      <ul class="bursts">
        <li class="deg0"></li>
        <li class="deg36"></li>
        <li class="deg72"></li>
        <li class="deg108"></li>
        <li class="deg144"></li>
        <li class="deg180"></li>
        <li class="deg216"></li>
        <li class="deg252"></li>
        <li class="deg288"></li>
        <li class="deg324"></li>
      </ul>
      <i class="fas fa-exclamation-circle"></i>
    </div>
  </div>
  <div class="col-lg-9">
    <p>Comments are not hidden from <i>other people</i>. Comments, if included in your deployment code, will be available for the whole world to see.</p>
  </div>
</div>

A few reasons why you may want to include comments in your code:

- **_Messages_** - Primary comments convey information about code. Typically, this means _why_ some code was written in a certain way, or may also point out information to those collaborating on code together.
- **_Dividers_** - Stylesheets can get long, quickly. A CSS comment can be added at the beginning of a specific section as a sort of label or descriptor.
- **_Testing_** - You can turn code snippets on or off by delineating them as comments. This is useful when hunting for errors or trying different ways of styling content.

In CSS, comments are placed inside of a “forward-slash + star” set (`/*...*/`).

<div class="code-heading">
  <span class="css">CSS</span>
</div>
```css
/* This is a CSS comment. */


/* Everything placed between the “forward-slash + star” pair is part of the comment. */

/*
Comments in CSS are known as “block-comments,”
which means they can span multiple lines!

Notice how the comment delineators are placed on
lines above and below the text respectively.
*/
```
