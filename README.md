# Assignment: CSS Hell

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

# License/Copyright

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

# Part 1 Changes

<b> In 1.html </b>

- add `<link rel="stylesheet" href="styles.css">`
- remove the style tags in the 1.html, and add them to the style sheet in `styles.css`.

<b> In 2.html </b>

- add `<link rel="stylesheet" href="styles.css">`
- remove the style tags in the 2.html, and merge them into the style sheet in the `styles.css`. That is, add the items that does not previously exist in the sheet, and modify the existing ones so that the styles of the pages doesn't change sharply.

<b> In 3.html </b>

- add `<link rel="stylesheet" href="styles.css">`
- remove the style tags in the 2.html, and merge them into the style sheet in the `styles.css`. That is, add the items that does not previously exist in the sheet, and modify the existing ones so that the styles of the pages doesn't change sharply.

<b> In styles.css </b>

- add `background-color: wheat;` to the body tag, to make the background color of the pages look paper-like.
- add `font-family: sans-serif` to the header tag `h1, h2, h3, h4, h5, h6` and the paragraph tag `p`, to theme the header and paragraph and make the page look old. (`serif` makes little difference, `sans-serif` looks better)
- add `font-size: large` to make the font of paragraph larger so that it looks more comfortable.
- add `border-radius: 10px` to the image tag `img` to make the edges and corners of images to look softer.
- set `font-size: large` and add `font-style: italic` in p.poem

# Reference

- The CSS file in part 1 are modified based on the style tags in:

1.  https://www.gutenberg.org/cache/epub/4300/pg4300-images.html
2.  https://www.gutenberg.org/cache/epub/1661/pg1661-images.html
3.  https://www.gutenberg.org/cache/epub/25344/pg25344-images.html
4.  https://www.w3schools.com/css/css_align.asp
