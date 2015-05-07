## Website Performance Optimization portfolio project

### About
The Main objective was to optimize the critical rendering path, making the page render as quickly as possible, using techniques you've seen in the [Website Performance Optimization](https://www.udacity.com/course/ud884).

### How to run
To get started, download the entire directory from my github (https://github.com/Ahmed-hadi/P4_resubmitted.git), and open index.html in a browser locally or you can use github pages link: http://ahmed-hadi.github.io/P4_resubmitted/.

### Page load speed optimization
- Image compression: images were rescaled and resized to the final layout dimensions.
- Moved the google font and the style.css links to the end of the body.  
- Added an inline style block in the head where I put the styles needed to properly render margins, paddings, colors, and borders.
- Added `media="print"` to the link to print.css.

### Frame rate optimization
- Loop optimization: unnecessary JS operations were pulled out of `for` loops where possible in changePizzaSize() at `views/js/main.js`.
- and also optimized updatePosition() functions
- Compressed images and updated/specified image dims
