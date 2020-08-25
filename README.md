# Azure-Kinect-Extract-Images-IMU
# Introduction

This is a good code to get pictures and IMU file to create a Bag file. The code which works in playback mode and reads the mkv file (how to create a mkv file can be found in this [link](https://docs.microsoft.com/en-us/azure/kinect-dk/azure-kinect-recorder)) to get whole frames and save them according their timestamps in nonosecond. Also, beside readinding pictures it gets the IMU file and save it as a csv file. The order of csv file cells is timestamp in nanosecond, gyro.x, gyro.y, gyro.z, acc.x, acc.y and acc.z respectively.

The format of images are png and the size of them are 480*752.

# Usage Info
For using this code you need OpenCV and libjpeg-turbo::libjpeg-turbo.
