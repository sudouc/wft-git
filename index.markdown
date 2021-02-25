---
layout: default
---
# WT ![](https://github.githubassets.com/images/icons/emoji/octocat.png) is Git?!  
![](/assets/wtf-git-hero.jpg)  
Git makes managing your projects and coursework much easier and is an essential skill in the software engineering industry. This repository lets you play with pushing and pulling to and from Git.  

## Getting started

**1)** <svg viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 5c0-1.11-.89-2-2-2a1.993 1.993 0 00-1 3.72v.3c-.02.52-.23.98-.63 1.38-.4.4-.86.61-1.38.63-.83.02-1.48.16-2 .45V4.72a1.993 1.993 0 00-1-3.72C.88 1 0 1.89 0 3a2 2 0 001 1.72v6.56c-.59.35-1 .99-1 1.72 0 1.11.89 2 2 2 1.11 0 2-.89 2-2 0-.53-.2-1-.53-1.36.09-.06.48-.41.59-.47.25-.11.56-.17.94-.17 1.05-.05 1.95-.45 2.75-1.25S8.95 7.77 9 6.73h-.02C9.59 6.37 10 5.73 10 5zM2 1.8c.66 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2C1.35 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2zm0 12.41c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm6-8c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"></path></svg> Fork this repository by going to `https://github.com/sudouc/wtf-git` and clicking the fork button in the top right corner.  

**2)** Create a local clone of your fork  
`git clone https://github.com/<your username>/wtf-git`

**3)** Create a new file in the "\_posts" folder, using the template as a guide (make sure to use the naming convention `2021-02-25-your-name.md`). Fill this in with a little about yourself. Take a look at the [markdown cheatsheet](/cheatsheet) if your not familiar with markdown  

```markdown
---
layout: post
title:  "Template Member"
date:   2021-02-25
categories: member
tags: member
author: Alice & Bob
---

I'm ___,

I study a ___.
```
**Note:** Its important to correctly update the `title` parameter to match the file name. I.E. the file `2021-02-25-your-name` must match the title `Your Name`

**4)** Commit and push your changes back to your fork  
```shell
git add .
git commit -m 'Created page for yourName'

```


**5)** Make a pull request  

**6)** Wait for your request to be merged and watch it go live

### Stuck at config and cloning?

![](assets/git.gif)

Download Slides by going to [the events page](https://sudouc.club/events)

<h2>Meet our members:</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>