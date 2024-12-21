# Markdown Extension Ideas

## MystMD
https://mystmd.org/spec/

### References 

````
see {numref}`my-table`

```{list-table}  Caption text
:name: my-table

*   - Head 1
*   - Row 1
```
````

### Footnotes 

```
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.
```

## ArchieML

https://archieml.org/

### Key Value Pair

```archieml
key: value
another_key: another_value
```

### Nested Objects

```archieml
  {colors}
  red: #f00
  green: #0f0
  blue: #00f
  
  {.numbers}
  one: 1
  ten: 10
  one-hundred: 100
  {}
  
  nestedKey: nestedValue

  {months}
  january: 0
  february: 1
  
```

### Arrays

```
array[]: 
* item1
* item2
```

### Arrays of objects

```archieml
array[]:
* key1: value1
  key2: value2
* key1: value3
  key2: value4
```

## Multimarkdown 

https://fletcher.github.io/MultiMarkdown-6/

### abbreviation format 
    ```
    [>HTML]: Hypertext Markup Language
    Hypertext Markup Language (HTML) and HTML

    [>(HTML) Hypertext Markup Language] and HTML
    Hypertext Markup Language (HTML) and HTML
    ```
    
### citations

    ```
    Cite a source.[p. 42][#source]
    [#source]: John Doe. *A Totally Fake Book*. Vanity Press, 2006.
    Cite a source.(p. 42, 1)

    John Doe. A Totally Fake Book. Vanity Press, 2006.  ↩

    Cite a source.[p. 42][#John Doe. *A Totally Fake Book*. Vanity Press, 2006.]

    Cite a source.(p. 42, 1)

    John Doe. A Totally Fake Book. Vanity Press, 2006.  ↩
    ```

### Glossaries 

```
[?(glossary) The glossary collects information about important
terms used in your document] is a glossary term.

[?glossary] is also a glossary term.

[?glossary]: The glossary collects information about important
terms used in your document
```

## Kramdown

https://kramdown.gettalong.org/syntax.html#inline-attribute-lists

### Inline Attribute List

```
This *is*{:.underline} some `code`{:#id}{:.class}.
A [link](test.html){:rel='something'} and some **tools**{:.tools}.
```

### Block Attribute List

```
A simple paragraph with an ID attribute.
{: #para-one}

> A blockquote with a title
{:title="The blockquote title"}
{: #myid}

{:.ruby}
    Some code here
```

## Remark 

### Remark Autolink References 

```
- Example ([JIRA-4275](https://example.atlassian.net/browse/JIRA-4275))
Set fix
```

### Remark Attr

Images:
`![alt](img){attrs} / ![alt](img){ height=50 }`

Links:
`[rms with a computer](https://rms.sexy){rel="external"}`

Autolink :
`Email me at : <mailto:falseEmail@example.org>`

Header (Atx) :

```
### This is a title
{style="color:red;"}

or

### This is a title {style="color:yellow;"}
```

Header :

This is a title


