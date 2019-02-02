---
title: Writing in Markdown
module: topic-02
permalink: /topic-02/markdown-readme/
categories: development
tags: markdown, markup
---

<div class="divider-heading"></div>


Despite how it sounds, Mark<u>down</u> is actually a mark<u>up</u> language! A **markup language** is a system for annotating a document in a way that is syntactically distinguishable from the text. Markup languages tend to encourage writers to focus on _content_ and _structure_ before concerning themselves with presentation.

Structure is defined for a processor through the use of tags embedded directly in the text.

You learned about Markdown and [Markdown files](../../topic-01/markdown-files) last topic, but let's look at another example:

<div class="code-heading">
  <span class="md">Markdown</span>
</div>
```markdown
A **markup language** is a system for annotating a document in a way that is syntactically distinguishable from the text. Markup languages tend to encourage writers to focus on *content* and *structure* before concerning themselves with presentation.
```

You can see that in order to make text **bold**, I need to wrap it in double asterisks:  `**bold**`. *Italic* text is wrapped in single asterisks: `*italic*`.


<div class="divider-pg"></div>


## README.md Files
Again, **README files** are text-based files used in documentation. Files ending in a `.md` file extension are Markdown files, so a **README.md** is a README file written in Markdown.

Every repository you make for this class will have a README.md file. We initiated our **web-dev-hw/** root repository with a README.md file, but all homework repositories will need to have README.md files created for them.

<span class="label label-danger">Important</span> Markdown README files are <u>only</u> ever named `README.md` or `readme.md`!

<div class="code-heading">
  <span>Directory Tree</span>
</div>
<pre id="bash">
.
├── <i class="far fa-folder-open"></i> assignment-01/
│   └── <i class="far fa-file-alt"></i> README.md
├── <i class="far fa-folder-open"></i> assignment-02/
│   └── <i class="far fa-file-alt"></i> README.md
├── <i class="far fa-folder-open"></i> assignment-03/
│   └── <i class="far fa-file-alt"></i> README.md
... etc ...
└── <i class="far fa-file-alt"></i> README.md <i class="fas fa-long-arrow-alt-left bounce-x"><span>Root Repo's README</span></i>
</pre>

**For every assignment you submit, you will also write a short report in a text file.** This report is the `README.md` for that directory, and may discuss a number of things every week:

- Questions regarding your understanding of the Topic's materials.
- Summarizing the work you did this cycle, paying particular attention to the individual choices you made.
- Is there anything in particular you learned that you would like to discuss further?
- What problems did you have? How did you solve them?
