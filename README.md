# 1. The expected output from this project:
1. The pipeline should be able to detect the lanes, highlight them using a fixed color, and paint the area between them in any color (we went for green color for that) <br>
3. The pipeline should roughly estimate the vehicle position away from the center of the lane <br>
3. As a bonus, the pipeline should estimate the radius of curvature of the road as well (we made it!)

## Note:
We tried to get the output without using Camera Calibration, but the curves were not detected correctly (you can find the notebook and videos outputs in old_version_with_output folder). <br>
So in the lane_detection_opencv_updated notebook we tried to use the Camera Calibration. We were encouraged to do so as the camera lenses distort the incoming light to focus it on the camera sensor. Although this is very useful in allowing us to capture images of our environment, they often end up distorting light slightly inaccurately. This can result in inaccurate measurements in computer vision applications. <br>
Additionally, we used "canny detection" in the old version, and we used "sobel" instead in the new version.


# 2. How to run the code:
1. First you need to clone the repo
2. Get the output of the pipeline from the test images using the Lane_detection_opencv_updated notebook
3. Get the output from the test videos using two different options:
  - By running test.bat script <br>
  - By running the last two cells in the Lane_detection_opencv_updated notebook 

## Note:
When you run the script to get the output video, you will be asked to enter three inputs:<br>

1. Select the debuging mode
- Enter 1 to enable the debugging mode. In this mode, the pipeline shows all the stages that code goes through <br>
- Enter 0 to disable tha debugging mode. In this case, the output will be only the final result from the pipeline

2. Enter the input video path <br>
(You can find 3 test videos with different levels of curves difficulties in Project_data folder)

3. Enter the output video path


# 3. Samples from videos output:
You can find them in the test_video_ouput folder 
## Note:
For the challenge_video.mp4 and harder_challenge_video.mp4 videos, we tried to get better outputs but we couldn't. Maybe we need to apply other techniques.

