# USLS-test

Published page: [https://bonnieho.github.io/USLS-test/](https://bonnieho.github.io/USLS-test/)

## Introduction

This mini-project was presented as an opportunity to showcase my ability to take the content of a static image and render an identical version using only cascading styles (CSS). Needless to say, since making translations such as these are something I thoroughly enjoy doing, this was a challenge I embraced with great enthusiasm.

This is the image I was tasked with replicating:

![image of the test graphic](images/html-css-test.png)

- - - 

### The Process

My approach was to first mentally deconstruct the image as if were already a web page or modal and record the characteristics (color, size, spacing, font) of the different 'elements' in the image. Once those basic properties were recorded, I set out to determine the specific font family that the text should resemble most closely. After several hours of exhaustive online research, I found the perfect match in a licensed font family called 'Rooney Sans'. Unfortunately, since this is comercially licensed typeface, the fallback was to find something that matched as closely as possible in the publically available Google Font collection. An added advantage to using this system is that the font's characters will load within the cache of the end-user as the page itself loads, mitigating the need for the typeface to be installed on that visitor's device itself.

Once a font was settled on, the elements were created within a basic, standards-compliant, html document. One of the approaches (with responsiveness in mind) was that the styles were created using a base font size in pixels and relative sizing wherever possible. Breakpoints were incorporated into the styles to structurally allow the page elements to adapt to different devices' viewport dimensions and maintain function and readibility. For better efficiency with edits and overall comprehension, ids and classes were named intuitively based on their function. Lastly, accessibility was taken into consideration with the inclusion of some semantic, organizational structure (an added h1) despite the fact that the content has not been seemingly laid out with that in mind.

As an added feature, I've included considerable, relevant meta data and OpenGraph meta elements in Rich Link Preview assets towards SEO improvement.

- - - 

#### What I would still like to do (MVPs):

* ~~finish :hover and :active states for all divs with button functionality;~~  [DONE!]

* experiment with 'containerizing' the popover so that I do not have to turn off the visibliity of the arrow when the viewport windows decreases (it's currently detaching at lower screen sizes because of the large viewport's absolute placement);

* create a modal (dialog pop-up) for activation of the 'Why give $50?' link (explaining the importance of donating $50);

* create a modal (dialog pop-up) for all buttons as a response to activation;

* ~~create a tooltip on :hover for the progress bar that displays the dollar amount of contributions to date;~~  [DONE!]


- - -


(c)2019 __Bonnie Lynne Hoffman__ 

*towards consideration for a front-end development position*
