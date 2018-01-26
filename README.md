markdown-spellcheck-cli
=======================

This is a simple command-line tool for spell-checking markdown files (based on [markdown-it-spellcheck](https://github.com/matatk/markdown-it-spellcheck)). For embedded HTML blocks within your markdown, it checks the text content of elements, and some "user-facing" attributes (as per the [html-text-extract documentation](https://github.com/matatk/html-text-extract#html-text-extract)).

Install with: `npm install --global markdown-spellcheck-cli`

Run `markdown-spellcheck` for help.

Development
-----------

### Set-up

* Check out the code.
* `npm install`

### Useful scripts

* `npm test`&mdash;lints the code (which also happens on pre-commit).
