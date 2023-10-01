# Image Filters

This code contains Nearest neighbour up/down sampler,Convolution filter, High pass filter, Box filter and Bilateral filter.

## Requiement
Please install the followings:

1- <code>Numpy</code>

2- <code>Numbda</code>

3- <code>OpenCV</code>

Note: It is recommended to run the code on google colab or jupyterlab.

## 1-Nearest Neighbour Interpolation
1. Upload the desired image to content folder if you are using google colab.

2. give the inputs sepertaed by space as: **image_name scale**



**Note**: You can enter any number for sacle even float number like 1.35


---
**Example1**: img1.JPG 2

upsampling with scale factor of 2

input image:

![Input_Image](https://github.com/M-Moeini/Test/blob/main/Pictures/img1.JPG)

output image:

![Output_Image_Scaled_2x](https://github.com/M-Moeini/Test/blob/main/Pictures/img1_NNI_US.jpg)

---

**Example2**: img1.JPG 0.7

downsampling with scale factor of 0.7

input image:

![Input_Image](https://github.com/M-Moeini/Test/blob/main/Pictures/img1.JPG)

output image:

![Output_Image_Scaled_0.7x](https://github.com/M-Moeini/Test/blob/main/Pictures/img1_NNI_DS.jpg)



## 2-Bilinear Interpolation
1. Upload the desired image to content folder if you are using google colab.

2. give the inputs sepertaed by space as: **image_name scale**



**Note**: You can enter any number for sacle even float number like 1.35


---
**Example1**: img1.JPG 2

upsampling with scale factor of 1.65

input image:

![Input_Image](https://github.com/M-Moeini/Test/blob/main/Pictures/img1.JPG)

output image:

![Output_Image_Scaled_2x](https://github.com/M-Moeini/Test/blob/main/Pictures/img1_BLF_US.jpg)

---

**Example2**: img1.JPG 0.28

downsampling with scale factor of 0.7

input image:

![Input_Image](https://github.com/M-Moeini/Test/blob/main/Pictures/img1.JPG)

output image:

![Output_Image_Scaled_0.7x](https://github.com/M-Moeini/Test/blob/main/Pictures/img1_BLF_DS.jpg)
