# Photo-Sketching
It is a simple code which uses python openCV library to generate a pencil sketch from a photo. The steps followed are,

Read the input image as gray scale image
Remove any noise using a 3x3 gaussian filter
Create a negative image
Detect the edges from both image & its negative using Sobel
Merge these two edge images -> These two images reinforces some edges and complements some edges -> Alternatively, these two images can be blended with different weights
Invert the blended image to get black sketch on white background
Show the image and wait for a keystroke to close the display
