# HTML5-Canvas

drawImage has three signatures for drawing in a Canvas object. The link above lists how to use each.

Signature in this context means a specific function call with a number of parameters.

drawImage can be called with either 3, 5, or 9 parameters. So it has 3 signatures.


Syntax
void ctx.drawImage(image, dx, dy);
void ctx.drawImage(image, dx, dy, dWidth, dHeight);
void ctx.drawImage(image, sx, sy, sWidth, sHeight, dx, dy, dWidth, dHeight);



Parameters

image

An element to draw into the context. The specification permits any canvas image source (CanvasImageSource), such as an HTMLImageElement, an HTMLVideoElement, an HTMLCanvasElement or an ImageBitmap.

dx

The X coordinate in the destination canvas at which to place the top-left corner of the source image.

dy

The Y coordinate in the destination canvas at which to place the top-left corner of the source image.

dWidth

The width to draw the image in the destination canvas. This allows scaling of the drawn image. If not specified, the image is not scaled in width when drawn.

dHeight

The height to draw the image in the destination canvas. This allows scaling of the drawn image. If not specified, the image is not scaled in height when drawn.

sx

The X coordinate of the top left corner of the sub-rectangle of the source image to draw into the destination context.

sy

The Y coordinate of the top left corner of the sub-rectangle of the source image to draw into the destination context.

sWidth

The width of the sub-rectangle of the source image to draw into the destination context. If not specified, the entire rectangle from the coordinates specified by sx and sy to the bottom-right corner of the image is used.

sHeight

The height of the sub-rectangle of the source image to draw into the destination context.