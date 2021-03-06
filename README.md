# Code_Refractor_Mdls

## Contents
1. Project Description
2. User Story and Acceptance Criteria 
3. Modifications to Provided Code
4. Outputs 
5. References
6. Contributions

## Project Description
Refractor an existing page to make it more accessible. 

![Final Page Screenshot](https://github.com/mariadls/Code_Refractor_Mdls/blob/main/assets/images/Final_Page_Screenshot.png?raw=true)

# User Story and Acceptance Criteria  
## User Story
As a marketing agency
I want a codebase that follows accessibility standards
So that our own site is optimized for search engines

## Acceptance Criteria
* GIVEN a webpage meets accessibility standards

* WHEN I view the source code

* THEN I find semantic HTML elements

* WHEN I view the structure of the HTML elements

* THEN I find that the elements follow a logical structure independent of styling and positioning

* WHEN I view the image elements

* THEN I find accessible alt attributes

* WHEN I view the heading attributes

* THEN they fall in sequential order

* WHEN I view the title element

* THEN I find a concise, descriptive title

# Modifications to HTMl and CSS files 

## Modifications to HTML file 

```
Desctiptive Comments were added 
<!--Start Navigation/Header-->
<!--End Navigation-->	 
<!-- Hero -->
<!--Hero End-->	 
<!--Main Content-->
<!--End Main Content-->	 
<!--Benefits Section Start-->
<!--Benefits Section End-->	  
<!--Footer Start-->
<!--Footer End-->

Changed title to "Horiseon"
Changed <div> to <header> tag
Changed <div> for <nav> tag
Changed <div> class for <content> tag 

Added empty lines to make HTML easier to read

Changed <div id> to <section id>
Deleted image div classes in <div id> tags
Changed <div id> to <section id> in the Benefits section 
Added desicprive alt propertives to all the images 
Removed </img> tag

Changed <div> class in footer to <footer> tag
```

## Modifications to CSS File
```
Descriptive comments were added to the css file 
/* General Styles */
/* ==========================	 
  
Header and Navigation Styles	 
  
============================= */
/* Header Style Start */
/* Header Style End */	   
/* Main Content Styles Without Benefits */
/* Main Content Styles End */	 
/* ------- Additional content ------- */
/* Footer Style Start */
/* Footer Stye End */

Did not find that any CSS rules could be deleted, only modified. 
Deleted . for classes 
Added # for elements with id attributes 
Changed <header div> for <header nav> and associated <div> tags in the <header> tag

Merged benefit tags to simplify CSS file, example: 
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
 merged to: 
#benefit-lead,
#benefit-brand,
#benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

```
# Outputs

The project is hosted in GitHub at the following repository: https://github.com/mariadls/Code_Refractor_Mdls.git

You can find the Deployed Page here: https://mariadls.github.io/Code_Refractor_Mdls/

# References 
[HTML Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML")

[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet')

# Contributors 
Made following guidelines from MSU Coding Bootcamp Challenge One: Code Refractor Guidlines

Made by Maria De Los Santos
