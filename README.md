
<div align="center">

![license](https://img.shields.io/github/license/mohmorsi/Space-Byte?style=flat-square)
![html logo](https://img.shields.io/badge/HTML-C75333?style=flat-square&logo=html5&logoColor=white)
![css logo](https://img.shields.io/badge/CSS-3079E9?style=flat-square&logo=css3&logoColor=white)
![javascript logo](https://img.shields.io/badge/JS-ECD74E?style=flat-square&logo=javascript&logoColor=white)
![made with heart by mohmorsi](https://img.shields.io/badge/made%20with%20%E2%9D%A4%EF%B8%8F%20by-mohmorsi-red?style=flat-square)
</div>

# FunkyButtons

## Overview
This code defines CSS styles for a container with centered flex items, including cancel and submit buttons with cool animations for hover and focus states.

## HTML Structure
This code assumes the existence of a container element with the class "container", inside which there are one or more button elements with the class "btn". There may be additional classes applied to some of the buttons, such as "btn-cancel" or "btn-submit".

## CSS Styles
• `html, body`: sets the margin and padding of the entire page to 0.

• `body`: sets the background color to a dark gray.

• `.container`: sets the container element to use flexbox, and center its children horizontally and vertically. The height is set to 100% of the viewport height.

• `.btn`: sets the basic styles for all buttons, including font family, minimum and maximum widths, margin, padding, border radius, border width, background color, text color, font size, and letter spacing.

• `.btn:focus`, `.btn:hover`: sets styles for the button when it is being hovered or focused, including a background color change and a cursor change.

• `.btn:active`: sets a scaling transformation for the button when it is being clicked.

• `.btn-cancel`: sets specific styles for a button with the "btn-cancel" class, including color and border color changes.

• `.btn-cancel`: focus, .btn-cancel:hover: sets an animation for the button when it is being hovered or focused, sliding it to the left using a keyframes rule.

• `@keyframes left-slide`: specifies the animation for the "left-slide" animation, which moves the box-shadow of the button to the left and changes the text color.

• `.btn-submit`: sets specific styles for a button with the "btn-submit" class, including color and border color changes.

• `.btn-submit:focus`, `.btn-submit:hover`: sets an animation for the button when it is being hovered or focused, pulsing its box-shadow using a keyframes rule.

• `@keyframes pulse`: specifies the animation for the "pulse" animation, which changes the box-shadow of the button and its text color.

## Demo



https://user-images.githubusercontent.com/8793750/224219723-56262657-4f1d-4aa0-af13-eadee529fc5f.mov



## Usage
To use this code, create an HTML file that includes a container element with one or more button elements inside. Apply the appropriate classes to the buttons to achieve the desired style. Then link to this CSS file in the head of your HTML document.
