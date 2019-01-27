---
title: Directory Structure
module: topic-01
permalink: /topic-01/directories-structure/
categories: development
tags: directory, file, folder, name
---

<div class="divider-heading"></div>

Directories are hierarchical - that is, they are organized in a structure resembling a tree, with a single root which branches off into related groups of content.

## Hierarchy
The top-most directory is considered the **root directory**. Whatever current “folder” you are in can be considered the **directory**, and any directories inside that current directory are called **subdirectories.**

<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
./root/
└── <i class="far fa-folder-open"></i> directory/ <i class="fas fa-long-arrow-alt-left bounce-x"><span>current</span></i>
    └── <i class="far fa-folder-open"></i> subdirectory/
        └── <i class="far fa-file-alt"></i> file.txt
</pre>

<span class="label label-info">Note</span> The root directory in our trees will be shorted to `.` from here-on-out.


<div class="divider-pg"></div>


## Relationships
The web also use familial terms to describe content relationships, such as “grandparent,” “parent,” and “child.” Let's see how this applies to directories:


### Immediate
<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
└── <i class="far fa-folder-open"></i> my-site/ <i class="fas fa-arrows-alt-h bounce-x"><span>parent to</span></i><div class="line horizontal-down bounce-x" style="width: 8rem"></div>
    └── <i class="far fa-folder-open"></i> content/ <i class="fas fa-arrows-alt-h bounce-x"><span>child of</span></i><div class="line horizontal-up bounce-x" style="width: 5.5rem"></div>
        └── <i class="far fa-folder-open"></i> images/
            └── <i class="far fa-image"></i> logo.png
</pre>

In this example, `content/` is a subdirectory of the `my-site/` directory, also referred to as a “child” of that directory (i.e. **child directory**).

The reverse also applies; in reference to `content/`, `my-site/` would be considered its **parent directory**.

This can also describe the location of files. The file `logo.png` is found in its parent directory, `images/`.

<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
└── <i class="far fa-folder-open"></i> my-site/
    └── <i class="far fa-folder-open"></i> content/
        └── <i class="far fa-folder-open"></i> images/ <i class="fas fa-long-arrow-alt-left bounce-x"><span>parent</span></i><div class="line horizontal-down bounce-x" style="width: 6rem"></div>
            └── <i class="far fa-image"></i> logo.png <div class="line horizontal-up bounce-x" style="width: 9rem"></div>
</pre>



### Extended
This familial titling can go deeper as well.

<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
└── <i class="far fa-folder-open"></i> my-site/ <i class="fas fa-arrows-alt-h bounce-x"><span>grandparent to</span></i><div class="line horizontal-down bounce-x" style="width: 6.4rem"></div>
    └── <i class="far fa-folder-open"></i> content/
        └── <i class="far fa-folder-open"></i> images/ <i class="fas fa-arrows-alt-h bounce-x"><span>grandchild of</span></i><div class="line horizontal-up bounce-x" style="width: 1rem"></div>
            └── <i class="far fa-image"></i> logo.png
</pre>

Here, `images/` is the **grandchild directory** of `my-site/`, which is `images/`'s **grandparent directory.**

This process can extend to great-grandmember, great-great-grandmember, and so forth.