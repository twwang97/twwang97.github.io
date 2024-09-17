---
title: "Stereo Reconstruction"
excerpt: "Point-cloud reconstruction from disparity in the context of stereo cameras refers to the process of creating a 3D representation of a scene using information obtained from two or more images captured by stereo cameras.. <br/><img src='/images/disparity_pcd_motorcycle.png'>"
collection: visions
---
The process of point-cloud reconstruction involves the following steps: <br>
(1) <b>Stereo Calibration</b>: <br>
Calibrate the stereo camera system to determine the relative positions and orientations of the cameras. This is crucial for accurately computing the disparity. <br>
(2) <b>Image Rectification</b>: <br>
Rectify the stereo images to ensure that corresponding points in the left and right images lie on the same scanline. This simplifies the disparity calculation. <br>
(3) <b>Disparity Map Calculation</b>: <br>
Compute the disparity map, which represents the pixel-wise differences in the x-coordinates of corresponding points in the left and right images. <br>
(4) <b>Depth Calculation</b>: <br>
Use the disparity information to calculate the depth of each pixel in the scene. This is often done using the triangulation method, where the baseline distance between the cameras and the disparity value are used to compute the depth. <br>
(5) <b>Point-Cloud Generation</b>: <br>
Finally, create a three-dimensional point cloud by associating each pixel's depth value with its corresponding 2D image coordinates. <br>
<br>

* External link: [dataset](https://vision.middlebury.edu/stereo/data/scenes2014/), [github](https://github.com/twwang97/Advanced-Computer-Vision-Homework), [video](https://youtu.be/ybpL50fBDeA)