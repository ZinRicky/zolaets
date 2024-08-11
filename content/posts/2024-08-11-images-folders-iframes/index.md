+++
title = "Images, folders and iframes: go, shortcodes!"
date = 2024-08-11T09:50:00Z
+++

It’s time to implement some simple shortcodes for some basic needs.

## Image blocks
Most of the times, an image in a post should be its own block, take a considerable amount of space and be centered.

{{ img_block(img="a5QZA6g_700bwp.webp", alt="A meme of an airplane falling onto the Kaaba.", caption="Random meme from 9gag.") }}

For this style of blog in particular, I feel there is no need to make an image style that float on the right of the paragraph — and it would be painful to make it work well on small viewports.

## To each (post) its own (folder)
I also changed the structure of the `content` directory: now, instead of having all Markdown files under the same `posts` folder, each one gets its own sub-folder inside `posts`.
This way, adding images to them is more manageable, unless you want to recycle memes.
And you *shouldn’t* recycle memes.

## 50 shades of iframe
Sometimes, you just want to drop a YouTube video in the middle of a blog post.

{{ youtube(id="rjwrdX3e7kM") }}

Sometimes you just want to share some music.

{{ spotify(id="playlist/37i9dQZF1DWTcqUzwhNmKv") }}