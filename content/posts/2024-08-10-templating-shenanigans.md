+++
title = "Setting up the Zola template"
date = 2024-08-10T21:45:00Z
+++

When I started this silly little project some hours ago, I thought that Zonelets was *astonishingly simple* to replicate.
While Zonelets is not exactly a CSS stunt or a JS mess, there are some things that took me *way too much time* to implement properly.

## Yet again, the basics

Themes for Zola usually start from a `base.html` file.
The `<head>` is not that complicated; it’s just long to write.
The most general `<body>` possible has a navbar at the top, a main section and a rather small footer; these weren’t hard either.

Adding a `content` Tera block makes filling the main part of a page rather simple.
In fact, `page.html` (for blog posts) and `standalone.html` (for the *about* page) almost wrote themselves.

## Pagination madness

The hardest thing was to properly set up the “recent articles” section in the index.
It shows the last blog entries, but no more than four; and, if there are more than four posts on the sites, then it spawns a link to the archive.

Since I’m not very familiar with the ins and outs of Tera templating, I struggled for half an hour, but then I finally found the correct order of `{% if 4 < post_section.pages | length %}`.

The archive section was much easier after all that struggle.
