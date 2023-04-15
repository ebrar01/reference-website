# reference-website

1. Naming convention for all filenames, paths and folders 
- The naming convention for all filenames should be lowercase, no spaces and dashes are fine. Folder naming convention should be similar to filenames. For paths, the folders, assets and files should be inside the root folder so they can be easily linked inside any .html files.

2. Best practices for commit messages 
- Best practices for commit the messages is using the GitHub desktop app. Commit the code to the main first, and then push it to the origin. In this way you can see your code changes in the GitHub. 

3. What is HTML? 
- HTML or The HyperText Markup Language is a coding language for documents designed to be displayed in a web browser.

4. Proper syntax for HTML tags.
- After you find the spesific tag which is defining the purpose of the text, put "<" before the tag, and put ">" to close the tag. Or use "/" for comments. 

5. Explain or demonstrate commonly used html tags/elements:
    - headings: h1-h6 ; h1 is used for most important heading of the web page and only used once. h6 is the least important and smallest heading. They go according to their importance from largest(h1) to smallest(h6). 
    - p ; used for paragraphs. It is a block-element. It always start on a new line. Browsers automatically add margin before and after each "p" element. 
    - lists: ul, ol, dl ; "ul" describes unordered list, "ol" describes ordered list. "li" tag need to be used for each list item under "ul" or "ol" list tags. And "dl" describes description list. "dt" used for term or name, and just used once. "dd" used for description of term, and can be more than one. 
    - a ; this tag used for links in html. Proper way to do it is; `<a href=“”> Link text </a>`
    - img ; this tag is used to embed an image in an HTML page. Images are not technically inserted into a web page; images are linked to web pages. Proper way to do it is; `<img src=“” alt=“” />`
    - q ; used to mark up quotes embedded in other elements like a paragraph.  This element is intended for short quotations that don't require paragraph breaks. 
    - blockquote ; used for long quotations. 
    - cite ; Marking the source of the quote. 
    - em ; used for words that have a stressed emphasis compared to surrounding text.
    - strong ; used for strong importance or urgency emphasis. 
    - b ; used for keywords or make the text bold. 
    - i ; used for Another language, technical term, title
    - small ; Used for specifying smaller text. 

6. Explain block Elements and also explain the list of block elements and why they are used from below: 
- A Block-level element occupies the entire horizontal space of its parent element, and vertical space equal to the height of its contents, thereby creating a "block".
    - html ; this elements always need to give a meaning to your content.
    - head ; this element includes the metadata to make the HTML page readable for machine or web browser. 
    - body ; this element includes the content for the webpage. Every document can has only one body element.
    - header ; this element generally positions on the top of the page and can include a logo or company name. It is a introductory content. Headings, subheading, authors can put into this element. 
    - nav ; this element are used for navigation links. Navigation links can be use for within the current documents or to the other documents. 
    - main ; this element represent the main content of the page. Every web page can has only one main element. It is also tells the browser to where the main content is.
    - section ; this element is used to wrap around related pieces of content. Every section element has its own heading.
    - article ; this element is used to define an independent, self-contained content. It can be be independently distributable or reusable. 
    - div ; Block element used to group elements together.
    - aside ; this element represent a document's portion whose content is only indirectly related to the document's main content.Asides are frequently presented as sidebars.
    - footer ; this element used for links, copyright information, extra information about the company, terms and services. This element genarally positions at the bottom of the page. 
    - span ; this element is used to mark up a part of a text, or part of a document. Span element is an inline container element. 
    - small ; this element used for specifying smaller text.

7. Explain why accessibility is important and also explain the accessibility properties like:
- Accessibility is important, because our web pages need to be proper and easy to reach for all users, even who has any kind of disability. 
    - landmark roles ; This element is for the people who is using the screen readers. They can jump the specific section that they want within the website. 
    - aria labels ; These are the descriptions for the links that used in the webpage. 
    - image alternative texts ; This elements are for an explanation for the photos or images. This can be for if the photo is not uploading or someone who can not see the image. 

