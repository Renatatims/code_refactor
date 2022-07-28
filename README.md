# Code Refactor Project
Code refactoring - web accessibility and codebase improvement

## Description 
This repository contains a project to improve accessibility standards from a website.

## Objectives
1. Modify the actual coding in order to become more acessible when using assistive technologies.
2. To follow a logical structure and cleaner appearance

## In order to do this, it was applied the following:

1. Title element was previously generic and it was changed to a descriptive title, under the company's name. 

2. A favicon was added to assist with browser tab navigation.

![Screenshot](assets/screenshots/capture1.PNG) "favicon")

3. Included "viewport" in the head-section, to enable the page to follow screen-width of the device being used.

````html
<meta name="viewport" content="width=device-width, initial-scale=1.0"> 

````



2. <title>Horiseon Social Solution Services </title> <!--Changed title, from "website" to "Horiseon Social Solution Services"-->

3. <!--Added a favicon-->

4.<!--switched "div" to "header" -->

5.  <nav class="navigation"> Navigation: <!--changed "div" to "nav" and added a class name to nav, so it can be easily found-->

6.<section class="content">  <!--changed "div" to "section"-->

7. <article class="article"><!--changed "div" to "article"--> <!--changed class name to "article"-->

8.<aside class="benefits"> <!--changed "div" to "aside"-->

9.  <!--Footer-->
    <footer class="footer"> 


CSS

10. /*body - added "a" and "p" which are general attributes in the body section*/

11. /*Top-Navigation - class name added: "navigation"*/

12./*Articles - "Search Engine Optimization", "Online Reputation Management", "Social Media Marketing" 
since all these articles have the same properties, a class="article" was created so there is less repetition in the CSS file.*/

13. /*Div - "Lead Generation", "Brand Awareness", "Cost Management" all 3 under the same class="benefits-content", 
since they have the same properties*/

14. /*@media - included @media so the website gets resized correctly on smaller screens*/

15. /*position:relative on header*/

16. /*position:relative on navigation - float changed to none in smaller screens*/

17./*navigation ul li - display changed to block and position to relative in a smaller screen*/

18. /*width 100% - in a smaller screen the position of content will adjust*/

19. 
.article img {
        max-height: 180px;
        position: relative;
        
    }

/*fixed the images when resizing the screen*/

20. /*added margin so the benefits content is visualy organized*/

21. /*added @media screen for 576px - so content adjusts properly on cellphones*/

22. Alt elements

23. Link reference to the Home page from the logo
