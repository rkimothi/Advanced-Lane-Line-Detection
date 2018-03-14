In this project I have used Image Processing using OpenCV library in python. I have also used camera calibration for distortion correction, perspective transform to get bird's eye view of the image, polynomial fitting for lane lines.

First of all I start with calibrating the camera for distortion correction using some chessboard images.

For the project I have used color and gradient filters to filter out the lane lines. Then I have used perspective transform to get a bird's eye view of the image. Then I used histogram to find out the x position of the bottom of the lane lines. Then I found out where the lane lines are and fitted the lane line with polynomials. Then I have highlighted the region of the lane lines and then used inverse perspective transform to change the view to the original image.

Here is a video otuput showing lane lines on a video stream drawn by using this algorithm:
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/CSFoCrawzbA/0.jpg)](https://www.youtube.com/watch?v=CSFoCrawzbA)