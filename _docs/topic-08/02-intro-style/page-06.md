---
title: Styling Images
module: topic-08
permalink: /topic-08/basic-styling-images/
---

<div class="divider-heading"></div>

Images have certain behaviors within a page, including how and where they appear and react with surrounding and nearby elements. To declare images in the `<style>` element, use the element selector `img {}`.

## Sizing Images
You may have images of all different sizes you want to include in your page, but once there, you'd like them all to be the same width for consistency. Instead of adding width values to all your `<img>` tags, you can do it across <u>all</u> images on the page using the **width property**.

<span class="label label-info">Note</span> This means your image tags <u>do not need</u> width values; for example, `<img src="#" alt="" title="" />`


<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
img {
  width: ;
}
```


## Floating Images

<p><span class="remember-text">Remember?</span><br/>
That images are <a href="../../topic-05/extra-markup#inline" target="_blank">inline elements</a> that appear “within” or adjacent to neighboring elements.</p>


To override where images appear, you can use the **float property** to effectively direct the flow of adjacent elements, either to the left or right.

For example, using `float: left;` will place the image to the left, and elements below will flow around it. The opposite is true of `float: right;`.

<div class="code-heading">
  <span class="html">HTML</span>
</div>
```html
img {
  float: ;
}
```


<div class="divider-pg"></div>


### Example
See how you can manipulate an image's size and placement with **width** and **float**!


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="bveMWm" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="Basic HTML Image Styling" class="codepen"></p>
</div>
