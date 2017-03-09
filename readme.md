<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Terminal commands](#terminal-commands)
  - [Bash / Linux](#bash--linux)
  - [Git](#git)
  - [Node / NPM](#node--npm)
- [HTML tags](#html-tags)
  - [Document Setup](#document-setup)
  - [Content Tags](#content-tags)
  - [Commonly Used Tags](#commonly-used-tags)
  - [Semantic Tags](#semantic-tags)
- [CSS Properties](#css-properties)
- [Resources](#resources)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Terminal commands

### Bash / Linux

Command | Usage | Resource
----- | ----- | -----
`cd`	| change directory
`ls`	| list files and folders
`pwd`	| print working directory
`mkdir`	| make directory
`touch`	| create file
`mv`	| move a file or directory
`cp`	| copy a file or directory
`open`  | (mac)	open file or directory in Finder
`explore` | (windows	open file or directory in Explorer
`.`	    | the current directory
`..`	| one directory up in the file tree
`../..`	| two directories up in the file tree

### Git

Command | Usage | Resource
----- | ----- | -----
`git add`	        | select files to stage for commit | [Git SCM](https://git-scm.com/docs/git-add)
`git commit`    	| save your files in git locally | [Git SCM](https://git-scm.com/docs/git-commit)
`git push origin master`        	| push your files up to Github | [Git SCM](https://git-scm.com/docs/git-push)
`git push origin master:gh-pages`	| host your site on Github Pages | [GitHub Help](https://help.github.com/articles/creating-project-pages-using-the-command-line/)
`git clone [url]`   | create a local version of a git repository | [Git SCM](https://git-scm.com/docs/git-clone)
`git init`	        | initialize your project as a git repository | [Git SCM](https://git-scm.com/docs/git-init)
`git remote -v`	    | view git remotes (URLs) | [Git SCM](https://git-scm.com/docs/git-remote)
`git remote add origin [url]`	    | add a git remote to your project | [Git SCM](https://git-scm.com/docs/git-remote)

### Node / NPM

Command | Usage | Resource
----- | ----- | -----
`npm install` | Install an NPM package
`surge` | Host site on surge (include `--domain` option for custom URL)


---

## HTML tags

### Document Setup

Command | Usage | Resource
----- | ----- | -----
`html`	| where all of your HTML tags go | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html)
`body`	| anything you want to show up on the page | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body)
`head`	| information for the browser | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head)
`meta`	| for the browser, holds many different types of information | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta)
`!DOCTYPE`  | Used to declare the type of document being used to the browser | [MDN](https://developer.mozilla.org/en-US/docs/Glossary/Doctype)

### Content Tags

Command | Usage | Resource
----- | ----- | -----
`h1`, `h2`, `h3`, `h4`, `h5`, `h6`	| highest to lowest level headings | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements)
`p`	| paragraph | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)
`a`	| anchor (link to a location / page) | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)
`img`	| image | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)
`ul`	| unordered list | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
`ol`	| ordered list | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
`li`	| list item | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li)
`blockquote`    | A quote | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote)

### Commonly Used Tags

Command | Usage | Resource
----- | ----- | -----
`div`	| a generic block-level element | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)
`span`	| a generic inline-level element | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span)
`code`	| for referencing code | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/code)
`pre`	| preserves whitespace formatting | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/pre)
`link`	| link's the contents of an external file to the current HTML file | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link)
`script`	| inserts a script file into your page | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script)

### Semantic Tags

Command | Usage | Resource
----- | ----- | -----
`main`	| the main content of a page | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/main)
`article`	| for content that can be taken out of the context of the page and still make sense | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article)
`section`	| a section of the content / page | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section)
`header`	| top information unrelated to the main content | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header)
`footer`	| bottom information unrelated to the main content | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer)
`aside`	| Information aside from the main content | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/aside)
`nav`	| contains links to navigate the website | [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav)


---

## CSS Properties

Command | Usage | Resource
----- | ----- | -----
`color`	| color of the text | [W3Schools](https://www.w3schools.com/cssref/pr_text_color.asp)
`background-color`	| color of the background | [W3Schools](https://www.w3schools.com/cssref/pr_background-color.asp)
`width`	| width of an element's content | [W3Schools](https://www.w3schools.com/cssref/pr_dim_width.asp)
`height`	| height of an element's content | [W3Schools](https://www.w3schools.com/cssref/pr_dim_height.asp)
`padding`	| space between the edge of the content and the element's outer edge / border | [W3Schools](https://www.w3schools.com/cssref/pr_padding.asp)
`margin`	| space between the element and other elements outside of it | [W3Schools](https://www.w3schools.com/cssref/pr_margin.asp)
`border`	| line to mark the edge of an element, between margin and padding | [W3Schools](https://www.w3schools.com/cssref/pr_border.asp)
`font-size`	| font size | [W3Schools](https://www.w3schools.com/cssref/pr_font_size.asp)
`line-height`	| the height of the lines of your content (think double-space vs. single-space) | [W3Schools](https://www.w3schools.com/cssref/pr_line_height.asp)

## Resources

[Mozilla Developer's network HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
