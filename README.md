# HTML/CSS website clone project (McDonald's)

Welcome to my McDonald's website clone project, using HTML and CSS.

## Description

This clone is based on the URL:(https://www.mcdonalds.com/us/en-us/about-our-food/meet-our-food-experts.html), and aims at mimicing structuring, layout and styling as much as possible. 

## Structuring

I have structured the website using the appropriate layout, such as grid or flexbox, mainly by oberving the page and tried to limit my usage of Chrome DevTools to the bare minimums such as font-sizes, exact background color codes etc.

## Special CSS features, tooltips etc

Certain features that I have focused on, apart from the general HTML and CSS, are button :hover and :active functions, as well as tooltips for the first three links in the main body content. Media queries have been added to adjust to different screen sizes. 

## Additional notes

### CSS/SCSS formatting
The styling is done with Sass (.scss files), using variables and shared classes to optimize the process and simplify maintenance work in future. 
My naming of the classes follows the BEM naming convention.

### Gulpfile automation
I have created a gulpfile.js to minify HTML, CSS and JS, as well as compile .scss to .css. This gulpfile also watches for changes, and then writes all of the source code file in src/ subfolder into the dist/ subfolder (not in version control). This automates the process workflow and is easily done by simply running 'gulp' in the command line in the root directory. 