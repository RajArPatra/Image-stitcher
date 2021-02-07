# Image-Stitcher
This is An Implementation of efficient stitching of multiple sequential Image to get a complete stitched image.

### Part 1 - Callibration 

To get most out of a stitcher we need to callibrate the images from the camera whoose images we would stitch. 
Use chessborad images as shown below to get the callibration parameters.
Use the Notebook and the part 1 portion to get the callibration Parameters.

#### Chessboard Images
<img src="https://github.com/DRIP-AI-RESEARCH-JUNIOR/Image-Stitcher/blob/master/cal1.jpg" height="20%" width="20%">
<img src="https://github.com/DRIP-AI-RESEARCH-JUNIOR/Image-Stitcher/blob/master/cal2.jpg"  height="20%" width="20%">
<img src="https://github.com/DRIP-AI-RESEARCH-JUNIOR/Image-Stitcher/blob/master/cal3.jpg"  height="20%" width="20%">

### Part 2 - Undistort and Stitching.
Use the part 2 cells in the notebook to get the final output
The cells additionally contains 2 flags -
 - crop: set this as True to get an cropped output of the final stitched image , cropping out all the 0 pixel images.
 - merge: set this as True if you want the final imaage to have both the first frame and last frame as same.
#### Original Image:
![alt text](https://github.com/DRIP-AI-RESEARCH-JUNIOR/Image-Stitcher/blob/master/Original.png?raw=true)
#### Undistorted Image:
![alt text](https://github.com/DRIP-AI-RESEARCH-JUNIOR/Image-Stitcher/blob/master/Undistort.png?raw=true)
#### Final Image with crop and merge as True:
![alt text](https://github.com/DRIP-AI-RESEARCH-JUNIOR/Image-Stitcher/blob/master/final.png?raw=true)
