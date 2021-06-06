# **Charts**

* displaying data visually in a way better than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.

### **Chart.js**

* A ***JavaScript*** plugin that uses ***HTML5’s canvas*** element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

### **Installation**

* You can get the latest version of Chart.js from [npm](https://www.npmjs.com/package/chart.js) , the [GitHub releases](https://github.com/chartjs/Chart.js/releases/tag/v3.3.2) , or use a [Chart.js CDN](https://www.jsdelivr.com/package/npm/chart.js) . Detailed installation instructions can be found on the installation page.


# **Canvas API**

* > At first sight a `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the `<canvas>` element has only two attributes, width and height.

### **Drawing Rectangles**

   -  `fillRect(x, y, width, height)`: _Draws a filled rectangle._
   - `strokeRect(x, y, width, height)`: _Draws a rectangular outline._
   - `clearRect(x, y, width, height)`: _Clears the specified rectangular area, making it fully transparent._

### **Drawing Paths**

   - `beginPath()`: _Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up._
   - `Path methods`: _Methods to set different paths for objects._
   - `closePath()`: _Adds a straight line to the path, going to the start of the current sub-path._
   - `stroke()`: _Draws the shape by stroking its outline._
   - `fill()`: Draws a solid shape by filling the path's content area.


### **Drawing Triangle**

   - `moveTo(x, y)`: _Moves the pen to the coordinates specified by "x" and "y"._


### **Drawing Lines**
   - `lineTo(x, y)`: _Draws a line from the current drawing position to the position specified by "x" and "y"._

### **Drawing Arcs**

   - `arc(x, y, radius, startAngle, endAngle, counterclockwise)`: _Draws an arc which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction indicated by counterclockwise (defaulting to clockwise)._

   - `arcTo(x1, y1, x2, y2, radius)`: _Draws an arc with the given control points and radius, connected to the previous point by a straight line._

### **Bezier and quadratic curves**

   - `quadraticCurveTo(cp1x, cp1y, x, y)`: _Draws a quadratic Bézier curve from the current pen position to the end point specified by x and y, using the control point specified by cp1x and cp1y._

   - `bezierCurveTo(cp1x, cp1y, cp2x, cp2y, x, y)`: _Draws a cubic Bézier curve from the current pen position to the end point specified by x and y, using the control points specified by (cp1x, cp1y) and (cp2x, cp2y)._


# **Applying styles and colors**

### **Colors**

   - `fillStyle = color`: _Sets the style used when filling shapes._
   - `strokeStyle = color`: _Sets the style for shapes' outlines._

### **Transparency**

   - `globalAlpha = transparencyValue`: _Applies the specified transparency value to all future shapes drawn on the canvas. The value must be between 0.0 (fully transparent) to 1.0 (fully opaque). This value is 1.0 (fully opaque) by default._

### **Line styles**

* `lineWidth = value`: _Sets the width of lines drawn in the future._
* `lineCap = type`: _Sets the appearance of the ends of lines._
* `lineJoin = type`: _Sets the appearance of the "corners" where lines meet._
* `miterLimit = value`: _Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes._
* `getLineDash()`: _Returns the current line dash pattern array containing an even number of non-negative numbers._
* `setLineDash(segments)`: _Sets the current line dash pattern._
* `lineDashOffset = value`: _Specifies where to start a dash array on a line._

### **Gradients**

* `createLinearGradient(x1, y1, x2, y2)`: _Creates a linear gradient object with a starting point of (x1, y1) and an end point of (x2, y2)._
* `createRadialGradient(x1, y1, r1, x2, y2, r2)`: _Creates a radial gradient. The parameters represent two circles, one with its center at (x1, y1) and a radius of r1, and the other with its center at (x2, y2) with a radius of r2._
* `createConicGradient(angle, x, y)`: _Creates a conic gradient object with a starting angle of angle in radians, at the position (x, y)._
* `gradient.addColorStop(position, color)`: _Creates a new color stop on the gradient object._

### **Patterns**

* `createPattern(image, type)`:
  - **repeat**: Tiles the image in both vertical and horizontal directions.
  - **repeat-x** Tiles the image horizontally but not vertically.
  - **repeat-y**: Tiles the image vertically but not horizontally.
  - **no-repeat**: Doesn't tile the image. It's used only once.


### **Shadows**

  - `shadowOffsetX = float`: _ndicates the horizontal distance the shadow should extend from the object. This value isn't affected by the transformation matrix. The default is 0._
  - `shadowOffsetY = float`: _Indicates the vertical distance the shadow should extend from the object. This value isn't affected by the transformation matrix. The default is 0._
  - `shadowBlur = float`: _Indicates the size of the blurring effect; this value doesn't correspond to a number of pixels and is not affected by the current transformation matrix. The default value is 0._
  - `shadowColor = color`: _A standard CSS color value indicating the color of the shadow effect; by default, it is fully-transparent black._


### **Canvas fill rules**

  * > When using fill (or clip and isPointInPath) you can optionally provide a fill rule algorithm by which to determine if a point is inside or outside a path and thus if it gets filled or not. This is useful when a path intersects itself or is nested.


### **Drawing text**

  - `fillText(text, x, y [, maxWidth])`: _Fills a given text at the given (x,y) position. Optionally with a maximum width to draw._
  - `strokeText(text, x, y [, maxWidth])`: _Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw._

### **Styling text**

  - `font = value`: _The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif._
  - `textAlign = value`: _Text alignment setting. Possible values: start, end, left, right or center. The default value is start._
  - `textBaseline = value`: _Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic._
  - `direction = value`: _Directionality. Possible values: ltr, rtl, inherit. The default value is inherit._