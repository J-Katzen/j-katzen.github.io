---
layout: post
title: "Jekyll, Octopress, and Github Page Hosting"
date: 2013-10-05 13:23
comments: true
categories: ['code']
sharing: true
---

<h3><b>Hello World!</b></h3>
<p>Today I decided to take on the task of learning a thing or two about Jekyll, Octopress, and taking advantage of github pages to open a new blog that I've taken the liberty title 'Is this code?'</p>
<p>To be honest, initial setup took me a little longer than I had originally anticipated because of my lack of experience doing anything with ruby and rbenv.  For a little while, even though I had installed ruby1.9.3p448, I was still using my system's ruby1.8.7. The rbenv versions command helped me identify which version I could quickly enable with the rbenv local command.
``` sh
$ rbenv versions
$ rbenv local [version]
```
</p>
<p>After that was squared away, I was off to the races. I found a nice theme which I have applied and left unmodified for now after taking a look at this <a href="//github.com/imathis/octopress/wiki/3rd-Party-Octopress-Themes">list</a>. I changed the font, because I didn't want to lay any money down for the typekit font this theme was loading, so I opted for <a href="//www.google.com/fonts">Google Web Fonts</a> because they are free and have a great selection. It also helps that Octopress has great integration with them already, which is all well-documented on their site <a href="//octopress.org/docs/theme/template/">here</a>. Basic configuration setup followed, along with some link changing and voilà, you get what you see here now.</p>
