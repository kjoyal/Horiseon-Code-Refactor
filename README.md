Horiseon Code Refactor
    In this refactoring I was given a sample of HTML and CSS code and was tasked with the following:
       
        ## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title

For my first task, I refactored the HTML code to get rid of all but one of the div tags and replace them with semantic HTML elements, such as: header, footer, body, main, etc...
Each element was grouped into a logical page structure so as to avoid confusion and redundency...
Alt attributes were provided for each image, including a brief description of the image, should some of the images not load...
The title was changed to reflect the title of the header, logical and concise...
Heading attributes are organized in sequential order...

Secondly, upon inspection of the CSS file, a few class selectors needed to be updated to reflect the changes to the div tags...
Many of the elements in the document were listed out multiple times for various commands.  Tags that were alike in function and appearance were then grouped together to avoid unnecessary redundancy while also streamlining the code.  With less code to read it will be easier to debug later on and quicker to add attributes should I wish to add styles.