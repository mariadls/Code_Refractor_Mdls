# Code_Refractor_Mdls

## Project Description
Refractor an existing page to make it more accessible. 

## Contents

1. Deployed Page 
2. Modifications Made to Provided Code 
3. Contributions

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
## Final Page
![Final Page Screenshot](https://github.com/mariadls/Code_Refractor_Mdls/blob/main/assets/images/Final_Page_Screenshot.png?raw=true)

The project is hosted in GitHub at the following repository: https://github.com/mariadls/Code_Refractor_Mdls.git

You can find the Deployed Page here: https://mariadls.github.io/Code_Refractor_Mdls/

## References 
[HTML Accessibility](https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML")
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet')
