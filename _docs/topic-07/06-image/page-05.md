---
title: 3. Alternative Text
module: topic-07
permalink: /topic-07/img-alt/
---

<div class="divider-heading"></div>


<div class="panel panel-success">
  <div class="progress" style="margin-bottom: 0; border-bottom-left-radius: 0; border-bottom-right-radius: 0;">
    <div class="progress-bar progress-bar-success progress-bar-striped" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%">
      <span class="sr-only">60% Complete (success)</span>
    </div>
  </div>
  <div class="panel-body">
    <p style="font-size: large; margin: 0;"><span style="color: #999"><img src="#"</span> <span style="color: #79AF33; font-weight: bold;">alt="..."</span> <span style="color: #999">title="..." width="..." height="..." /></span></p>
  </div>
</div>


<span class="label label-danger">Important</span> This attribute is <b>required</b> in the element.

Proper style and accessibility standards dictate that you must always include the **alternative text attribute**. The key for this is simply `alt=""`. The value in the double quotes should describe the image. This description is used by screen readers for those who are visually impaired.

Therefore it is critical that you provide a detailed description, especially in the case where the image is necessary to understand the content of the page.

<ul style="list-style-type: none">
  <li class="icon-con"> Poor: &nbsp;&nbsp;&nbsp;<code>alt="Me getting help"</code></li>
  <li class="icon-pro"> Better: &nbsp;<code>alt="Justine receiving help from an instructor while at a computer"</code></li>
</ul>
