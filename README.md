<!--List of changes to HTML File--->
Line 8  ADD "TYPE" to the link rel line

Line 13-23:Oganized header listings/tabs to a cleaner one item per line look

Line 15-22: Changed top tabs to be a nav element as it seems as a menu or navagtion tool for the page

Line 30:class="search-engine-optimization"> was missing the ID tag on the same line

Line 31-52: Add ALT tabs/labels to images so if there is an issue with the image it atleast shows the name of it.

Entire File: Replaced divs using HTML 5 semantic layouts such as section, sidebar, nav.


<!--List of changes to CSS File-->

Line 27-41: Since we updated the tool bar at the top to a nav element we have to change the div class to nav on css style sheet

Line 89-133:  Added "mutiple class" tag to sections that have same styling..example(.benefit lead, .benefit brand, .benefit cost) <!-- Im not sure this is proper semantics as it would be as easy if you would like to change a specific class such as ".benefit brand? but not ".benefit cost">

Let me know if there are any issues.

# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

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

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.

