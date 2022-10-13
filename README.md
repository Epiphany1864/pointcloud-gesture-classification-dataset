# pointcloud-gesture-classification-dataset
This dataset contains the gesture samples used in our pointcloud's gesture classification project. 

It is collected by millimeter-wave (mmWave) FMCW radar and has proven to have a satisfactory classification accuracy for 5 gestures, ranging from 1m to 2.4m, -45° to +45°。

Data Structure

Data structure: The data structure of each gesture is 10* n, where n is various with frames and 
10 are 'frame id’, 'detected points in each frame’, 'x coordinate of each point’, 'y coordinate of each point’, 'z coordinate of each point’, 
'velocity of each point’, 'azimuth of each point', 'elevation of each point', 'SNR of each point' and 'noise of each point'.
