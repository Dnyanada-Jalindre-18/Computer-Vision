## Canny Edge Detection
* The Canny edge detector is an edge detection operator that uses a multi-stage algorithm to detect a wide range of edges in images

## Hough transform
* The Hough Transform is a method that is used for detecting shapes during image processing.
* The Hough transform takes a binary edge map as input and attempts to locate edges placed as straight lines. 
* The idea of the Hough transform is, that every edge point in the edge map is transformed to all possible lines that could pass through that point.
* To determine the areas where most Hough space lines intersect, an accumulator covering the Hough space is used. When an edge point is transformed, bins in the accumulator is incremented for all lines that could pass through that point
### Applications :
1. Detecting regular curves such as lines, circles, ellipses etc.
2. Used extensively in barcode scanning, verification and recognition
