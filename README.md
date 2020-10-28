# image-handler
Small class to read and write images as/from RGB values

## Usage

Simply create a new ImageHandler with the path to your image and retrieve the RGB matrix with `getPixels()`.

To save the image call `savePixels(pixelsToSave, newPath)`. This function also accepts optional new width/height in case the image has been resized from the original one.
