### Media Queries 

What are they? 

They are tool in CSS(and sometimes html) that allow a website to look good no matter the size of the screen(viewport) that it is being view on.


What are they used for? 

They are used to give a new set of styling information to follow based on the size of the viewport. You start out with one set of styles, either starting with the smallest (usually mobile screen) or the largest (usually desktop screen). The 3 main viewports are desktop, tablet, and mobile. For a website to be able to scene on majority of devices it will usually have at least 3 breakpoints. A breakpoint is when the style of the page changes from one viewport to the new one. 

You will want to set up your media queries up based on the initial viewport you style. When you reach a breakpoint it will read the media query that is applicable. Any styles in the applicable media query will override your initial set of styles. ORDER MATTERS!!!! If you have 2 breakpoints that are activated with a max-width of 55em and max-width of 30em, you will need to have the media query with the max-width of 55em above the other. If you do it the other way it will always activate the max-width of 30em for both breakpoints. So instead of having 3 varying viewports you will only have 2.


* Example: Say the default background color is blue...

```CSS
@media screen and (max-width: 55em){
body {
background-color: red;
}
}

```
In the above example, when the screen reaches a max width of 55em (or less) the background color will change from blue to red. This example is going from a desktop default and the breakpoints activate as the screen gets smaller. If you started with a mobile viewport and worked your way up you would use min width instead of max width.
