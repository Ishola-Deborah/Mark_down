# What is Markdown??

Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by **John Gruber in 2004**, Markdown is now one of the world’s most popular markup languages.

## Headings

To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.

     # A first-level heading
            
    ## A second-level heading
            
    ### A third-level heading

## Styling Texts
Bold - **THIS IS A BOLD TEXT,CHIDUBEM MUST NEVER FORGET**

Italic - *This is Italic*

Strikethrough - This is a strikethrough text

Subscript - <sub> This is a subcript Text </sub>

Superscript - <sup> This is superscript Text </sup>

## Quoting Text
You can quote a text with ">"
> This is a Quoted Text
>> Another quoted one
>>> CHIDUMEN

## Quoting Code
You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted. You can also press the Command+E (Mac) or Ctrl+E (Windows/Linux) keyboard shortcut to insert the backticks for a code block within a line of Markdown.
The followng are quoted code:
```
git status
git add
git commit
```
## Suppported Color Models
You can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

The background color is `#ffffff` for light mode and `#000000` for dark mode.

## Links
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ). You can also use the keyboard shortcut Command+K to create a link. When you have text selected, you can paste a URL from your clipboard to automatically create a link from the selection.

[MDN](https://www.w3schools.com/html/)

## Relative Link
A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might look like this:

[Readme](README.md)
[The heading section](headings.md)

## Image
You can display an image by adding ! and wrapping the alt text in [ ]. Alt text is a short text equivalent of the information in the image. Then, wrap the link for the image in parentheses ()
![Ict folks](ict-folks.jpg)

## Horizontal Line
Baby girl
***

## Tables
|Col 1 | Col2 | Col3 |
|-------|------|-----|
|This   |  is  | you |
| an     | example| can |
| of    | a table| add|
| with | 2 col  | any text|

## Lists
You can make an unordered list by preceding one or more lines of text with -, *, or +.
- Adam
- Shadow
  
* Lighten
* Darken

+ Lindlyn
+ Touche

To order your list, you can start with number
1. Octopus
2. Penthouse
3. Lighthouse

## Nested List
You can create a nested list by indenting one or more list items below another item.
1. First nested list
   - Second nested list
     - Third nested list
       - Fourth nested list 
  
## Check List
To create a task list, preface list items with a hyphen and space followed by [ ]. To mark a task as complete, use [x].

- [x] Go to the Zoo
- [x] Teach setup of Github Profile
- [ ] Explain Github Desktop 
- [ ] Review video features spec supports 
  
If a list start with a parenthesis();
- [ ] \(Optional) Open a followup issue

## Using Emoji
You can add emoji to your writing by typing :EMOJICODE:, a colon followed by the name of the emoji.

@Lion :+1: This PR looks great - It is ready to merge! :angry: :joy: :smile: :blush: :heart:


## Alerts
To add an alert, use a special blockquote line specifying the alert type, followed by the alert information in a standard blockquote. Five types of alerts are available:

> [!NOTE]
 Useful information that users should know, even when skimming content.

 [!TIP]
Helpful advice for doing things better or more easily.

 [!IMPORTANT]
Key information users need to know to achieve their goal.

[!WARNING]
Urgent info that needs immediate user attention to avoid problems.

[!CAUTION]
Advises about risks or negative outcomes of certain actions.

### Flashcard 1

**Question:** What is the capital of France?
**Answer:** Paris

---

### Flashcard 2

**Question:** What is the symbol for the element Gold?
**Answer:** Au

---

### Flashcard 3

**Question:** Who wrote the play "Hamlet"?
**Answer:** William Shakespeare

---

### Flashcard 4

**Question:** What is the powerhouse of the cell?
**Answer:** Mitochondria

---

### Flashcard 5

**Question:** What is the formula for the area of a rectangle?
**Answer:** Length x Width

# My Presentation

---

## Slide 1

This is the first slide of my presentation.

---

## Slide 2

Here's a list:
- Item 1
- Item 2
- Item 3

---

## Slide 3

### Subheading

![Image](https://example.com/image.jpg)

---

## Slide 4

```html
<button onclick="alert('Hello!')">Click me</button>
