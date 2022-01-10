User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines

Acceptance Criteria
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

Changes: 
Replaced generic <div> tags with semantic <header>,<main>, <aside><section> HTML elements.

Organized structure of code to follow the structure of the page. Then added comments in HTML and CSS to help future developers easily find corresponding sections. 
Consolidated CSS styles that were identical to clean up redundancy of the code. 

Added alt attributes to all image elements to make accessible by screen readers.

Renamed the title of the page "Horiseon" to help end users see what webpage they are visiting on the title tab. 




