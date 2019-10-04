# Markdown basic syntax

>The document is a aggregation for the basic syntax of markdown, retrieved from https://www.markdownguide.org/basic-syntax/
>
>This document should be read in correspondence with the rendered output.

## Headings

To create a heading, add number signs (#) in front of a word or phrase

### Level 3

#### Level 4

##### Level 5

###### Level 6

We get 6 levels of headings. From 1 to 6.

## Paragraphs

To create paragraphs, use a blank line to separate one or more lines of text. You should not indent paragraphs with spaces or tabs.

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

## Line breaks

This is the first line.  
And this is the second line.

## Emphasis

### **Bold**

To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

I just love **bold text**.  
I just love __bold text__.  
Love**is**bold

### *Italic*

To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.

Italicized text is the *cat's meow*.  
Italicized text is the _cat's meow_.  
A*cat*meow  

### ***Bold and Italic***

This text is ***really important***.  
This text is ___really important___.  
This text is __*really important*__.  
This text is **_really important_**.  

### Block Quotes

To create a blockquote, add a > in front of a paragraph.

> Dorothy followed her through many of the beautiful rooms in her castle.

#### Blockquotes with Multiple Paragraphs

Blockquotes can contain multiple paragraphs. Add a > on the blank lines between the paragraphs.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

#### Nested Blockquotes

Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

#### Blockquotes with Other Elements

> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
>*Everything* is going according to **plan**.

### Lists

#### ordered list

1. First item
2. Second item
3. Third item
4. Fourth item

---

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

---

#### Unordered Lists

- First item
- Second item
- Third item
- Fourth item

---

- First item
- Second item
- Third item
  - Indented item
  - Indented item
- Fourth item

### Adding Elements in Lists

- This is the first list item.
- Here's the second list item.

    I need to add another paragraph below the second list item.

    > A blockquote would look great below the second list item.

-And here's the third list item.

### Code

At the command prompt, type `nano`.

``Use `code` in your Markdown file.``

**To create code blocks, indent every line of the block by at least four spaces or one tab.**

    <html>
      <head>
      </head>
    </html>

### Links

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

<https://www.markdownguide.org>

<fake@example.com>

I love supporting the **[EFF](https://eff.org)**.

This is the *[Markdown Guide](https://www.markdownguide.org)*.

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends
of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to
eat: it was a [hobbit-hole][1], and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

### Images

![My avatar is so cool!](./avatar.jpg "My Avatar")

#### Linking Images

To add a link to an image, enclose the Markdown for the image in brackets, and then add the link in parentheses.

[![An old rock in the desert](./avatar.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.google.com)

### Escaping Characters

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.

### Tables

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

Creating tables with hyphens and pipes can be tedious. To speed up the process, try using the [Markdown Tables Generator](http://www.tablesgenerator.com/markdown_tables). Build a table using the graphical interface, and then copy the generated Markdown-formatted text into your file.

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.
    
    `{ my code }`
    
    Add as many paragraphs as you like.

~~The world is flat.~~ We now know that the world is round.

- [ ] Write the press release
- [ ] Update the website
- [ ] Contact the media

Automatic URL  
http://www.example.com

Disabling Automatic URL Linking  
`http://www.example.com`

## Math

$$
x+y=10
$$

$$
x^2+\cos(\theta)
$$

$$
J_\alpha(x) = \sum_{m=0}^\infty \frac{(-1)^m}{m! \Gamma (m + \alpha + 1)} {\left({ \frac{x}{2} }\right)}^{2m + \alpha}
$$

$$
J_\alpha(x) = \sum_{m=0}^\infty \frac{(-1)^m}{m! \Gamma (m + \alpha + 1)} {\left({ \frac{x}{2} }\right)}^{2m + \alpha}
$$

$$
x^{y^z}=(1+{\rm e}^x)^{-2xy^w}
$$

$$
\left. \frac{{\rm d}u}{{\rm d}x} \right| _{x=0}
$$

To get more information for mathematical formula, [click here](https://www.zybuluo.com/codeep/note/163962#mjx-eqn-eqsample)

