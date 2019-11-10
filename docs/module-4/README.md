# Module 3: Layouts Overview

> There is no singular layout method. Understand them all. 



## Formatting Contexts

From CSS Specification: 

“...the environment into which a set of related boxes are laid out. Different formatting contexts lay out their boxes according to different rules. For example, a flex formatting context lays out boxes according to the flex layout rules CSS3-FLEXBOX, whereas a block formatting context lays out boxes according to the block-and-inline layout rules CSS2. ”



## Block Formatting Context

* “is the root element
* `display: inline-block`
* is floated
* `position: absolute`
* :black_nib: Block Formatting Context

## Floats
* wrapping content around
* used with `shape-outside`
* do not use for page layout
* :black_nib: Floats
* :black_nib: [Shape Outside](https://codepen.io/nailaahmad/pen/jorKC)


## Positioning
* Static
* Relative
* Absolute
* Fixed
* :black_nib: Sticky | [Stick vs. Fixed](https://css-tricks.com/creating-sliding-effects-using-sticky-positioning/)
* :black_nib: Absolute Child with Relative Parent


## Multicolumn Content
* method of splitting content into columns
* Simple to use
* Not be used for page layout
* Window and Orphans still an issue on older Browsers
* :black_nib: Multicolumn Content


## FlexBox
* 1 Dimensional Layout
* Features designed for a responsive and flexible content
* Can be used for page layout, but is intended for - content - in the layout
* Different properties for Child vs. Parent
* Future syntax may be added/modified/removed
* :black_nib: [Parent (container) Properties](https://codepen.io/manikoth/pen/eZQwQO?editors=1100)
* :black_nib: [Child (items) Properties](https://codepen.io/manikoth/pen/aNQevB?editors=0110)
* :black_nib: [Direction](https://codepen.io/manikoth/pen/VaqGWr)
* :black_nib: [Justify Content](https://codepen.io/manikoth/pen/grZBrN)



## CSS Grid
* Two Dimensional Layout
* Use for Page Layout
* Use Dev Tools
* So (so) much more. 
* :black_nib: [`display: grid`](https://codepen.io/manikoth/pen/NVRwya)
* :black_nib: [Define Rows & Columns](https://codepen.io/manikoth/pen/EzgbRJ?editors=1100)
* :black_nib: [Line Based Placement](https://codepen.io/manikoth/pen/qGRgaq)