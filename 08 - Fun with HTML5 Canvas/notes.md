## canvas

canvas supports having alternative content and should be included to support older browsers.

<canvas id="stockGraph" width="150" height="150">
  current stock price: $3.15 + 0.15
</canvas>

<canvas id="clock" width="150" height="15":
  <img src="images/clock.png" width="150" height="150" alt=""/>
</canvas>

var canvas = document.getElementById('tutorial');
var ctx = canvas.getContext('2d');

### onload
This does something once the element is loaded.

## ctx
https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D

### ctx.strokeStyle
This lets you set the color, gradient or pattern of what goes on the canvas.

# Find hsl of things.
https://mothereffinghsl.com/


## global composite oprator

globalCompositeOperation

https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/globalCompositeOperation

## ctx.beginPath()

https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/beginPath
Last ctx.beginPath() would be on top because it was drawn last


## ctx.stroke()
https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/stroke

## arrow functions

Arrow functions have different this bindings. Arrow functions inherit the `this` binding of the containing function.

Anonymous and traditional JavaScript functions create their own `this` bindings function.

https://www.w3schools.com/tags/canvas_stroke.asp