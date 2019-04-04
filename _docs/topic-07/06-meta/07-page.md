---
title: Robots
module: topic-06
permalink: /docs/topic-06/meta-robots/
redirect_from: /docs/topic-06/06-meta/07-page.md
---

<div class="divider-heading"></div>

The **robots** name type tells browsers whether they may spider or crawl the published webpage.

This name type takes one of four acceptable content values:

- `noindex` _value_ - Prevents a page from being indexed.
- `nofollow` _value_ - Prevents links from being crawled.
- `noarchive` _value_ - Instructs a search engine not to store an archived copy of the page.
- `nosnippet` _value_ - Asks that the search engine not include a snippet from the page along with the page's listing in search results.

<div id="code-heading">HTML</div>
```html
<meta name="robots" content="nofollow">
```
