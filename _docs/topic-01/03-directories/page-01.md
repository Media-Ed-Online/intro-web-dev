---
title: Web Directories (“Folders”)
module: topic-01
permalink: /topic-01/directories-web/
categories: development
tags: directory, file, folder, organize, path
---

<div class="divider-heading"></div>


We organize these different files into groups, just like you do with your other non-web-based files. We commonly refer to the containers of these files as "folders," because that's exactly as they function; folios containing related files. In addition, most operating systems represent these folders with graphic icons (folders), so it's reasonable that we call them that.

But once we branch away from our desktop however, this term is a little less applicable. Consider this URL:

<div style="padding: 20px 0px 80px 0px;">
  <p align="center">
    <img src="https://www.mcdonalds.com/content/dam/usa/logo/m_logo.png" alt="McDonald's Logo" style="border: none;"/>
  </p>
  <p class="url-example">https://www.mcdonalds.com/content/dam/usa/logo/m_logo.png</p>
</div>

The **path** (or “directions”) for this image, `/content/dam/usa/logo/` actually refers to the nesting of its folders, or **directories**.

<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
└── <i class="far fa-folder-open"></i> content/
    └── <i class="far fa-folder-open"></i> dam/
        └── <i class="far fa-folder-open"></i> usa/
            └── <i class="far fa-folder-open"></i> logo/
                └── <i class="far fa-image"></i> m_logo.png

</pre>


<span class="label label-info">NOTE</span> “Folders” and “directories” refer to the same concept, but “directory” should be used when discussing file systems. You will hear us use directory most often.
