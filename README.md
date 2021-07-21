# Custom MultiMarkdown Syntax and Themes for [Drafts by Agile Tortoise](https://getdrafts.com/)

Markdown syntax with extended support for [MultiMarkdown](https://fletcherpenney.net/multimarkdown/) extensions, like footnotes, definition lists and Critic Markup.

This is an extended version of the default MultiMarkdown syntax, which includes support for custom colors for abbreviations, definition lists, glossary items, variables, metadata and other MultiMarkdown features not supported in the default MultiMarkdown syntax (images, bold italic, tables and more) while keeping it compatible with the default themes.

Install through the [Drafts Directory](https://directory.getdrafts.com/s/1jc).

For example of custom made themes using this syntax check out [Custom Light](https://actions.getdrafts.com/s/1je) and [Custom Dark](https://actions.getdrafts.com/s/1jd) :)

## Scope Reference (for theme makers):

* **Header Markup**: Allows customizing each header markup separately. Scopes: `markup.heading01`-`markup.heading06`, uses `markup.heading` by default.
* **Escaped Line Breaks**: uses `text.invisibles` by default.
* **Horizontal Rules**: ``text.multimarkdown.hr``, uses `markup` by default.
* **Footnotes**: ``text.multimarkdown.footnote``, uses `markup.link` by default.
* **Images**: `text.multimarkdown.image`, uses `markup.link` and `color.accent01` by default.
* **Subscripts**: `text.multimarkdown.subscript`, uses `markup` by default.
* **Superscripts**: `text.multimarkdown.superscript`, uses `markup` by default.
* **Math**: `text.multimarkdown.math`, uses `markup` by default.
* **Tables**: `text.multimarkdown.table`, with `text.multimarkdown.table.head`, `text.multimarkdown.table.header`, `text.multimarkdown.table.divider`, `text.multimarkdown.table`.caption also available for specific parts. Uses `color.accent02` by default.
* **Metadata**: `text.multimarkdown.metadata`, uses `color.accent03` by default.
* **Citations**: `text.multimarkdown.citation`, uses `markup.link` and `color.accent04` by default.
* **Glossary definitions**: `text.multimarkdown.glossary`, uses `markup.link` and `color.accent05` by default.
* **Abbreviation**: `text.multimarkdown.abbreviation`, uses `markup.link`, color.accent06 by default.
* **Definition Lists**: `text.multimarkdown.definitionList` with `text.multimarkdown.definitionList.term` and `text.multimarkdown.defitionList.definition` for more specific highlighting. Uses `color.accent03` by default.
* **Metadata Variables**: `text.multimarkdown.variable`, uses `markup.link` and code.keyword by default.
* **TOC (Table of Contents)**: `text.multimarkdown.toc`, uses `code.literal` by default.