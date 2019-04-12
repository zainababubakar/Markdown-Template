Below are some guidelines on writing Markdown Files

# HEADINGS:

```

# Heading 1
## Heading 2
### Heading 3

```

**Produces**:

# Heading 1
## Heading 2
### Heading 3

Headings in Markdown are any line which is prefixed with a # symbol. The number of hashes indicates the level of the heading. One hash is converted to an h1, two hashes to an h2 and so on. There are a total of 6 levels which you can make use of.

**NOTE**: Html tags can also be used for headings in markdown files but for the purpose of this documentation, stick to the **#** symbol for headings. 

**DO NOT USE HTML TAGS (`<h1>`, `<h1>`, e.t.c) FOR THE HEADINGS**

### QUOTES

```

> This is an example of a quote

```

**Produces**:

> This is an example of a quote

When you want to add a quote in Markdown, Prefixing the line with a ">" converts it into a block-quote.

### LINKS

```
[title](http://)

```

### HIGHLIGHT

```

==Highlight==

```
### BOLD 

```

**text**

```

**Produces**:

**text**

### Syntax Highlighting

```

    ```language example-javascript

        [...]

    ```

```

**Produces**:

```language example-javascript
   [...]
```

### INLINE CODE

```

` A code snippet `

```

**Produces**:

` A code snippet `

Using a single back-tick around a word in a sentence, you can show a quick `code` snippet.

Indenting by 4 spaces will turn an entire paragraph into a code-block.

### HORIZONTAL RULES

```

"---"

```
Want to throw-down a quick divider in your dosumentation to denote a visual separation between different sections of text? No problem. 3 dashes produce

---

### **For more information on writing markdown files, visit https://blog.ghost.org/markdown/.**
