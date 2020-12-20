# Homework-Week-1: Code Refactor

### Table of Contents 

1) The Repository
2) User Story
3) Code Refactoring
    - Example of Code Cleanup
    - Horiseon Web-page Before/After
    - Final Result after Code-Refactoring
5) Changes made to code (html/css)
    - FIXED HEAD
    - FIXED HEADER
    - FIXED MAIN IMAGE
    - FIXED SECTION/ARTICLE
    - FIXED SECTION/ASIDE
    - FIXED FOOTER
    - FINAL CHANGES
6) Overall Conclusion

# The Repository

- This repository shows a collection of edits I made to the code for the Horiseon company web-page. Below I share the steps I took to simplify the code that I was provided for this assignment. 

- My goal was to streamline the html and css, removing unnecessary elements or selectors, properly organizing each section, adding comments, and condensing everything while maintaining the original function of the website. 

# User Story

After following the parameters provided this site slightly changed, as the title on the tab in the browser is different and the footer has an added space at the bottom of the page. Besides these changes the web-page still looks as it originally did before. The links now all work and direct me below to help everyone easily find the relevant information about Horiseon!

# Code Refactoring

## Example of Code Cleanup:

- As you can see in this example below, I changed the title to be more specific and organized the header section by minimizing the "div" tags and removing both the "ul" and "li" tags. Also removed the unnecessary classes and added appropriate comments. I made these changes by applying HTML Semantics and following web accessibility, while making sure the links continued to work.

![Code Refactor Example 1](https://user-images.githubusercontent.com/73864182/102705773-f83c3400-423f-11eb-87bd-af100966f2ac.png)

## Horiseon Web-page Before/After:

- When I was finished applying these methods to the entire document (html & css) I was able to maintain the overwhelming majority of elements on this web-page. Besides #1 (the changed title) and #2 (the space added on the footer), nothing else seems to have changed.

![Code Refactor Example 2](https://user-images.githubusercontent.com/73864182/102705858-d5f6e600-4240-11eb-9da9-0053bf2b562a.png)

## Final Result after Code-Refactor:

## Horiseon Web-page

![Code Refactor Final Image](https://user-images.githubusercontent.com/73864182/102705872-0f2f5600-4241-11eb-8a42-cbdc105d2ac9.png)

*Below is a walkthrough of all changes made*


# Changes made to code (html/css):

*ADDED COMMENTS THROUGHOUT CODE AS CHANGES WERE MADE*

## FIXED HEAD:

- Added Company Name to the title tag ("website" to "Horiseon")


## FIXED HEADER:

### HTML:

- Changed parent "div" tags to "header"
- Removed "div class="header""
- Properly indented/spaced out this part of code
- Changed other "div" tags to "nav," to specify links below
- Removed the "ul" tags (unordered list) and "li" tags (list) to cleean up section
- Changed "class="seo"" to "id="seo"" to be more specific

*Double checked links, "Search Engine Optimization" doesn't work*

### CSS:

- Consolidated ".header" styles all under "header" selector
- Seperated the "h1" and "#seo" id selectors
- Put all CSS for the header links under "nav" selector
- Checked links, the text isn't seperated anymore
- Added "padding-left: 25px" under "a" selector to fix spacing between links


## FIXED MAIN IMAGE:

### HTML:

- Changed "div" tags for Main Image under header to "main" tags
- Removed "div class="hero""

### CSS:

- Changed ".hero" class to "main" selector to fix CSS for Main Image


## FIXED SECTION/ARTICLE:

### HTML:

- Changed parent element "div" to "section"
- Changed child element "div" to "article" for all 3 below
- Properly indent/space entire section/article
- Removed "class="content"" and changed it to just section tag
- Removed "search-engine-optimization," "online-reputation-management," and "social-media-marketing" class tags
- Added "id="search-engine-optimization" to fix 1st link in header
- Added "alt" tag to each image in section

### CSS

- Changed ".content" class to "section" selector
- Moved all "benefit" CSS below to fix order of page
- Grouped all "search-engine-optimization," "online-reputation-management," and "social-media-marketing" CSS together
- Changed all ".h2" class to "h2" selector
- Changed all "search-engine-optimization," "online-reputation-management," and "social-media-marketing" classes to just ids

## FIXED SECTION/ASIDE:

### HTML

- Changed parent element "div" to "section"
- Changed child element "div" to "aside"
- Changed "class=benefits"" to "id=benefits"
- Removed classes for "search-engine-optimization," "online-reputation-management," and "social-media-marketing" 
- Added "alt" tag to each image in section

### CSS

- Changed ".benefits" class to "#benefits" id
- Condensed all ".benefit-lead/brand/cost" classes under "aside" 
- Condensed all ".benefit-lead/brand/cost h3" heading under "h3" and moved to top of code
- Condensed all ".benefit-img lead/brand/cost img" images under "aside img"
- Properly indent/space/organized entire section/aside

## FIXED FOOTER:

### HTML

- Removed "class=footer"
- Properly indent/space footer

### CSS

- Removed ".footer" and ".footer h2" classes
- Changed these classes to "footer" and "h2"

## FINAL CHANGES:

- Went back over entire code (html & css) and organized the order of each section and properly indented and spaced everything.

- Revised and added comments to better identify and explain each section.

# Overall Conclusion

 The Code Refactoring assignment taught me how to better organize my code as well as understand every aspect of this web-page and control all of it's functions. 
 
 I feel far more confident when confronted with a wall of html/css than I did just two weeks ago. And I am defintiely more capable of navigating and writing code. 
 
 It also provided great practice at using GitBash to upload everything to my GitHub account and write an informative README file. Overall this project was challenging as well as fun!