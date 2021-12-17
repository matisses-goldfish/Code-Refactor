# Code Refactor: 01 Homework 📚

## Task Requirements (reference)
"Refactoring existing code (improving it without changing what it does) to meet a certain set of standards or to implement a new technology is a common task for front-end and junior developers. For this particular homework assignment, a marketing agency has hired you to refactor an existing site to make it more accessible."

----

## Acceptance Criteria (reference):

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
```
---
## Overall Goal
My main goal of this project was to adhear to the requirements, provided by my client, in order to increase both accessibility and page placement on search engines, such as Google. 

---

## My Process 

1. STEP 1: Look through all existing img elements and add alttags with short descriptions. 
    * WHY?: This allows screen readers to verbaly communicate to the consumer what might be occuring in an icon or photo. This creates a larger understanding of the pages content to those with visual imparments. 



2. STEP 2: Change non-semantic elements, such as div to a semantic elements, such as article or section.
    * WHY?: Non-semantic elements can be helpful for orginizing code, but they say nothing about the content and are unaccessiable to those with screen readers. By switching out div element for a section element, the consumer is now able to understand whats occuring in a specific portion of a web page. 



3. STEP 3: Change title elements and class="" tags to match the existing content. 
    * WHY?: When the title of a page has no larger meaning or is unrelated to the content it contains, it can be confusing and disorienting. 

    > Example: The title of the page was previously set as "Title", but this say nothing about the pages content or meaning. Therefore I changed it to match the company name, "Horiseon".

----
## Final code
![screenshot of code with changes made](Code-Explination.png)

---

## Clients Unchanged Website
![Clients Website unchanged](01-html-css-git-homework-demo.png)

---
