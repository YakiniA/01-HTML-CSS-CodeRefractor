# 01 HTML CSS Git: Code Refactor

This assignment on HTML and CSS focus on code refractor, taking the existing code and refabricate to make it more clear, ensured that all the links are working correctly, organized to follow the semantic structure of HTML elements, included the comments for every change.

# Changes done in HTML:

* Included a clear and precise title for the webpage.
* Used semantic HTML elements like header, nav, section, aside, footer to clearly understand its purpose instead of the plain div tag.
* The link for Search Engine Optimization in the header is not working as the id attribute is missing. Fixed the issue and ensured all the links are working correctly.
* Used the id attribute alone for Search Engine Optimization, Online Reputation Management, Social Media Marketing as both id and class attributes have the same values. This avoids confusion and repetition, it is simple to refer with id attribute alone.
* For all the image elements, the alt attribute has been added.
* Deleted the closing tag(</img>) for the image as it is not necessary.

# Changes done in CSS:

* Changed the CSS file to incorporate the change in HTML for the semantic tags header, nav, section, aside, footer. 
* Merged all the Benefit - lead, brand, cost separated by commas because their properties are the same. By this, repetition of the same code is avoided.
* For Search Engine Optimization, Online Reputation Management, Social Media Marketing, the CSS properties are applied by using the id attribute instead of class. And being their properties same merged into a single one using comma-separated.