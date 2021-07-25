## CSS
![CSS](https://miro.medium.com/max/1400/0*0Jt6AoXxmN0n0qhN)

### What is CSS?

CSS stands for Cascading Style Sheets with an emphasis placed on “Style.”
While HTML is used to structure a web document (defining things like headlines and paragraphs, 
and allowing you to embed images, video, and other media), CSS comes through and specifies your document’s style—page layouts
, colors, and fonts are all determined with CSS. Think of HTML as the foundation (every house has one),
and CSS as the aesthetic choices (there’s a big difference between a Victorian mansion and a mid-century modern home).

### How does CSS actually work?
When a browser displays a document, it must combine the document's content with its style information. 
It processes the document in a number of stages, which we've listed below. 
Bear in mind that this is a very simplified version of what happens when a browser loads a webpage,
and that different browsers will handle the process in different ways. But this is roughly what happens.

![CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_works/rendering.svg)

### CSS Syntax
#### Style of CSS
/* Create your test CSS here */

p {
  color: red;
}
#### Selectors


h1
a:link
.manythings
#onething
*
.box p
.box p:first-child
h1, h2, .intro

#### Specificity

.special {
  color: red;
}

p {
  color: blue;
}

<p class="special">What color am I?</p>

####  cascade and specificity.

p {
  color: red;
}

p {
  color: blue;
}


![CSS](https://www.w3schools.com/css/img_selector.gif)
