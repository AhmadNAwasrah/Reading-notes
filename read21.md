# Chart.js &  Canvas 
##  Canvas

The HTML <canvas> element is used to draw graphics on a web page 
- element is only a container for graphics 
- you must use JavaScript to actually draw the graphics 
- Canvas has several methods for drawing paths, boxes, circles, text, and adding images 
![img](https://pc.eiu.ac/wp-content/uploads/2019/02/100.-Basics-of-to-HTML-5-Canvas-Drawing-600x338.png)
## The rendering context 
lement creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. In this tutorial, we focus on the 2D rendering context. Other contexts may provide different types of rendering 

## Checking for support 
The fallback content is displayed in browsers which do not support <canvas>. Scripts can also check for support programmatically by testing for the presence of the getContext() method. 
## Drawing shapes with canvas
we can get into the details of how to draw on the canvas. By the end of this article, you will have learned how to draw rectangles, triangles, lines, arcs and curves, providing familiarity with some of the basic shapes. Working with paths is essential when drawing objects onto the canvas and we will see how that can be done 
## The grid 
The grid Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we'll see how we can translate the origin to a different position, rotate the grid and even scale it 
![a](data:image/jpeg;base64,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)
# Drawing rectangles 
Unlike SVG, <canvas> only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes. 




## Applying styles and colors 
- Colors  
- fillStyle = color
Sets the style used when filling shapes. 
- strokeStyle = color
Sets the style for shapes' outlines. 
![z](https://mdn.mozillademos.org/files/5417/Canvas_fillstyle.png)
## Transparency 
we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.

globalAlpha = transparencyValue
Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default.
The globalAlpha property can be useful if you want to draw a lot of shapes on the canvas with similar transparency, but otherwise it's generally more useful to set the transparency on individual shapes when setting their colors.

Because the strokeStyle and fillStyle properties accept CSS rgba color values, we can use the following notation to assign a transparent color to them 
# Line styles 
- lineWidth = value
Sets the width of lines drawn in the future. 
- lineCap = type
Sets the appearance of the ends of lines. 
- lineJoin = type
Sets the appearance of the "corners" where lines meet. 
- miterLimit = value
Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes. 
- getLineDash()
Returns the current line dash pattern array containing an even number of non-negative numbers. 
- setLineDash(segments)
Sets the current line dash pattern. 
- lineDashOffset = value
Specifies where to start a dash array on a line. 
![img](https://www.w3resource.com/w3r_images/line-picture.png)
### Drawing text
 he canvas rendering context provides two methods to render text: 
 - fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw
![img](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text/baselines.png)

## Styling text 

- font = value
The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
- textAlign = value
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
- textBaseline = value
Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
- direction = value
Directionality. Possible values: ltr, rtl, inherit. The default value is inherit

## Advanced text measurements 
- measureText()
Returns a TextMetrics object containing the width, in pixels, that the specified text will be when drawn in the current text style.
# charts  

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create. 
A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.



