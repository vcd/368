# Module 5: Putting It Together

## Overview: Atomic Design Process 

## Atomic Design Components
Actually _Atomic Design_ process used on large scale website, but the ideas are applicable. Let’s redefine as: 

* Large: Largest, Base/Sitewide Styling
* Medium: Medium: Medium-sized Modules, made up of smaller-Components
* Small: Individual Components, specific parts
* Media Queries: At this size, do this. 

### Setup Files

> [CodePen Project Web 1 Final Website][1]

* Create necessary pages
* HTML body classes
* CSS Table of Contents
* Normalize CSS
* As always, CSS: 
	* Cascade
	* Inheritance
	* Specificity
	* Box Model
	* `display` types
	* Responsive Web Design
	* Art Direction

### Main Navigation 
* Reusable, sitewide, Module
* Use `positioning` to fixed navigation
* :black_nib: [https://codepen.io/manikoth/pen/QWWzodR][2]

### Footer
* Another, reusable, sitewide, Module
* :black_nib: Footer [Footer Navigation][3]

### Bio
* :black_nib: [Bio][4]
* Reference: [CSS Tricks Shape Outside][5]

### Contact Form
* :black_nib: [Contact Form][6]
* Reference [FormSpree.io][7]

### FlexBox for Content Alignment
* FlexBox is one-dimensional layout
* :black_nib: [Portfolio Content with FlexBox][8]

### CSS Grid for Layout 
* :black_nib: [CSS Grid for Layout][9]
* Use `fr` unit when possible
	* No arithmetic
	* No overflow issues with Box Model
* Reference
	* [fr vs %][10]

### Lightbox
* Ex 1: [Pure CSS, no JS Lightbox][11]
* Ex 2: [CSS Lightbox with reflection][12]
* Pros: No JS need. Fast to load. 
* Cons: Manually count images.   

[1]:	https://codepen.io/manikoth/project/editor/DWpjRK
[2]:	https://codepen.io/manikoth/pen/QWWzodR
[3]:	https://codepen.io/manikoth/pen/oNNJOeJ?editors=1100
[4]:	https://codepen.io/manikoth/pen/oNNJOMO?editors=1100
[5]:	https://css-tricks.com/almanac/properties/s/shape-outside/
[6]:	https://codepen.io/manikoth/pen/jOOXdgd
[7]:	https://formspree.io/
[8]:	https://codepen.io/manikoth/pen/qBBLwOK?editors=1100
[9]:	https://codepen.io/manikoth/pen/oNNJVQq?editors=1100
[10]:	https://codepen.io/manikoth/pen/VwwqRxX
[11]:	https://codepen.io/dudleystorey/pen/izJkB?editors=1100
[12]:	https://codepen.io/PureCSS/pen/GzbRKO