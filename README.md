# goldmark markdown extensions

goldmark is a well-known and respected markdown to html converter.  
ref: github.com/yuin/goldmark(https://github.com/yuin/goldmark)  

The processor has extension for the parser and the renderer.  

For a quick review, the goldmark parser first creates block elements, and then parses each block element for inline elements.

An example of a block element is a paragraph.
Examples of inline elements are images and emphasis.

This package has two extensions for inserting attributes into the html elements:

## BlockAttrExt
The Block attribute extension is a slightly modified fork of mdigger's repository(https://github.com/mdigger/goldmark-attributes)

## ImgAttrExt
The image attribute extension is an adaption for image tags in markdown. The parser attributes have been modified to keep numeric attribute values as strings and not convert them to float64.

