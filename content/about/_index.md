+++
title = "About"
template = "standalone.html"
+++

## About the original

Zonelets is a semi-automatic blog builder.
Its main gimmick is being completely manual except for a single JS script, which keeps track of the published posts.
For detailed information about its use, please check the [quick start guide](https://zonelets.net/posts/2020-11-08-Quick-Start-Guide) and the references therein.

## About this theme

This is a theme for [Zola](https://www.getzola.org/), a static site generator that has two gimmicks:

- being a single lightweight executable, even on Windows;
- being written in Rust (dear Rustaceans, please don’t hurt me).

At the moment, this theme is **very** basic.
But so is Zonelets, so I don’t mind.
So far, I have implemented:

- Zonelets’s default theme, i.e. the one for its main website;
- basic blog management, i.e. a `posts` directory that accepts `YYYY-MM-DD-slug-of-the-post.md` files;
- syntax highlighting (I just took one of Zola’s default highlighters and called it a day).

These are the things I would like to add to this theme:
- shortcodes for:
    - figures with alt-text and optional caption;
    - privacy-respecting YouTube iframes;
    - Spotify and Bandcamp iframes;
- a tag system;
- an Atom feed generator.
