# The Difference :
### HTML: :wrench: :hammer:
In simpler terms, think of HTML as the building blocks of a webpage. It's like a set of instructions that tells web browsers how to display different elements,
such as text, paragraphs, heading, images, and videos, on a page. 
### CSS: :rainbow:
In simpler terms, think of CSS as the "stylist" for your webpage. It's what makes your webpage look visually appealing and well-designed.
CSS works by specifying rules for how different HTML elements should be displayed—using, for example, fonts or colors.

## HTML pointers :
* [RESSET](./resset.css) : Every web browser has its own default styles for different elements. How `Google Chrome` renders headings, paragraphs, lists, and so forth may be different from how `Internet Explorer` does. To ensure cross-browser `compatibility`, it is a good practice to implement a `resset` of all parts and elements of your html to a `uniform` basic raw form , before implementing your actuall `css` styling. 
This file contains the popular `Eric Meyer's` css resset code, which would be linked in the `head` element of your HTML code, to resset every other values of each element to
a uniform font,colour,size etc. 

* SEMANTIC_CODE : Dessist from styling, colouring or adding fonts to your page using HTML, that is the job of `css` in a seperate file. HTML should be the carrier of the page content structured properly with the proper elements and tools. This gives an ideal interpretation of the content , meaning and usage of the page to both the computer and human users. Including `css` sstyling codes in your `HTML` code file is bad practice:x:

* [SPECIAL_CHARACTER](./special_char_link.txt) : Special characters include various punctuation marks, accented letters, and symbols. When typed directly into HTML, they can be misunderstood or mistaken for the wrong character by either the computer or human; thus they need to be encoded. In this file is a link with a long list of characters and their direct codes.

* HIEARACHY and INDENTATION : HTML elements are hierarchical, which means that they can be nested inside each other to create a tree-like structure of the content on the web page. Code should be well-formed and properly indented, with each element on its own line and each level of hierarchy indented by one level. This makes the code easier to read and understand, and can help to avoid errors. 

* [BASIC_HTML](./basic.html) : This file contains a basic html file structure with some description comments.
    - A void long lines of codes. If long text should be in one line on web page, break them into multiple lines in the HTML code
    - Use proper indentations, white spaces and blank lines , for readability.
    - Never skip the `<title>` element in your HTML document
    - Never skip the `<html>` , `<body>` , and `<head>` tags. This is the first step to semantic codes
    - The lang attribute is vital to include within an `<html>` element. Its primary goal is to define the natural language of the content. 
    Browsers and search engines use this information for a more accurate page ranking in search results. If there's a piece of text in a different language, 
    you can specify the language with the lang attribute for the element that surrounds the content.
    - Give everything the appropriate hierarchy.
    - Some elements are self closing eg. `<br> <embed> <hr> <img> <input> <link> <meta> <param> <source> <wbr>`
    - Observe and use `block` and `in-line` elements properly
        * Block-level elements begin on a new line, stacking one on top of the other, and occupy any available width. 
        Block-level elements may be nested inside one another and may wrap inline-level elements eg- `<header> , <p>` , etc
        * Inline-level elements must not begin on a new line. They fall into the normal flow of a document, 
        lining up one after the other, and only maintain the width of their content. Inline-level elements may be nested inside one another; 
        however, they cannot wrap block-level elements. eg, `<span> <a> <pre>` etc
    - always set the height or width of images. Otherwise when the image loads, the content on the webpage will be shifted.
    - `<strong>` and `<em>` are semantic tagss used to put emphasis, even though they both bold and italics the texts withing them respectively.
    `<b>` and `<i>` can be used respectively in place of them.
    - some text formating tags 
        * <b> tag - Bold Text
        * <i> tag - Italic Text
        * <u> tag - Underlined Text
        * <strong> tag - Strong Text
        * <em> tag - Emphasized Text
        * <mark> tag - Highlighted Text
        * <sup> tag - Superscript Text
        * <sub> tag - Subscript Text
        * <del> tag - Deleted Text
        * <ins> tag - Inserted Text
        * <big> tag - Big Text
        * <small> tag - Small Text
