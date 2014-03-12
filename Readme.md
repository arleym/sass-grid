# 12 Column Sass Grid
###### v0.0.1

Simple, yet feature rich nestable grids based on Bootstrap / 960 grid. 

***

Bootstrap grids are awesome. This grid system builds on its simplicity adding a few more robust column traits that designs often call for:  

- Added an extension class for tight rows (`.row--tight`) - no margins between columns, or beneath the row.
- Added an extension class for reversing the order of columns on mobile (`.row--inverted`); by default columns float left to right and stack on mobile to show in the same order. This class floats right. This gives you the ability to have text on the left, and an image on the right for large screens, but stack with image first for mobile. 
- Added an extended class to prevent the row from stacking to single column at the 767px breakpoint (`.row--static`). Many of these columns may need to stack at some point, in which case I recommend you extend with your own module namespaced class using a media query at the ideal width. 
- Naturally you can mix and match these perfectly: `<div class="row row--tight row--static row--inverted"></div>`
- Using `.row` instead of `.row-fluid`. By default these rows are fluid to the parent, which doesn't have to be responsive.


### Demo

There's a [demo on CodePen](http://codepen.io/ArleyM/pen/oAhjf).

And I've blogged about this a bit more at [ArleyM.com](http://arleym.com/faux-forking-bootstrap-grids/). 



### Futurey stuff
In nearly a year of using this grid I haven't needed a row of five columns yet (20%, 40%, 60%, 80%). That may come!



#### Thanks! 

[@ArleyM](http://twitter.com/ArleyM)