8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file) 
- CSS is Cascading Style Sheets is the language to control the appearance of our HTML pages. You need to create a css folder. And a css file into that css folder. The extension needs to be .css.  After you create it, you need to link your css file to the html page. You need to put it under the "head" element, with using the "link" element. The proper way to do it is ;  `<link rel="stylesheet" href="css/style.css">` .

9. What is the difference between CSS property and value (write explanation and an example code) 
- The CSS property is The type of design you want to add. Ex. width, color, border, etc. But the value is Accepted value for property. Ex. 30px, blue, etc. 

10. Why do we use border-box property in CSS? 
- border-box tells the browser to account for any border and padding in the values you specify for an element's width and height. 

11. Explain different type of ways we can add spacing to an element. 
- You can use padding, border or margin to add spacing to your element. Also you can add them manually as well. 

12. What is the main difference between margin and padding? 
- Padding represents the amount of inner space an element has, while the margin is whitespace available surrounding an element. 

13. What are different types of display properties? 
- There are four types of display properties. They are; inline, block, inline-block and none. INLINE ; allows element on the same line; height and width properties have no effect. BLOCK ; force the element to be on its own line regardless of its width. INLINE-BLOCK ; element is formatted as an inline element but you can apply height and width values. NONE ; the element is completely removed. 

14. Write a brief explanation of flexbox property.
- It is a one-dimensional layout model. For more complex layouts you can use Flexbox to control the flow and alignment of
elements. 

15. What are different types of flexbox properties and what is the major difference between them? 
- The flexbox properties are; flex-direction, flex-wrap, flex-flow, justify-content, align-items, align-content. The main difference is they can be used in row or a column. And you have more options to create your content according to the margin, padding, or etc. 

16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property.
- In the .css file, after you defined the element that you want to position, you need to apply which flexbox property you want. They might be; flex-direction, display, flex-wrap, justify-content, align-items, align-content, etc. For example if we want to edit the .container element, the code would be ; `.container {display:"the sub property";}`

17. Write a code example on how you will use a flexbox property on a parent element with sub properties. 
- `.container {flex-direction: column-reverse;}`

18. What is CSS grid property? 
- CSS grid is basically two-dimensional grid system to CSS. A grid is a set of intersecting horizontal and vertical lines defining columns and rows. 

19. Write the parent and two sub-properties used for CSS Grid Property. 
- The parent element is GRID CONTAINER. HEADER and FOOTER two sub-properties examples for CSS Grid Property. 

20. What is the difference between display: flex and display: grid? 
- Flexbox property is designed for one-dimension, either row or column. Grid properties is designed for two-dimensions; rows and columns at the same time.  

21. What sub-property we use to divide elements in CSS Grid properties?
- We use `"grid-template-columns"` 

22. What unit we use to fractionally divide the element width in CSS Grid property and what are others unit we can use alternatively? (Write a code example) 
- We can use `fr` unit to represent a fraction of the available space in the grid container. We can use `px` unit as well. 1fr = one fraction of the available space minus the two fixed values of 200px plus 200px. For example ; `{grid-template-columns: 3fr 3fr 3fr;}` .

23. What is the area property in CSS grid we use for the child elements? 
- The Grid Area property specifies a grid item's size and location in a grid layout. And the child elements for are property are; grid-row-start, grid-column-start,grid-row-end, grid-column-end.

24. Which sub-property of display grid you can use to prevent displaying empty columns. Write a code example of that property. 
- The auto-fir sub-property is used for prevent displayinf empty columns. `.grid-container{grid-template-columns: repeat(auto-fit, minmax(200px, 4fr));}` 

25. Explain the steps to add google fonts to your CSS file and how will you link it to the html file. 
- You need to chose your font from google fonts website. The website should give you html and css codes to show how you going to write your code. You need to link your html code into your html file under head element. And also you need to use the css code that the website gave you while you are writing your css codes. 
 