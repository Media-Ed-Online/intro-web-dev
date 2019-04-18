---
title: Fixed and Sticky Menus
module: topic-12
permalink: /topic-12/nav-menu-sticky/
---

<div class="divider-heading"></div>

By now you should be familiar with [relative positioning](../../topic-11/position-relative/) and [absolute postitioning](/topic-11/position-absolute/), both of which allow you to place items where you want in relative to other elements.


<div class="divider-pg"></div>


## Fixed (Never Moves)
Setting an element to **fixed position** (`position: fixed;`) is similar to using absolute positioning in that the position is in relation to the browser, instead of any parent elements. Unlike absolute position though, fixed position is in relation to the _viewable_ portion of the browser. This means, that even when you scroll, an element set to fixed will remain viewable in the browser window.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="NwdmbR" data-default-tab="result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Dropdown Menu with Fixed Header" class="codepen"></p>
</div>


<div class="divider-pg"></div>


## Sticky (Gets Caught in the Scroll)
Setting the position to **sticky position** (`position: sticky`) will lock your nav bar into place once its reached in the scroll. In the following example, I have site information first, followed by the nav bar. Once a visitor scrolls down past the site info and the nav bar hits the top of the window, it will remain at the top unless the visitor scrolls above it again.

<div class="codepen-embed">
  <p data-height="600" data-theme-id="30567" data-slug-hash="JVLjZr" data-default-tab="result" data-user="Media-Ed-Online" data-embed-version="2" data-pen-title="Dropdown Menu with Sticky Header" class="codepen"></p>
</div>
