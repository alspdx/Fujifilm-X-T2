# Fujifilm XT-2 Product Page

#### Product information page for the new Fujifilm camera, the X-T2, _2017_

#### by **Adam Smith**

## Description

| Term | Description | Implementation |
| -- |:--:| --|
| border-box | This property tells the browser that the width and height settings of an element are measured to the element border outer edge. | I used a box-sizing reset to give all elements the border-box property so that when width and height are set in CSS, adding a border does not add to the height and width that the element's box will occupy. |
| float | This property removes the element from the normal flow of it's containing element, moving the element as far as it can go in the direction specified by the values "left", "right", "none", or "inherit". | Float was used to push the upper image left and the table right for the layout. Additionally it was used in the image gallery at the bottom of the page to keep the left images anchored left and push the right images to the end of the div. |
| display: block | This property makes an element display like a block element making it start on a new line and occupy the whole width the parent element whether or not it is as wide. The element will also respect top and vertical margins.| In this web page I used "display: block" to style the paragraph introduction text in the product description. |
| display: inline | This property tells the browser to treat the element like an inline element. The element will display on the same line next to other elements and no longer break the flow of the web page. | I changed the display properties to inline for the the divs containing the main product image, the table with product specifications, and images in the image gallery at the bottom of the page to display them in rows with other divs. |
| centered content | Centered content is any sort of content or element that has been centered vertically or horizontally inside of it's parent container for a cleaner visual layout. | I used a combination of absolute positioning, text-aligning, padding and margins to center content throughout the website. |
| pseudo-element | Pseudo elements are keywords added to CSS selectors to target specific parts of the HTML element | I applied the pseudo element ":after" to the main image's parent div to add the text "Available Now" in front of the image. |
| clear-fix | Clear fix is a technique used by developers when the parent container of floated elements collapses to make the end of the container clear it's elements. | I made a class selector with a common clear-fix styling in CSS and applied it on every container I floated elements inside of to make sure they did not collapse. |
| positional selector | Positional selectors target elements at particular positions on the page by calling their location inside of or next to other elements. | I used positional selectors to target many elements inside of other elements and to target particular elements such as first-children, nth-children, and last-children.  I also used ":first-letter:" to target the first letter of the paragraph introduction text span in the product description to color it red.|
| selector combinator | Selector combinators are used to describe relationships between CSS selectors to target descendants, children, general siblings, or adjacent siblings of a particular element. | Selector combinators are used all throughout my CSS page to target descendants and direct children of elements. |


## Setup

Visit the webpage [here](https://alspdx.github.io/Fujifilm-X-T2).

Alternately you may [Clone this repository](https://github.com/alspdx/Fujifilm-X-T2).
  1. Click on the link above.
  2. Click the green button marked **Clone or download**.
  3. Click **Download ZIP**.
  4. Unzip file.
  5. Open index.html in Chrome or another web browser.

## License

Copyright (c) 2017, Adam Smith

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
