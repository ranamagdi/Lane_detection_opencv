# 1. What are the purposes from this project :
1. Your pipeline should be able to detect the lanes, highlight them using a fixed color, and paint the 
area between them in any color you like (we paint to green) <br>
2. You’re required to be able to roughly estimate the vehicle position away from the center of the 
lane.<br>
3. As a bonus, you can try to estimate the radius of curvature of the road as well (we make it!).
## Note:
We tried to get the purposes without use Camera Calibration and we get the output fail to detect the curves correctly (you can find our notebook and videos outputs in old_version_with_output folder) .So in the lane_detection_opencv_updated notebook we tried to use the Camera Calibration because we encourage to use when we read that the Camera lenses distort incoming light to focus it on the camera sensor.Although this is very useful in allowing us to capture images of our environment, they often end up distorting light slightly inaccurately.This can result in inaccurate measurements in computer vision applications.So we add this step .<br> And also we tried to use canny detection in old verion but we use it insted sobel.


# 2. How to run the code:
## 2.1 Firstly you need to clone the repo then if you want to see the output from test images :<br>
  You can find Lane_detection_opencv notebook to get the test images with pipeline .
## 2.2 Secondly if you want to see the output from tet videos :<br>
 1. You can find Lane_detection_opencv.py to get the test videos directly by run the script on the command prompt .<br>
 2. You can also find in the Lane_detection_opencv notebook by run code in 2 last cells .<br>
 ## Note :
 when run the code to get the test video you will show 3 input messages:<br>
 1. Choose the debug mode 1 or 0 (if you will choose 1, your pipeline should be showing all the stages that your code is 
going through.but if you choose 0 you will find the final result from pipeline).<br>
 2. Please write the input video path (you will find in Project_data folder 3 test videos with different levels of curves difficulties).
 3. Please wirte the output video path.

# 3. Samples from videos output:
 You can find the test_video_ouput folder 
 ## Note :
 In challenge_video.mp4 and harder_challenge_video.mp4 we tried to get output better than this but we cann't achived maybe we need to apply another techniques .

