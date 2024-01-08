# The Markdown elements outlined in the original design document

Markdown is a lightweight markup language designed for easy formatting of plain text. It is widely used for creating simple and clean documents with a focus on readability and ease of use. Markdown documents can be easily converted into HTML, making them suitable for various purposes such as writing documentation, creating web pages, and composing emails

## Headers:- 
Markdown provides six levels of headers, indicated by the number of hash symbols (#). The more hash symbols, the smaller the heading.


| Name       |   | Markdown Syntax |
|------------|---|-----------------|
| Heading  1 | - | # Hariom        |
| Heading  2 | - | ## Hariom       |
| Heading  3 | - | ### Hariom      |
| Heading  4 | - | #### Hariom     |
| Heading  5 | - | ##### Hariom    |
| Heading  6 | - | ###### Hariom   |

## Paragraphs:- 
To create paragraphs, use a blank line to separate one or more lines of text.

Follow for more Data Science Content <br> 
Share the content with your coder friend  

## Line Breaks 
To create a line break or new line <br>, end a line with two or more spaces, and then type return.

You can use two or more spaces (commonly referred to as “trailing whitespace”) for line breaks in nearly every Markdown application, but it’s controversial. It’s hard to see trailing whitespace in an editor, and many people accidentally or intentionally put two spaces after every sentence. For this reason, you may want to use something other than trailing whitespace for line breaks. If your Markdown application you can use the **BR** HTML tag.

# Emphasis
You can add emphasis by making text bold or italic.

## Bold

To bold text, add two asterisks or underscores before and after a word or phrase. To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.

| Name         |   | Markdown Syntax                |
|--------------|---|--------------------------------|
| Bold type 1  | - | You just love ** code hariom **. |
| Bold type 2  | - | I just love __ bold text __.     |
| Bold type  3 | - | Love ** is ** bold               |

## Italic

To italicize text, add one asterisk or underscore before and after a word or phrase. To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters

| Name         |   | Markdown Syntax                |
|--------------|---|--------------------------------|
| Italic type 1  | - | You just love * code hariom *. |
| Italic type 2  | - | I just love _ bold text _.     |
| Italic type  3 | - | Love * is * bold               |


## Bold and Italic

To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.

| Name                                 |   | Markdown Syntax           |
|--------------------------------------|---|---------------------------|
| This text is ***really important***. | - | This text is ***  #  ***. |
| This text is ___really important___. | - | This text is ___ #  ___.  |
| This text is __*really important*__. | - | This text is __* #  *__.  |
| This text is **_really important_**. | - | This text is **_ # _**.   |


# Blockquotes

To create a blockquote, add a > in front of a paragraph
>  This is a blockquote example

> Dorothy followed her through many of the beautiful rooms in her castle.

## Nested Blockquotes

Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>>  The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with 
> 

# Lists
You can organize items into ordered and unordered lists.

## Ordered Lists
To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.

| Name           |   | Markdown Syntax |
|----------------|---|-----------------|
| 1. First item  | - | 1. First item   |
| 2. Second item | - | 2. Second item  |
| 3. Third       | - | 3. Third        |
| 4. Fourth.     | - | 4. Fourth.      |

## Unordered Lists

To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. Indent one or more items to create a nested list.


| Markdown Syntax |
|-----------------|
| -  First item   |
| * First item    |
| + First item    |

### Output

-  First item
* First item
+ First item

## Code Blocks
Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

1. Open the file.
2. Find the following code block on line 21:

        <html>
          <head>
            <title> Code hariom t</title>
          </head>

3. Update the title to match the name of your website.

## Images
[AlT text of Image]( Image URL)

# Code
To denote a word or phrase as code, enclose it in backticks (`).

At the command prompt, type `Codehariom`. 
# Links

To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://www.linkedin.com/in/realhariom/)).

Our Linkedin Profile link  [Follow on Linkedin ](https://www.linkedin.com/in/realhariom/).

# Tables
To add a table, use three or more hyphens (---) to create each column’s header, and use pipes (|) to separate each column. For compatibility, you should also add a pipe on either end of the row.


| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Alignment
You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |