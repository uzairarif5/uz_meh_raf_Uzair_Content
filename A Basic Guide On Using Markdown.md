This document is meant for non-coders learning how to use .md files for the first time, it is suppose to be very simple. If any experts see any mistakes, feel free to message me.

I would prefer if your read this doc at Github: https://github.com/uzairarif5/uz_meh_raf_Uzair_Content/blob/main/A%20Basic%20Guide%20On%20Using%20Markdown.md

Switch between preview and code in Github to see the difference.

# This is Heading (also called H1)

This is a normal paragraph. Always make sure to go to new line twice for the next paragraph.
A single new line won't work.




Multiple new lines will not work. If you really need multiple new lines, use:
<br/>
<br/>
<br/>
"br" means break.

Links are made [like this](https://i.pinimg.com/736x/31/dc/76/31dc76b88cfba521b6f3836b8f439a03.jpg).

## This is also heading (2nd level, also called H2)

### This is H3

#### H4

##### H5 

###### H6 

####### H6 is the highest

#Make sure to add a space, otherwise it will not work.

# Another Header

You can also put images in here, like so: 

![alternative text if the image does not exists](https://source.roboflow.com/dcGjORvHS9Tf5W6627Y58CEWlBm2/0NJK2wMshvFBp6FwL0Yn/original.jpg "This is a title, which will be displayed when a mouse hovers on the image")

Here is the html way:

<img alt="alternative text if the image does not exists" src="https://source.roboflow.com/dcGjORvHS9Tf5W6627Y58CEWlBm2/0NJK2wMshvFBp6FwL0Yn/original.jpg" title="This is a title, which will be displayed when a mouse hovers on the image">

You can specify width or height:

<img alt="alternative text if the image does not exists" src="https://source.roboflow.com/dcGjORvHS9Tf5W6627Y58CEWlBm2/0NJK2wMshvFBp6FwL0Yn/original.jpg" height="50px" title="This is a title, which will be displayed when a mouse hovers on the image">
<img alt="alternative text if the image does not exists" src="https://source.roboflow.com/dcGjORvHS9Tf5W6627Y58CEWlBm2/0NJK2wMshvFBp6FwL0Yn/original.jpg" width="100px" title="This is a title, which will be displayed when a mouse hovers on the image">

- You can also make bullet points
- Here is another

1. Bullet points can also be numbered.
2. This is a second point.

You can also do <i>italics</i> and <b>bold</b>.

There are _two_ ways to do *emphasis*.

There are __two__ ways to do **strong**.

<i>Italics</i> and *emphasis* look the same, and so do <b>bold</b> and **strong**, so what's the difference? The purpose of <i>italics</i> and <b>bold</b> are purely visual, while *emphasis* and **strong** have semantic meaning, screen readers and screen engines can make use of them.

To do a ~~strikethrough~~, you can use tilde.

To identify a piece of text as code, use backticks (`if text.isBackticks then codetime`). Code can also span multiple lines:
```
if user.reading
  then print("good day!")
if user.curiousAboutUsingTags:
  then print("Tags don't work here, for example <b>these tags</b> have no affect.")
```

To create a horizontal rule, use three or more asterisks (***) by themselves:
******

Here | is | a | table
-|-|-|-
col1 | col2 | col3| col4
col1 | col2 | col3| col4

The hyphens are there to separate the table header and table body. The hyphens row can also specify text alignment using colons. A colon on the left of the hypen make it left-aligned, on right of the hyphen makes it right-aligned and on both sides of the hyphen makes it center aligned. Default is left:

Here | is | a | table
-|:-|-:|:-:
col1 | col2 | col3| col4
col1 | col 2 | col3 | col4

You can add references in footnotes like so[^1]. You can name them anything[^anything] and they will be automatically numbered.

Lastly, if you are citing something from another resource, you can use quotes or blockquotes. <q>Quotes</q> are for inline, while blockquotes span multiple lines. For example:

> Use ">" to do blockquotes.
>
> Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since 1966, when designers at Letraset and James Moseley, the librarian at St Bride Printing Library, took a 1914 Cicero translation and scrambled it to make dummy text for Letraset's Body Type sheets. It has survived not only many decades, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised thanks to these sheets and more recently with desktop publishing software including versions of Lorem Ipsum.[^randomText]

> Not adding a ">" in between causes a break. 
>> Use ">>" for double blockquotes.

[^1]: This is a reference for footnote
[^anything]: Another reference
[^randomText]: This is from https://www.lipsum.com