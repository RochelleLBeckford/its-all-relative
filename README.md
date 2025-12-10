<img src="img/icons/cover-cherry-blossom-alleyway.png" width="100%" height="400">

# 🌸 Its All Relative 🌸

## Practice: Creating a Webpage building upon HTML basics and understanding how to use CSS Basics

### Understanding selectors and properties to bring styling with colors, fonts, sizing, layouts, and much more...

<hr>

### Practice Understanding CSS -> Setting an Elements Position

<hr>

##

## 💫 Overview:
-   [ ] This is a CSS tutorial website that teaches the user how to move and layer elements on a webpage in two parts. Part one, explains how to move elements from their normal position and how to control element layering or overlap through code examples of the before and after effects along with pictures of this concept. Part two, applies these concepts through a mock tutoring company website.

<hr>

## 🎨 Key Design Features:
-   [ ] <b> Cherry Blossom theme for the color scheme across both pages </b>
-   [ ] <b> Visual Dividers </b> between sections
-   [ ] <b> Flexbox layout </b> for header | footer alignment
-   [ ] <b> Interactive elements </b> (expandable notification, contact form)
-   [ ] <b> Consistent styling </b> across both pages through a single CSS file (style.css)

<hr>

-   [ ] Simple practice to gain a better understanding of the power of adding CSS Styling to a webpage and how it can make it uniquely beautiful
    -   [ ] CSS or Cascading Style Sheet, is a language that paints a website with colors, fonts, layouts, and animations.
    -   [ ] CSS is used to create stunning webpages.
    -   [ ] It can enhance the user experience, and can make a webpage unquie and stand out amongst the rest.
    -   [ ] It is absolutely beautiful to see a webpage come to life and become even more beautiful.

<hr>

-   [ ] CSS - Setting Elements:
    -   [ ] "relative" position:
        -   [ ] This allows your elements to be "moved" around the screen, away from where it would normally be on the screen
        -   [ ] Seeting an element's "position" property to anything but "static", it can be moved with "top", "right", "bottom", and "left" properties. This includes "relative".
            -   [ ] "top" -> moves an element down the screen
            -   [ ] "right" -> moves an element to the left
            -   [ ] "left" -> moves an element to the right
            -   [ ] "bottom" -> moves an element up the screen
        -   [ ] For instance, this is the syntax for static elements:
            ``` css
            div {
                width: 200px;
                height: 200px;
            }

            #div-a {
                background-color: red;
            }

            #div-b {
                background-color: blue;
            }
            ```
        -   [ ] To break #div-b out of the normal flow by changing its position to relative, and then move it from the "left" and "top: sides by 25px:
            ``` css
            #div-b {
                backfround-color: blue;
                position: relative;
                left: 25px;
                top: 25px;
            }
            ```
        -   [ ] The rendered relative elements: <img src="img/main/rendered-relative-syntax.png" alt="Rendered Syntax of Relative Elements">
        -   [ ] The "top" and "left" properties can also be set with relative units: <img src="img/main/rendered-relative-syntax-with-top-and-left-properties.png" alt="Syntax of Relative Elements with top and left properties">

    -   [ ] "z-index" property:
        -   [ ] This changes the way elements are "layered" on the webpage, regardless of when they appear on the HTML file.
        -   [ ] For instance, the following syntax is for two static &lt;div&gt; elements along with "z-index":
            ``` css
            div {
                width: 200px;
                height: 200px;
            }

            #div-a {
                background-color: red;
            }

            #div-b {
                background-color: blue;
                position: relative;
                left: 25px;
                bottom: 25px;
                z-index: -1;
            }

            #div-c {
                background-color: lightgreen;
            }
            ```

        -   [ ] This will render relative elements with the "z-index" properties:
        <img src="img/main/rendered-elements-with-z-index.png" alt="Rendered Relative Elements layered differently using z-index">

<hr>

## &lt;/&gt; Semantic Outline of the webpage:

-   [ ] The &lt;header&gt; element:
    -   [ ] Is used for the beginning of the webpage
    -   [ ] Houses the title of the webpage along with Logos
    -   [ ] The &lt;figure&gt; element:
        -   [ ] Usually holds an image, illustration, diagram, code snippets, etc...
        -   [ ] It can also hold more than one
    -   [ ] The &lt;img&gt; element:
        -   [ ] Is used for all the images on the webpage

-   [ ] The &lt;nav&gt; element:
    -   [ ] This element tends to contain ordered lists, unordered lists, or even both types of lists
    -   [ ] Each &lt;li&gt; element will house an &lt;a&gt; elements with the #id-name of the desired section or part of the webpage it will be linked within the "href" attribute
        -   [ ] For instance:
            -   [ ] &lt;a href="#desired-section"&gt;🌸 Desired Section🌸&lt;/a&gt;
            -   [ ] <a href="#desired-section">🌸 Desired Section 🌸</a>
                -   [ ] When the user would click the 🌸 Desired Section 🌸 link they would then be navigated to that section of the webpage

-   [ ] The &lt;br&gt; element:
    -   [ ] Creates a new line in your code and forces whatever comes after to start on a new lin

-   [ ] The &lt;hr&gt; element:
    -   [ ] Adds a horizontal line or dividing line across the webpage
    -   [ ] Used to separate sections or different topics on a webpage

-   [ ] The &lt;main&gt; element:
    -   [ ] Is where the main information of the webpage will go
    -   [ ] The &lt;section&gt; element:
        -   [ ] This groups together pieces of similar information
    -   [ ] The &lt;article&gt; element:
        -   [ ] This will house a singular piece of information describing what this section is about in great detail

-   [ ]  The &lt;footer&gt; element:
    -   [ ]  This element tends to finish off the webpage as it is located at the very bottom of the webpage and is the last set of items that will be seen
    -   [ ] For instance:
        -   [ ] A footnote on the webpage
        -   [ ] Links to different sections of the webpage
        -   [ ] A copyright symbol for copyright information
            -   [ ] & copy; -> is the symbol for copyright
        -   [ ] A link to external sources using the "href" attribute of the &lt;a&gt; element for the links in the list item to external sources
            -   [ ] &lt;a href="/privacy"&gt;Privacy&lt;/a&gt;
                -   [ ] Use the target attribute to open the link path in a new tab instead of the current page
                -   [ ] <a href="/privacy" target="_blank">Privacy</a>
                -   [ ] When the user clicks one of these external links, they would be redirected to a new page with the informat ion

<hr>

## ✨ Encompassed Technologies:
-   [ ] HTML:
    -   [ ] Will be the structure and skeleton of how the app will appear on the webpageWill be the structure and skeleton of how the app will appear on the webpage
-   [ ] CSS:
    -   [ ] Encompass the style of the app and give it some flair

<hr>

## 🌐 Live Demo
-   [ ] Visit the Live Website:
    -   [ ] <a href="https://rlb-its-all-relative.netlify.app" target="_blank">rlb-its-all-relative</a>

