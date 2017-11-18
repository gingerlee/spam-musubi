# _Spam Musubi Styling_

#### _Aa single page application that showcases one product: Spam Musubi, November 17, 2017_

#### By _**Ginger Lee Kretschmer**_

## Description

_This page showcases Spam Musubi, including a recipe, a photo gallery and large image. It uses an array of CSS concepts such as border box, floats, pseudo classes and elements._

## Setup/Installation Requirements

* _Please download copy this link into the browser of your choice.


## Support and contact details

_Questions? Contact Ginger at kretschmons@gmail.com_

## Technologies Used

_HTML and CSS_

## CSS Elements Used

| Element   |      Description      |  Use in Application |
|----------|:-------------:|------:|
| Border-Box |  Border-box effectively changes the way dimensions are measured for every element so it includes borders and padding. | I've applied border-box to all elements in the body of my html. |
| Float | The float property specifies how an element should float.  |   I've used the float property in the header as well as in the three columns in the content section of the site. |
| Display: Block | Block elements are HTML elements that when displayed start on a line of their own, in effect making a block on the page. |  I've used block elements throughout the layout, for example the bottom banner and footer items stack on top of each other as block elements should.  |
| Display: Inline | Inline elements do not appear on their own line, but share a line with other elements. |  I've used inline elements in the un-ordered list that makes up the navigation bar in the top right of the site. |
| Center Content | Centering content through CSS can be accomplished in many different ways, for example text can be centered using the 'text-align:center' declaration | I've centered content using the text-align:center, margin: 0 auto, background: url(../img/main-spam.png) center no-repeat;, etc. |
| Pseudo-Element | Pseudo-Elements are added to selectors and are treated as virtual elements of their own that we can style like regular HTML elements. |    I've used the '::after pseudo-element to add red text to one of the list items in the recipe ingredients list.' |
| Pseudo-Class | Pseudo classes allow one to style elements in certain states. |    I've used the :hover pseudo-class on the navigation and the recipe list item.  |
| Clear-fix |  Elements after a floating element will flow around it. One can use the "clearfix" hack to fix the problem. |   I've used this on the main content section of the site, since the header uses floats the content was collapsing wihtou a clearfix. |
| Positional Selector | These are used to specify particular elements in the flow of the document. |  I've used the nth-child in the Fun Facts column to color every other list item. |
| Selector Combinator | This is a way to target specific elements in one CSS rule | I've used this many times on this site, for example in my recipe column, I used '.recipe-column ul li:nth-last-child(2):hover' which is a rule I've made to target just the 2nd to last list item in the un-ordered list (there is an ordered list below)|

### License

Copyright (c) 2017 **_Ginger Lee Kretschmer_**
