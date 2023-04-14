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

