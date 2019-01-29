---
title: Plain Text Files
module: topic-01
permalink: /topic-01/text-files/
categories: development
tags: document, file, processor, text
---

<div class="divider-heading"></div>


As you just read in “<a href="../web-files-text">Text Documents</a>”, said **text documents** are files that store an [ASCII character set](https://en.wikipedia.org/wiki/ASCII) (as opposed to binary data), which is the most common format for the English language. These text files can include text documents of prose, code, or some combination of both.


## Creating plain text files
Text files can be created and edited using a **“text editor,”** which is any application for editing ASCII text documents. This includes both prose or code documents. <a href="https://atom.io/" target="_blank">Atom</a>, <a href="https://www.sublimetext.com/" target="_blank">Sublime Text</a>, and <a href="http://brackets.io/" target="_blank">Brackets</a> are popular options among web developers.

The default application on Mac and Windows are the following:

- macOS - _textEdit.app_
- Windows - _Notepad.exe_


## What types of files are text documents?
The simplest and most common text document is a "text file", which will bare the `.txt` extension. This generic document type contains only ASCII characters. These are the common characters you use for writing and reading (A-Z, a-z, 0-9), and special characters (such as #, %, !, ., etc.). These files also include carriage returns (new line), tabs, spaces, and an end-of-file (eof) designation that let's a program know where the file finishes. This last group, of course, contains characters that are there but that are not displayed in basic text editors.

<img src="../img/txt-file.png" alt="A .txt file open in textEdit.app" title="A .txt File" style="width: 400px;" />


<div class="divider-pg"></div>


## “Well, I have Microsoft Word, so...”

You might be tempted to say Microsoft Word Document files (`.doc` or `.docx`) are text files. However, these are actually containers of many smaller files that are ZIP-compressed together into the `.docx` file. This complex file that Microsoft uses allows them to store images, objects, text, and complex formatting instructions all in a single file, which can then be easily saved, shared, or sent between users of the Microsoft productivity applications.

<img src="../img/txt-vs-word-files.jpg" alt="A .docx file loaded into a simple text editor" title="A .docx file viewed in Atom" />

The downside to this format though is that you cannot open this file in a basic text editor to change it. The image below shows a Microsoft Word Document (`.docx`) opened in the Atom text editor. As you can see, this file does not present itself in a way that offers you much understanding of its contents.

<img src="../img/txt-vs-word-files-atom.jpg" alt="A .docx file loaded into a simple text editor" title="A .docx file viewed in Atom" />


<div class="divider-pg"></div>


## What are other types of plain text-based files?

Well, as you might guess, most computer languages are saved as plain text or ASCII files. However, they often have different extensions. These extensions provide information to the computer, as well as to the user as to ‘how’ the file may be used or _compiled_.

In this class, we will be using the following text file types;

- Markdown; `.md`
- HyperText Markup Language (HTML); `.html`
- Cascading Style Sheet (CSS); `.css`

In the Git module, we'll look at the first type; Markdown or `.md` files, using a text editor.
