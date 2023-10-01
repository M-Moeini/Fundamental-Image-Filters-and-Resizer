# Image Filters

This code contains Nearest neighbour up/down sampler,Convolution filter, High pass filter, Box filter and Bilateral filter.

## Requiement
Please install the followings:
1- <code>Numpy</code>
2- <code>Numbda</code>
3- <code>OpenCV</code>

Note: It is recommended to run the code on google colab or jupyterlab.

## Nearest Neighbour Interpolation
-Upload the desired image to content folder if you are using google colab.

-give the inputs sepertaed by space as below:
 image_name scale sample_type

**Note**: sample type is either **us** or **ds** which representing Upsampling and Downsampling respectively.


---
**example1**: img1.JPG 2 us

upsampling with scale factor of 2

input image:
![Input_Image](https://github.com/M-Moeini/Test/blob/main/Pictures/img1.JPG)

output image:
![Output_Image_Scaled_2x](https://github.com/M-Moeini/Test/blob/main/Pictures/img1_NNI_US.jpg)
