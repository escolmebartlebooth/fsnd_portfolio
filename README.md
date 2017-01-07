# Udacity Full Stack Project: Build a Portfolio

## Implementation

### Pre-Requisites

This project was built using HTML5 and CSS and 1 batch script to resize images:

+ /raw_images/convert_images.bat

This batch file depends on ImageMagick which is not included in this repository

### Files

+ index.html: HTML 5 markup for the webpage. Links to css and google fonts
+ /css/main.css: CSS file for styling
+ /img/*.{jpg,svg}: images and logos for use at various screen sizes

### Implementation notes

+ Imported font from googlefont api (lato)
+ media query breakpoints for viewports at 600 and 900 pixels
+ used picture/sources/srcset elements to control which image size displayed
+ used last-of-type and first-of-type to control margins of project images