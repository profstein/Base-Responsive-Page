# Base-Responsive-Page
This page is intended to demonstrate a basic responsive web page. While it can work on a production site, it is not aimed at production-ready sites but for use in teaching responsive web design.

## Description of Files

* **css/base.css:** This has comprehensiv base styling for a site including:
    * **CSS Variables (Custom Properties)** for controlling Typography, Color and Spacing. These variables are used throughout the stylesheet and changing the values of them is one of the first things you can do to make this your own.
    * **Minimal Normalize**: this helps to make the site look the same across browsers. 
    * **Basic Type and Button styles**: this gives base styling to the most common text and interactive (links, buttons) elements
    * **Basic Responsive Media** styles for img, video, svg elements as well as to make embedded video responsive.
* **css/style.css** This is empty. You can put your site specific styles here. See demo-style.css for an example of what might go in it.
* **index.html:** This is a blank page but it includes the two .css files listed above, jquery, and the basic structure almost all pages have:
    * meta information in the head
    * Skip link to main content
    * Three main page sections: header | main | footer
* **css/demo-style.css** a demo of the kind of site-specific css you might add to style.css. You can see the results in demo.html
* **demo.html**: demo content to show how base.css and demo-style.css look in action.
* **js/main.js**: empty JavaScript file. You can write your custom JS code here.
* **js/vendor/jquery** This is a local version ofjqeury in case the CDN version doesn't load.

## Projects Used
This page inlcudes files from a number of other projects:

1. jQuery: https://jquery.com/
4. HTML5 Boilerplate: https://html5boilerplate.com/


In general it owes a inflential debt to HTML 5 Boilerplate. It is in some ways a simplified version that is less daunting to use directly from GitHub.

Generative AI was used to confirm the current use and acceptance of some of the CSS and HTML choices.

