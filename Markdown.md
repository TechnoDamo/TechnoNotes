# 📘 Markdown (.md) Full Conspectus

Markdown is a lightweight markup language with plain text formatting syntax. It’s used to format text for the web, typically in `.md` files like `README.md`.

---

## 📚 Table of Contents

1. [Headings](#headings)  
2. [Text Formatting](#text-formatting)  
3. [Lists](#lists)  
4. [Links](#links)  
5. [Images](#images)  
6. [Blockquotes](#blockquotes)  
7. [Code](#code)  
8. [Horizontal Rules](#horizontal-rules)  
9. [Tables](#tables)  
10. [Task Lists](#task-lists)  
11. [Escaping Characters](#escaping-characters)  
12. [Extended Syntax (GitHub Flavored Markdown)](#extended-syntax-github-flavored-markdown)  

---

## Headings

Use `#` to define headings. More `#` = lower heading level (like h1, h2…h6).

```markdown
# H1 - Largest
## H2
### H3
#### H4
##### H5
###### H6 - Smallest
```

---

## Text Formatting

```markdown
*Italic* or _Italic_  
**Bold** or __Bold__  
***Bold Italic***  
~~Strikethrough~~
```

Result:

*Italic*, **Bold**, ***Bold Italic***, ~~Strikethrough~~

---

## Lists

### Unordered List

```markdown
- Item 1
- Item 2
  - Subitem
* Item 3
```

### Ordered List

```markdown
1. First item
2. Second item
   1. Subitem
3. Third item
```

---

## Links

### Inline link

```markdown
[OpenAI](https://openai.com)
```

### Reference-style link

```markdown
[Google][1]

[1]: https://google.com
```

---

## Images

```markdown
![Alt Text](https://example.com/image.jpg)

![Local Image](./img/logo.png)
```

Add title (optional):  
```markdown
![Alt Text](image.jpg "Title")
```

---

## Blockquotes

```markdown
> This is a quote.
> 
> - Author
```

Nested quotes:

```markdown
> Level 1
>> Level 2
```

---

## Code

### Inline Code

```markdown
Use `git status` to check changes.
```

Result: Use `git status` to check changes.

### Code Block

Using three backticks:

\`\`\`python
def hello():
    print("Hello, world!")
\`\`\`

Indented code (legacy style):

    def hello():
        print("Hello")

---

## Horizontal Rules

Use three or more of the following:

```markdown
---
***
___
```

---

## Tables

```markdown
| Syntax | Description |
|--------|-------------|
| Header | Title       |
| Cell   | Text        |
```

Align text:

```markdown
| Left   | Center | Right  |
|:-------|:------:|-------:|
| A      | B      | C      |
```

---

## Task Lists

```markdown
- [x] Write a README
- [ ] Add documentation
- [ ] Deploy to production
```

Result:

- [x] Write a README  
- [ ] Add documentation  
- [ ] Deploy to production

---

## Escaping Characters

Use `\` to escape Markdown characters:

```markdown
\*Not Italic\*  
\# Not a heading
```

---

## Extended Syntax (GitHub Flavored Markdown)

### Syntax Highlighting

```markdown
```javascript
console.log("Hello world");
```
```

### Emoji (GitHub only)

```markdown
:smile: :rocket: :tada:
```

Result: 😄 🚀 🎉

### Mentions

```markdown
@username  
#123 (issue or PR)
```


