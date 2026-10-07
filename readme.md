# Markdown to HTML Converter

This project is a polished single-file web app that converts Markdown input into HTML output in real time. It is designed as a lightweight editor/preview tool with a dark UI and a clean preview panel.

The final build is contained in `testing.html`.

## Overview

The app lets you:

- type Markdown on the left
- preview rendered HTML on the right
- click the Convert button to refresh the output
- copy the generated HTML to the clipboard
- load an example Markdown document instantly

## How to use it

1. Open `testing.html` in a browser.
2. Enter Markdown in the editor panel.
3. The HTML preview updates automatically.
4. Use the buttons to:
   - Convert
   - Copy HTML
   - Load Example

## Supported Markdown

This converter supports common Markdown elements, including:

- Headings (`#`, `##`, `###`)
- Paragraphs
- Bold text (`**text**`)
- Italic text (`*text*`)
- Links (`[label](https://example.com)`)
- Inline code (`` `code` ``)
- Unordered lists (`- item`)
- Blockquotes (`> quote`)
- Fenced code blocks (`````)
- Tables using pipe syntax

## Example

```markdown
# Sample Markdown

## Features

- Bold and italic
- Lists
- Code blocks
- Links
- Blockquotes
- Tables

**Bold text** and *italic text*.

[OpenAI](https://openai.com)

> This is a blockquote.

``` 
const hello = "world";
console.log(hello);
```

| Name | Age |
|------|-----|
| Alice | 24 |
| Bob | 29 |
```

## Notes

- This is a client-side app and does not require a backend or build step.
- It is intended as a simple, self-contained HTML/CSS/JavaScript tool.
- The output is generated directly in the browser.

## Files

- `testing.html` — final app build
- `readme.md` — project documentation
