All changes – unless gramatical – will be rejected unless done by a Minister.
Gramatical changes are not to change the meaning of a law.

# File names
All file names are to follow this format: `title;description.html`.


# Style
All paragraphs are to be in `<p>` tags. Text within a paragraph is to be indented by 4 spaces,
headings and other tags – unless within a paragraph – are not to be indented.
`<br>` tags are to have their own lines.
Lines should be wrapped at 120 charecters or where it makes gramatical sense;
if you are not using an IDE or text editor that automaticly wraps lines,
mention @TheSuperGamer20578 in your PR and request that your lines get wrapped –
and make sure that you ticked the box to allow maintainers to edit your branch.


# Heading levels
- `<h2>` Article
- `<h3>` Section
- `<h4>` Subsection
- `<h5>` Subsubsection
- `<h6>` Subsubsubsection

`<h1>` is not to be used


# Example
`Example;An example law to show what other laws should look like.html`
```html
<h2>Example Article</h2>
<h3>Example Section</h3>
<p>
    This is an example of what a small law might look like
</p>
<h4>A very long Subsection</h4>
<p>
    This is a very long Subsection to demonstrate wrapping.
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna
    aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur
    sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</p>
<h4>A link</h4>
<p>
    This Subsection contains a <a href="https://example.com">link</a>.
</p>
<h4>Many linebreaks</h4>
<p>
    This
    <br>
    Subsection
    <br>
    has
    <br>
    lots
    <br>
    of
    <br>
    linebreaks.
    <br>
    It has 6 linebreaks!
</p>
<h3>Another Section</h3>
<h4>A Subsection</h4>
<h5>A Subsubsection</h5>
<p>
    A Subsubsection! Thats a bit ridiculous
</p>
<h5>Another Subsubsection</h5>
<h6>A Subsubsubsection</h6>
<p>
    How many subs can you add to section
</p>

```


# Basic HTML guide
## Tags
A tag is the stuff between `<` and `>` e.g. `<h2>`. Some tags need to be closed, this is done by doing another tag with a `/` prepended to the name e.g. `</h2>`.
## Headings
Headings are done with `<hX>` where X is the heading level and need to be closed with `</hX>`, the stuff between the opening and closing tags is the heading.
## Other tags
- `<p>` paragraph: like headings, paragraphs need to be closed, the stuff between the opening and closing tags is the paragraph
- `<a href="LINK">` link: needs a closing tag, the stuff between the opening and closing tags is the text that appears on the link
  e.g. `<a href="https://example.com">Example link</a>` becomes [Example link](https://example.com).
- `<br>` linebreak: HTML ignores linebreaks, this can be helpful if you want to add linebreaks in your file to prevent the horizontal scrollbar
  but you want to let the web browser handle the wrapping for you
