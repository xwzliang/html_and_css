# Structural markup

## Headings
For main headings
`<h1>text</h1>`
For subheadings
`<h2>, <h3>, <h4>, <h5>, <h6>`

## Paragraphs
`<p>text</p>`

## Bold
`<b>text</b>`

## Italic
`<i>text</i>`

## Superscript
`<sup>text</sup>`
e.g.
E=MC<sup>2</sup>

## Subscript
`<sub>text</sub>`
e.g.
H<sub>2</sub>O

## Whitespace
When the browser comes across two or more spaces next to each other, it only displays one space. Similarly if it comes across a line break, it treats that as a single space too. This is known as white space collapsing.

## Line Breaks
`<br />`
It is a good habit to put a space before the forward slash in an empty element.


# Semantic markup

## Strong
`<strong>text</strong>`
The use of the this element indicates that its content has strong importance. By default, browser will show the contents in bold.

## Emphasis
`<em>text</em>`
By default browsers will show the contents in italic.

## Quotations

Blockquote
`<blockquote><p>text</p></blockquote>`

Shorter quote
`<q>text</q>`

Both elements may use the cite attribute to indicate where the quote is from. Its value should be a URL that will have more information about the source of the quotation.

## Abbreviations and Acronyms
`<abbr title="text">text</abbr>`
A title attribute on the opening tag is used to specify the full term.

## Citations
`<cite>text</cite>`
Browser will render the content in italics.

## Definitions
`<dfn>text</dfn>`
The first time you explain some new terminology (perhaps an academic concept or some jargon) in a document, it is known as the defining instance of it.

## Author Details
```
<address>
<p><a href="mailto:example@example.org">example@example.org</a></p>
<p>physical address</p>
</address>
```

## Changes to Content

insertion
`<ins>text</ins>`
content is usually underlined

deletion
`<del>text</del>`
content usually has a line through it

substitution
`<s>text</s>`
indicates something that is no longer accurate or relevant (but that should not be deleted). Content usually has a line through it.
