title: Tag Plugins
---
Tag plugins are different from post tags. They are ported from Octopress and provide a useful way for you to quickly add specific content to your posts.


## Block Quote

Perfect for adding quotes to your post, with optional author, source and title information.

**Alias:** quote

```
content

```

### Examples

**No arguments. Plain blockquote.**

```
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem.
```

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem.

**Quote from a book**

```
Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.
```

Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.

**Quote from Twitter**

```
NEW: DevDocs now comes with syntax highlighting. http://devdocs.io
```

NEW: DevDocs now comes with syntax highlighting. http://devdocs.io

**Quote from an article on the web**

```
{% blockquote Seth Godin http://sethgodin.typepad.com/seths_blog/2009/07/welcome-to-island-marketing.html Welcome to Island Marketing %}
Every interaction is both precious and an opportunity to delight.
{% endblockquote %}
```

Every interaction is both precious and an opportunity to delight.

## Code Block

Useful feature for adding code snippets to your post.

**Alias:** code

```
code snippet
```

### Examples

**A plain code block**

```
alert('Hello World!');
```


alert('Hello World!');


**Specifying the language**

```
[rectangle setX: 10 y: 10 width: 20 height: 20];
```


**Adding a caption to the code block**

```
array.map(callback[, thisArg])
```

**Adding a caption and a URL**

```
_.compact([0, 1, false, 2, '', 3]);
=> [1, 2, 3]
```


_.compact([0, 1, false, 2, '', 3]);
=> [1, 2, 3]


## Backtick Code Block

This is identical to using a code block, but instead uses three backticks to delimit the block.

&#96`` [language] [title] [url] [link text]
code snippet
&#96;``

## Pull Quote

To add pull quotes to your posts:

```

content

```

## jsFiddle

To embed a jsFiddle snippet:

```
```

## Gist

To embed a Gist snippet:

```
```

## iframe

To embed an iframe:

```
```

## Image

Inserts an image with specified size.

```
```

## Link

Inserts a link with `target="_blank"` attribute.

```
```

## Include Code

Inserts code snippets in `source/downloads/code` folder.

```
```

## YouTube

Inserts a YouTube video.

```
```

## Vimeo

Inserts a Vimeo video.

```
```

## Include Posts

Include links to other posts.

```
```

## Include Assets

Include post assets.

```
```

## Raw

If certain content is causing processing issues in your posts, wrap it with the `raw` tag to avoid rendering errors.

```

content

```


## Post Excerpt

Use text placed before the `<!-- more -->` tag as an excerpt for the post.

**Examples:**

``` 
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
<!-- more -->
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
```
