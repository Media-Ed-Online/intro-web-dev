---
title: Git Version Control
module: topic-01
permalink: /topic-01/git-vcs/
categories: development
tags: git, vcs
---

<div class="divider-heading"></div>

One great thing about working with text files is that their simplicity makes it easy to track changes between various versions of that file. Since the files contain only [ASCII](http://www.asciitable.com) characters, it is easy to create programs that can look for character or word level changes to a document.

“You can think of a **version control system** (VCS) as a kind of “database.” It lets you save a snapshot of your complete project at any time you want. When you later take a look at an older snapshot (let's start calling it "version"), your VCS shows you exactly how it differed from the previous one.” [<a href="https://www.git-tower.com/learn/git/ebook/en/command-line/basics/what-is-version-control#start" target="_blank">Git-Tower.com</a>]

<img src="../img/what-is-vcs.png" alt="database-like structure traking changes to a file with date stamps" title="Version Control" />


<div class="divider-pg"></div>


## Why use a VCS?
- **Tracking Changes** - Version control allows a developer/writer to make changes to a file and track their changes over time. By “committing” changes to a file with a simple, associated message, the developer can create a list of how they have changed that file over time.
- **Revert Back** - Version control also allows for a developer/writer to make changes that may or may not work. If they find that the change they made was inappropriate, or did not work, they can simply revert back to a previous version. There is no need for directories full of “save as...” files.
- **Share and Collaborate** - Version control makes collaboration and sharing easier. Then all associated parties can see all changes made by each other, and manage any conflicts that may occur within a file.

<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="https://player.vimeo.com/video/41027679?color=EFB73E&title=0&byline=0&portrait=0" frameborder="0" allowfullscreen></iframe>
</div>


<div class="divider-pg"></div>


## “Yes, but why are _we_ using a VCS?”
- I want you to use the principles of GIT so that you can track incremental changes to your work throughout your weekly assignments.
  - This will allow you to see your own change history.
  - This will allow you to try things, and know that if they do not work well, you can easily go back to what you had working before.
- Your git repositories (or repos) can easily be integrated with GitHub.com (discussed in the next section), which has some definite benefits:
	- Built in distributed cloud backup for free.
	- A free hosted webspace. (This is how you will submit assignments during most of the course).
	- This allows us to easily see your work/code and track the changes you made during the weekly development cycle.
- The last reason you will be using GIT and GitHub.com is because they are standard industry tools in both commercial and research facilities. Your familiarity and comfort with GIT will make you a better future collaborator.
