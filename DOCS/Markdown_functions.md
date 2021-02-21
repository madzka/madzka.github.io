---
layout: default
title: Markdown functions
nav_order: 2
---

![Alt Text for image](assets/markdown_logo.png)


# **MARKDOWN - BASIC FUNCTIONS** 

## This is a quick reference to the basic functions of Markdown. ##

Below you see the most important functions of Markdown Syntax with the examples. The green sentences shows comments which are not visible on the page. Comments are written in < !--text-- >. See the correct characters in Markdown source code.   

To start writing in Markdown you use simple plain text with one or two blank lines between them for example

<!-- Example for normal text -->

    This is a simple line  


For a line break, add either a backslash \ or two blank spaces at the end of the line 

    This is a simple line. This is a simple line. \
    This is a simple line. 

You can add simple title to document
<!-- Example for title -->
Title
=====

You can create *Table of Contents* with Markdown.  

<!-- Example of Headers -->
To create HEADER start a line with a hash # and space. The more hash #, the smaller the header. You get the following effect:

# Header 1  
<!-- Example of paragraph of text -->
Markdown is a great tool for documentation on Github because documentation is only as useful as it is readable. Among other things, Github's flavor of markdown allows for the creation of tables to display data in rows and columns.  

## Header 2 
<!-- Example of another paragraph -->
Each lesson introduces a single Markdown concept with an example. When you see a red pulsing circle in the example, select to examine it for details.

Going to https://commonmark.org/help/tutorial/index.html you find the open source Markdown tutorial with functions description. 
### Header 3 

#### Header 4  

##### Header 5  

###### Header 6  


Markdown has text formatting options.  
To get a bold text put a text line between ** text ** or _ text _.  
<!-- Example for Bold -->
**This is bold text**
__This text is bold too__

To get an italic text put a text line between * text * or _ text _. 
<!-- Example for Italic  -->
*This is italic text*

To create link copy the URL and paste in parentheses [titile](http://)
<!-- Example for Links -->
[Link to Markdown Guide](https://www.markdownguide.org/)

To get image start line with an exclamation point ! and square brackets [  ] then paste the picture path.  

<!-- Example for Images -->
![moon](assets/moon.jpg)


<!-- Just text -->
x=2;

<!-- Example for inline code -->
Specify `x=2;` when x equals two.

To create inline code, wrap text with backtick `. To create a code block place 3 backticks ``` on a line above and below the code block. 

<!-- A block of code -->

```
x=2;
y=3;
z=x+y;
```
To create a Quote start a line with sign greater than > followed by an optional space. 

<!-- Example for Quote -->
> All along the watchtower, princes kept the view  
> While all the women came and went, barefoot servants, too

Markdown bulleted lists followed asterisk sign * in front of each list 
<!-- Example for Bullet List -->
* An item
* Another item
    * A sub-item
    * Another sub-item
* Yet one more item


Numbered List uses numbers followed by period .   
<!-- Example for Numbered List -->
1. Item 1
2. Item 2

To make Tables follow this rule

<!-- Example for Tables -->
| header 1    | header 2    |
| ----------- | ----------- |
| item 1      | item 2      |
| something 1 | something 2 |

