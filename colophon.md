---
layout: post
title: Colophon
---

To author this web site, I write all the pages in
[Markdown](http://help.github.com/articles/markdown-basics/) using a
plain ascii editor. After I write something, I upload the changes
(using git) to [Github Pages](http://pages.github.com).

After each upload, Github Pages automatically runs
[Jekyll](http://jekyllrb.com). Jekyll processes the markdown pages and turns
them all into static HTML pages. This process typically takes just a few
seconds to update my entire site. Github Pages then serves this site for free.

### Why Jekyll is interesting

Jekyll is easier to manage than traditional blogging tools. It's
retro, a return to simpler tools. Modern web sites and blog engines
(like Wordpress or Drupal) are dynamic, meaning some code is run on
the server each time you view a page. All this dynamic server code
adds management complexity and presents an opportunity to exploit
security flaws.

Most pages are static, meaning they don't change each time you
look at them. When the web was invented in the 1990's, most pages were
static html files. The file you put on the server was exactly what the
browser loaded. Static files are incredibly efficient to serve, easy
to manage, and offer practically no opportunities for malware to
affect the server.

With jekyll, there is no server software for me to manage, configure,
or maintain.  The files themselves are static, which means there is no
vendor lock-in.  I can move my site to any other ISP any time I want
by just copying a folder, and I don't have to do much else to be up
and running.

Jekyll lets you avoid cut-and-paste repetition by using templates. You
can focus on just writing content, and let the templates handle the
other stuff like formatting or nav bars.

### Why Markdown is interesting

Markdown is easier to write than HTML. Instead of adding HTML tags,
Markdown gives you a few basic and easy-to-write markup tools. For
example, to *italicize* some text, just surround it with asterisks.

<pre><code>For example, to *italicize* some text, just surround it with asterisks.</code></pre>

If you want to add fancy HTML to a markdown page, you can.
I find that for basic text blogging, this just isn't necessary.


### Why Github Pages is interesting

Github Pages is jekyll-aware, meaning I just upload markdown files
and Github runs jekyll on them automatically on their servers.

Github Pages is hosted by github, which means it's extremely reliable
and efficient to reach audiences worldwide. Managing content with git
is a very good idea, because it keeps track of all edits. I can easily
compare, undo, and roll back to an older version of any of my content
any time.

Github Pages is free. Thank you, github.

Using git, I have a complete and accurate backup copy of all my files
at all times. One copy is on my laptop, another is on Github's server,
and I can make other copies elsewhere whenever I wish.  If something
happens to either my laptop or to Github, or I just don't want to use
them any more, I can switch very easily.


