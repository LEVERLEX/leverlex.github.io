---
layout: default
title: Markdown Test Page
---

# Markdown Formatting Test

This page demonstrates various markdown formatting elements supported by GitHub Pages.

## Text Formatting

**Bold text** using double asterisks `**bold**` or double underscores `__bold__`

__Bold text with underscores__

*Italic text* using single asterisks `*italic*` or single underscores `_italic_`

_Italic text with underscores_

~~Strikethrough~~ using double tildes `~~strikethrough~~`

## Headers

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

## Links

[Link with text](https://leverlex.github.io)

[Empty link]()

Auto-link: https://leverlex.github.io

## Lists

### Unordered Lists

- Item 1
- Item 2
  - Nested item 2.1
  - Nested item 2.2
- Item 3

### Task Lists

- [x] Completed task
- [ ] Incomplete task
- [ ] Another incomplete task

### Ordered Lists

1. First item
2. Second item
3. Third item

## Code

### Inline Code

Use `inline code` with single backticks.

### Code Blocks

Using triple backticks:

```
Plain code block
Multiple lines
```

```javascript
// JavaScript code block
function hello() {
  console.log("Hello, World!");
}
```

```python
# Python code block
def hello():
    print("Hello, World!")
```

Using tildes:

~~~~
Code block with tildes
~~~~

## Blockquotes

> This is a blockquote
> It can span multiple lines
> 
> And have multiple paragraphs

> Nested blockquotes
>> Like this

## Horizontal Rule

---

***

___

## Tables

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |

## Mentions

Mentions use @ symbol: @username

## Images

![Alt text](https://via.placeholder.com/150)

## Escaping

You can escape markdown characters with backslash: \*not italic\* \`not code\`

## HTML

<p>You can also use <strong>HTML</strong> directly in markdown.</p>

<div style="background-color: #f0f0f0; padding: 10px; border-radius: 5px;">
  Custom styled content
</div>

---

*This page tests all markdown elements referenced in issue #6*
