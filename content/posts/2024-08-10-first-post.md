+++
title = "The absolute basics"
date = 2024-08-10T17:30:00Z
+++

First things first, we can make words **bold**, *italic* or ***both***.
We can also switch to a `monospace font` if we ever need to present a thing verbatim — inline code, for instance.

Long text isn’t justified nor hyphenated, as you can see below.  
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec dictum massa in eros maximus, eu gravida est iaculis. Fusce dignissim maximus rutrum. Vivamus ac vulputate ipsum. Proin nec elit arcu. Aliquam vitae euismod ex. Donec varius nec sapien non condimentum. Aliquam erat volutpat. Nullam feugiat velit eleifend mauris aliquam, vitae iaculis quam luctus. Suspendisse consequat nibh eget nulla porttitor, ut fringilla mi sollicitudin. Nunc sit amet gravida sapien, nec tempus risus. Mauris eget rhoncus nibh. Vivamus lacinia placerat est eget eleifend. Ut interdum sapien in nisi rutrum pulvinar. Nullam vel dui ut felis tincidunt hendrerit.

A [link](#) doesn’t get any special treatment when in the post, expect when hovered over.
Selecting a portion of normal text should not lead to strange colours.  
Similar non-exciting behaviour can be expected for titles’ size.

Thanks to [Zola’s syntax highlighting](https://www.getzola.org/documentation/content/syntax-highlighting/), it was easy to render code properly.
In order to solve horizontal overflow, I opted for `overflow-x: scroll`.

```html
<html>
<head>
    <title>Hello, world!</title>
    <style>
        h1 {
            font-family: sans-serif;
        }
    </style>
    <script>
        console.log("Hello, world!");
    </script>
</head>
<body>
    <h1 id="top-site">Hello, world!</h1>
    <img src="/foo.png" alt="The most stunning view of Milan (ITA).">
</body>
</html>
```

The `<hr>` tag should also behave properly and accordingly to the overall style.

---

Like this.
I took some liberty with respect to the original CSS hints, but the result is much more bearable.
