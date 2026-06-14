This C program performs automatic edge detection and patch-based analysis on BMP images.

It uses fundamental image processing techniques including:



1. Greyscale conversion
2. Gaussian blur (noise reduction)
3. Sobel operator (gradient-based edge detection)
4. Canny edge filtering (non-maximum suppression)
5. Hysteresis thresholding (strong/weak edge connection)
6. Patch analysis (dividing image into blocks and counting edges)



The program will prompt for the path to the BMP file: *images/sample.bmp*

Then, it asks for a patch size, an integer that evenly divides both the image’s height and width.



The processed image is saved automatically as: *results/image\_o.bmp*



The final result highlights patches containing significant edges, helping identify regions of interest in the image.

