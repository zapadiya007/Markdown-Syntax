# Markdown Syntax

* Headings
* Paragraphs
* Line Breaks
* Emphasis ( Bold and Italic )
* Lists
* Code Blocks
* Horizontal Rules
* [Links](#links)

Headings
==========
    # Heading 1
    ## Heading 2
    ### Heading 3
    #### Heading 4
    ##### Heading 5
    ###### Heading 6

    Alternate Syntax
    Headings 1
    ========
    Headings 2
    ----------

# Paragraphs
    To create paragraphs, use a blank line to separate one or more lines of text.

# Line Breaks
    To create a line break or new line (<br>), end a line with two or more spaces, and then type return.
    Example : 
        jkjsjfjkjfkjs1  
        djskjjffjjfjdkjf2  
        ckjkfjsdfjlksdjglk3  
        dhjd

# Emphasis

Bold

    To bold text, add two asterisks or underscores before and after a word or phrase. 
    To bold the middle of a word for emphasis, add two asterisks without spaces around the letters.
    Example :
            I just love **bold text**.
            I just love __bold text__.
            Love**is**bold

Italic

    To italicize text, add one asterisk or underscore before and after a word or phrase. 
    To italicize the middle of a word for emphasis, add one asterisk without spaces around the letters.
    Example :
            I just love *bold text*.
            I just love _bold text_.
            Love*is*bold

Bold and Italic 

    To emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase. 
    To bold and italicize the middle of a word for emphasis, add three asterisks without spaces around the letters.
    Example :
            This text is ***really important***.
            This text is ___really important___.
            This is really***very***important text.

# Blockquotes  
    To create a blockquote, add a > in front of a paragraph.
    Example :
            > Dorothy followed her through many of the beautiful rooms in her castle.

Blockquotes with Multiple Paragraphs :

    Blockquotes can contain multiple paragraphs. Add a > on the blank lines between the paragraphs
    Example :
            > Dorothy followed her through many of the beautiful rooms in her castle.
            >
            > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

Nested Blockquotes : 

    Blockquotes can be nested. Add a >> in front of the paragraph you want to nest.
    Example :
            > Dorothy followed her through many of the beautiful rooms in her castle.
            >
            >> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

Blockquotes with Other Elements :

    Blockquotes can contain other Markdown formatted elements. 
    Not all elements can be used — you’ll need to experiment to see which ones work.
    Example : 
            > #### The quarterly results look great!
            >
            > - Revenue was off the chart.
            > - Profits were higher than ever.
            >
            >  *Everything* is going according to **plan**.
    
# Lists

Ordered Lists :

    To create an ordered list, add line items with numbers followed by periods. 
    The numbers don’t have to be in numerical order, but the list should start with the number one.
    Example :
            1. First item
            2. Second item
            3. Third item
                1. Indented item
                2. Indented item
            4. Fourth item

Unordered Lists
        
    To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items. 
    Indent one or more items to create a nested list.
    Example :
            - First item
            - Second item
            - Third item
                - Indented item
                - Indented item
            - Fourth item

Starting Unordered List Items With Numbers
    
    If you need to start an unordered list item with a number followed by a period, 
    you can use a backslash (\) to escape the period.
    Example :
            - 1968\. A great year!
            - I think 1969 was second best.

Code Blocks in list

    Code blocks are normally indented four spaces or one tab. 
    When they’re in a list, indent them eight spaces or two tabs.
    Example :
            1. Open the file.
            2. Find the following code block on line 21:

                <html>
                  <head>
                    <title>Test</title>
                  </head>

            3. Update the title to match the name of your website.

Images in list

    1. Open the file containing the Linux mascot.
    2. Marvel at its beauty.

        ![Tux, the Linux mascot](/assets/images/tux.png)

    3. Close the file.

Nest an unordered list in an ordered list

    1. First item
    2. Second item
    3. Third item
        - Indented item
        - Indented item
    4. Fourth item

## Code

    To denote a word or phrase as code, enclose it in backticks (`).
    Exmaple :
            At the command prompt, type `nano`.
            
Escaping Backticks

    If the word or phrase you want to denote as code includes one or more backticks, 
    you can escape it by enclosing the word or phrase in double backticks (``).
    Example :
            ``Use `code` in your Markdown file.``

Code Blocks
    
    To create code blocks, indent every line of the block by at least four spaces or one tab.
        
        <html>
          <head>
          </head>
        </html>

## Horizontal Rules

    To create a horizontal rule, use three or more asterisks (***), dashes (---), 
    or underscores (___) on a line by themselves.
    Example :
            ***
            ---
            _________________

## Links

    To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) 
    and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).
    Example :
            My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

Adding Titles
    
    You can optionally add a title for a link. 
    This will appear as a tooltip when the user hovers over the link. 
    To add a title, enclose it in quotation marks after the URL.
    Example :
            My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy")

URLs and Email Addresses
    
    To quickly turn a URL or email address into a link, enclose it in angle brackets.
    Example :
            <https://www.markdownguide.org>
            <fake@example.com>

Formatting Links

    To emphasize links, add asterisks before and after the brackets and parentheses. 
    To denote links as code, add backticks in the brackets.
    Example :
            I love supporting the **[EFF](https://eff.org)**.
            This is the *[Markdown Guide](https://www.markdownguide.org)*.
            See the section on [`code`](#code).





![img](./img1.jpg)


