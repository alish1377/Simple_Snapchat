# Simple_Snapchat
## An introduction to the Augmented Reality world
In this project, a simple Snapchat application is implemented using some compute vision algorithms. The process is as follows:
1. Extract key points using the shape_detector function from the dlib library
2. Find the Homography matrix between the jocker.png(mask image) and all individual's face images using the findHomography function from OpenCV and fit the mask to all faces using this matrix.
3. Evaluate the robustness of fitting regarding the new mask-faces.

Some results of this work:


