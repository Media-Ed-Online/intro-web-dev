---
title: Navigating to Sections on the Same Page
module: topic-08
permalink: /topic-08/basic-nav-section/
---

<div class="divider-heading"></div>

When pages are long, or visitors are expected to interested in specific topics, you can section the page using `<div>`s with unique `id`s. A page can then include its own navigation with links to those unique sections.

<p><span class="remember-text">Remember?</span><br/>
Jumping to areas on <a href="../../topic-04/same-page">the same page</a> is a two-step process of <b>adding ids</b> to elements and <b>creating links</b> to those ids.</p>


<div class="external-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="yKJEQX" data-default-tab="html,result" data-user="Media-Ed-Online" data-pen-title="HTML Nav Element, Page Navigation" class="codepen"></p>
</div>


<span class="label label-info">Note</span> It is considered good practice to include “back to top” options for the user, to avoid excessive scrolling and confusion. This can be done by using `#` as the [source's placeholder](https://www.w3.org/TR/html5/browsers.html#dom-location-hash), or creating an `id` at the page's beginning.
