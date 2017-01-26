# Resize-binary-edge-image
Resize binary edge image while maintaining curves connectivity and line thickness of one pixel
Resize binary edge image that consists of lines and curves of thickness of one pixels (i.e edge images, graphs, contours..) to new size binary image while maintaining line connectivity and line thickness of one pixel. 
  
  
Input 
I: Binary edge image (logical type) consist of lines and curves with a thickness of one pixel (such as curves, contour line, template, or edge images) 
Sy,Sx: The size of the resized image 
OR 
Sy (no Sx) the scale ratio of the resized image to the original image 
Output 
mat: Resized version of the input image I, also binary edge image, the connectivity/topology of the edges/curves in I is maintained and also the line thickness remains one pixel

Note: 
In addition to enlarging/shrinking of images can also be used to stretch edge images by using different proportions (Sx,Sy) of output image dimension to input image dimension
