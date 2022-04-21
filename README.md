# Marketing Agency Code-Refactor
Web development: accessibility. Mission:  Take existing code and refactor it (recall that to refactor code is to improve it without changing what it does)

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
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

Class requirements Homework Critera:

Added Semantic HTML elements
- Header
- Nav
- Section
- Aside
- Footer

Added Alt tags to all imagery
*I moved the class float-left & float right to the beginning of the element content*

Change .Class to #ID Variables
Combine content section into one class - content
Combine benefits section into one class - benefits

CSS Additional Updates
- add nav within the .header (div) to .header nav
- change .hero to .hero img
 - - remove background declaration
 - - set height to auto 
- Rearrange class and id in the order it appears within the HTML index.html file

I hade issue with github  'error: failed to push some refs to'

## Feature to apply next
- Make mobile friendly