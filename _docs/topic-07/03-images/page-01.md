---
title: All About Images
module: topic-07
permalink: /topic-07/img-about/
categories: html
tags: history, html5, image
---

<div class="divider-heading"></div>


## Images in HTML
As stated in the introduction, the **image element** is a multi-part element comprised of several "commands" over how the image will render.

The 5 attributes an image element should include are:
1. The tag itself.
2. The source attribute.
3. Alternative text.
4. The image title.
5. Width and height values.

<div class="row callout-columns status-danger">
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
      <i class="fas fa-times-circle"></i>
    </div>
  </div>
  <div class="col-lg-9">
    <p>The <a href="#" data-toggle="tooltip" title="The location of the file, either by relative or absolute URL">source</a> and <a href="#" data-toggle="tooltip" title="short description of the image">alternative text</a> attributes are <b>required</b> in the image element.</p>
  </div>
</div>

As with the break (`<br />`) and horizontal ruler (`<hr />`) elements, the image element is an _empty element_ that only requires a single tag. This tag is the **image tag**, `<img />`.

<a href="#" data-toggle="tooltip" title="The location of the file, either by relative or absolute URL">source</a> As with hyperlinks, this element is reliant on _attributes_ within the tag to allow it to be useful. Visit the next pages to learn these attributes.

The first attribute that we will need to consider is `src=""`. Within the double quotes you will need to include a **URL source** to the location of the desired image.

This will typically be a **relative URL** to a file stored on the same server as the web page, but can also be an **absolute URL** to an image anywhere on the Internet.


<div class="divider-pg"></div>


## Did you Know?
<div class="row">
  <div class="col-lg-8">
    <p>Images, unlike hyperlinks, use the URL <b>source</b> to retrieve additional data for the page, as opposed to sending the user to another page.</p>

    <p>As I am <i>sure</i> you can imagine, you will need use images a lot in web design and development.</p>

    <p>But like most things about the web, imagery has humble beginnings. To the right is first picture ever uploaded on the web, posted by Tim Burners Lee on behalf of a comedy band called <cite>Les Horrible Cernettes</cite>, July 18, 1992.</p>

    <p>It is interesting to note that the first image on the web was, in fact, Photoshopped. <a href="https://www.busbud.com/blog/exposing-the-nofilter-movement/" targe="_blank">#NoFilter</a> is a new concept, not a web Renaissance.</p>
  </div>
  <div class="col-lg-4">
    <img src="../img/les-horrible-cernettes.jpg" alt="Four women dressed in 1980's formalwear" title="Les Horrible Cernettes" style="max-width: 250px; margin-top: 0;"/>
    <p class="img-caption">Les Horrible Cernettes (1992)</p>
  </div>
</div>


<div class="divider-pg"></div>


<h2 id="img-src">Image Source</h2>


<div class="divider-pg"></div>


<h2 id="img-alt">Alternative Text</h2>
Proper style and accessibility standards dictate that you must always include the **alternative text attribute**. The key for this is simply `alt=""`. The value in the double quotes should describe the image. This description is used by screen readers for those who are visually impaired.

Therefore it is critical that you provide a detailed description, especially in the case where the image is necessary to understand the content of the page.
