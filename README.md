# Markdown Syntax
* Headings
* Paragraphs
* Line Breaks
* Emphasis ( Bold and Italic )
* Lists
* Code Blocks
* Images

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

Code Blocks

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

Images 

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

    
![img](./img1.jpg)


