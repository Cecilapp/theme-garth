---
title: Why this site is static
tags: [Web]
---
This blog is a folder of text files turned into plain HTML. No database, no comments, no tracking. Here is why I like it that way.
<!-- break -->
For years my notes lived in a blogging platform that kept asking me to update plugins. One day I realised I spent more time maintaining the blog than writing in it.

## How it works now

Every post is a Markdown file with a few lines of front matter:

```yaml
---
title: Why this site is static
tags: [Web]
---
```

A static site generator, [Cecil](https://cecil.app), reads the files, applies a theme, and writes HTML pages. I upload the result, and that's it.

## What I gained

- **Speed**: pages are small and load instantly, even on the slow connection at the cabin.
- **Durability**: in twenty years, Markdown files will still open in any text editor.
- **Quiet**: no notifications, no dashboard, no numbers to check.

What I lost is the comment section. I don't miss it: people who want to reply send me an email, and those emails are almost always kind.
