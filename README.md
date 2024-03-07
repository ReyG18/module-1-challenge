# Code Refactoring Challenge - [Horiseon Website](https://reyg18.github.io/module-1-challenge/) - Module 1

## Description

For the module 1 challenge, the objective was to refactor a website in order to 
improve accessibility. Various changes have been made to the html file that will
improve the efficiency of the browsers' assistive technologies.

## Changes

**Changes to HTML**

-   The original code was div soup. In order to improve accessibility, all div tags
    were changed into more suitable semantic html tags. As a result, changes were
    also made in the CSS file. (see comments)
-   '.hero' class name was unclear and changed to ."background-image" for clarity.
-   The main content was separated into their own sections to improve code organization
-   Fixed a broken link.
-   Added alt text to all images (except the background image).
-   Changed footer 'h2' to 'h4'.

**Changes to CSS**

-   Fixed an error where calibri in the font families was not 'calibri'.
-   Updated certain class selectors as a result of class names being changed in the html.
-   Consolidated the selectors 'header nav' and 'nav ul'.
-   Consolidated the class selectors '.benefit-lead', '.benefit-brand'. and '.benefit-cost'
    as well as their h3 and img selectors.
-   Consolidated the selectors for '.search-engine-optimization', 'online-reputation-management',
    and '.social-media-marketing' as well as their h3 and img selectors.

## Challenges

I was unable to figure out how to add alt text to the '.background-image' class without breaking it.
Either the image did not load and showed only the alt text, or both the alt text and image would display
simultaneously.
