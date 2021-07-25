Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout too

To draw a line chart, the first thing we need to do is create a canvas element in our HTML.

We can actually pass some options to the chart via the Line method, but we’re going to stick to the data for now to keep it simple.

The great things about Chart.js are that it’s simple to use and really very flexible.


It's easy to get started with Chart.js. All that's required is the script included in your page along with a single <canvas> node to render the chart.


Before submitting an issue or a pull request to the project, please take a moment to look over the contributing guidelines first.


At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the <canvas> element has only two attributes, width and height.


The <canvas> element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown.



Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high.


When the canvas is initialized or beginPath() is called, you typically will want to use the moveTo() function to place the starting point somewhere else. We could also use moveTo() to draw unconnected paths. Take a look at the smiley face below.


 If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.


In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

The line width is the thickness of the stroke centered on the given path. In other words, the area that's drawn extends to half the line width on either side of the path


The canvas rendering context provides two methods to render text:

1. fillText(text, x, y [, maxWidth]):
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

2. strokeText(text, x, y [, maxWidth]):
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.



