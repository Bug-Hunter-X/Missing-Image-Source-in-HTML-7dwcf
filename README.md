# Missing Image Source in HTML

This repository demonstrates an uncommon HTML error related to missing image sources. The error occurs when an image tag references a file that does not exist in the specified path, resulting in a broken image element.

## Bug Description
The HTML file includes an `<img>` tag with a `src` attribute pointing to an image file, `missing-image.jpg`. However, this image file is not present in the same directory as the HTML file.

## Solution
The solution involves either providing the correct path to an existing image or replacing the `src` attribute with a placeholder image or removing the image element completely.

## Files
* `bug.html`: The HTML file with the error.
* `bugSolution.html`: The corrected HTML file.