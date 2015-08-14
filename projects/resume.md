---
layout: default
title: Resume Layout Project
permalink: /projects/resume/
---

For this assignment you will create 3 unique resume layouts using the following: 

- [Bootstrap](http://getbootstrap.com)
- [Google Fonts](http://google.com/fonts)
- [Font Awesome](http://fontawesome.github.io) <small>(Optionally)</small>

We will be creating these layouts in [CodePen](http://codepen.io).

The layouts can be anything you like so long as they are different, but as jumping off points I'd recommend exploring the following options:

- A layout of rows alternating between 1 column (full-width) and 2 columns down the page, collpasing to 1 column on the smallest screen sizes.
- A two column layout with one smaller column serving as the "header" — your name, contact info, etc — and the rest of the resume sections existing in larger, right-hand column. On mobile these would collapse so that each section could occupy the the full-width of the screen.
- A layout that goes 1 column, 2 columns, 3 columns, 4 columns and then 1 column once more for the footer. On smaller screens reduce the 4-column sections to 2 columns across.

Ultimately I'd like to see creative combinations of columns and with some thought applied to how the layout might shift when viewed on smaller (mobile) screens.

For each layout you create following these steps:

### Step 1: Fork a copy of the starter template

Make sure you are logged into CodePen and go to the following page:

[http://codepen.io/mandis/pen/waZObG](http://codepen.io/mandis/pen/waZObG)

The content for your HTML, CSS and JavaScript will be empty, but the template will already have Bootstrap (and [Normalize.css](https://necolas.github.io/normalize.css/)) loaded for you.

Click the <strong>Fork</strong> button at the top of the page.

![Fork button](/images/resume-step-1-fork-button.png)

This will create a copy of the project and save it to *your* CodePen account. From here you can click on the **Settings** button and change the name of the project to something else.
![Rename project](/images/resumse-step-1-rename.png)

Make sure you do this for each of the 3 templates you'll be creating.

### Step 2: Choose some fonts for your project

The next step will be to choose some fonts for your template. You can choose as many as you like and use them however you wish, but be sure to choose at least 2 — one for the headlines and one for the main body text.

We'll be using Google Fonts for this. Go to:

[http://google.com/fonts](http://google.com/fonts)

When you've found a font you like click on the **Add to Collection** button that appears to the right.

![Add font to collect](/images/step-2-add-to-collection.png)

### Step 3: Include the font in your project

When you are done selecting fonts for your layout and have addedt them all to a collection click on the **Use** button that appears in the gray footer area near the bottom of the page.

![Use fonts in project](/images/step-3-use-in-project.png)

On the page that appears you should find options to check the different weights you'll like to use for your project. Select the weights you'll want ot include and scroll further down the page to the section where it says *Add this code to your website.*

![Use font code](/images/step-3-use-font-code.png)

Copy and paste the entire <code>&lt;link /&gt;</code> code snippet and then go back to your project in CodePen. Click the **Settings** button at the top of the page and select the HTML tab from the overlay that appears. In the space labeled *Stuff for &lt;head&gt;* past the snippet you copied.

![Past code in HEAD](/images/step-3-paste-copied-code.png)

We've now included your custom fonts! Be sure to refer back to the Google Fonts page where we created our collection to the section labeled *Integrate the fonts into your CSS* for instructions on how to use your newly acquired fonts in the CSS. It should look something like the screenshot below.

![Using the font in your CSS](/images/step-3-font-css.png)


### Step 4: Include Font Awesome in your project

Including Font Awesome is somewhat similar. We'll use the CDN version of Font Awesome so go ahead and copy this:

    <link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
    
And paste it into the *Stuff for &lt;head&gt;* field just as before, beneath the code you already pasted there for your fonts.

Your project is now ready to use Font Awesome icons! To search what icons are available to you and learn their class names you can use their website:

[http://fontawesome.github.io/Font-Awesome/icons/](http://fontawesome.github.io/Font-Awesome/icons/)


### Step 5: Create your layout!

You're ready to go! Be sure to refer to the [Bootstrap documentation](http://getbootstrap.com/css/) as you're going along — especially the CSS section that explains how the grid systems work!




