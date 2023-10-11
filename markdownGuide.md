# Markdown Reference Guide

Popular markdown syntax.  
Markdown preview: Ctrl+K V or Ctrl+Shift+V

## Table of Contents

1. [Headings](#headings)
2. [Paragraphs](#paragraphs)
3. [Line Breaks](#line-breaks)
4. [Styling](#styling)
5. [Blockquotes](#blockquotes)
6. [Lists](#lists)
7. [Checklist](#checklist)
8. [Code](#code)
9. [Links](#links)
10. [Images](#images)
11. [Tables](#tables)
12. [Emojis](#emojis)
13. [Footnotes](#footnotes)

## HEADINGS

# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6

## PARAGRAPHS

Use a blank line to separate two bodies of text.

Don't add spaces in front of your paragraphs.

## LINE BREAKS

End a line with two or more spaces (called "trailing whitespace"), and then type Enter/Return.  
Like this!

## STYLING

Italics: *asterisk* or _underscore_

Bold: **asterisks** or __underscores__

Strikethrough: ~~tildes~~

Underline: <ins>Important Title</ins>

Center: <center>Center of page</center>

Subscript: H<sub>2</sub>O

Superscript: 4<sup>2</sup>

## BLOCKQUOTES

> Today was a beautiful day.
>
>> It was bright and warm outside.

## LISTS

1. First list item
2. Second
3. Third

- Unordered list
* or
+ or
    + indent

## CHECKLIST

- [x] task 1
- [ ] task 2
- [ ] task 3


## CODE

To include code, use `backticks`.

To add code blocks, fence code with three backticks:

JavaScript example:

```JavaScript
let t = "string value";
console.log(t);
```

JSON example:

```JSON
{
    "firstName": "Burnt",
    "lastName": "Soup",
    "age": "30"
}
```

## LINKS

Enclose the link text in brackets, followed by the URL in parentheses:

> Watch videos on [Youtube](https://youtube.com/).

*you can also add a tooltip when the user hovers over the link by adding a string of text enclosed by quotation marks, within the parentheses:

> Watch videos on [Youtube](https://youtube.com/ "I love watching videos!").

To turn an email or url address into a link, use angle brackets:

> <https://youtube.com/>  
> <email@outlook.com>

## IMAGES

Add an exclamation mark, followed by alt text in brackets, and then the path/URL to the image in parentheses:

![Microsoft logo](https://blogs.microsoft.com/wp-content/uploads/prod/2012/08/8867.Microsoft_5F00_Logo_2D00_for_2D00_screen-1920x706.jpg)

## TABLES

Use three or more hyphens to create each column header and then use pipes to separate each column:

| Col 1   | Col 2   | Col 3 |
| :-----   | :-----:   | -----: |
| Left aligned!   | Centered | Right |
| Hi there | Okay | Alright |

## EMOJIS

:smile:  :grinning:  :slightly_smiling_face:  :grinning:  :frowning_face:  :neutral_face:  :sob:  :exploding_head:  :rage:  :smiling_imp:  :partying_face:  
:heart:  :100:  :warning:  :no_entry:  :white_check_mark:  :x:

## FOOTNOTES

Step 1 - Create the reference by adding a caret followed by some identifier (numbers or words, without spaces) within brackets.  

Step 2 - Add the footnote using the same caret+identifier, followed by a colon and your text.

Example:  
John, a Psychometrician[^1], published an article[^2] describing testing procedures.

[^1]: a person who studies the science of test-taking.
[^2]: <https://www.google.com/>
