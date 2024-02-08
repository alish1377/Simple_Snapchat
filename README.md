# Simple_Snapchat
## An introduction to the Augmented Reality world
In this project, a simple Snapchat application is implemented using some compute vision algorithms. The process is as follows:
1. Extract key points using the shape_detector function from the dlib library
2. Find the Homography matrix between the jocker.png(mask image) and all individual's face images using the findHomography function from OpenCV and fit the mask to all faces using this matrix.
3. Evaluate the robustness of fitting regarding the new mask-faces.

Some results of this work:

<img src="https://github.com/alish1377/Simple_Snapchat/blob/main/asset/Screenshot%20from%202024-02-08%2010-14-24.png" width="400" height="400"/><img src="https://github.com/alish1377/Simple_Snapchat/blob/main/asset/Screenshot%20from%202024-02-08%2011-34-59.png" width="400" height="400"/><img src="https://github.com/alish1377/Simple_Snapchat/blob/main/asset/Screenshot%20from%202024-02-08%2010-16-31.png" width="400" height="400"/>

In the last part of the project, the probable reasons for the low accurate performance of the algorithm on the third image are considered.
