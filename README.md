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
**Example1**: img1.JPG 1.65

upsampling with scale factor of 1.65

input image:

![Input_Image](https://github.com/M-Moeini/Test/blob/main/Pictures/img1.JPG)

output image:

![Output_Image_Scaled_2x](https://github.com/M-Moeini/Test/blob/main/Pictures/img1_BLF_US.jpg)

---

**Example2**: img1.JPG 0.28

downsampling with scale factor of 0.28

input image:

![Input_Image](https://github.com/M-Moeini/Test/blob/main/Pictures/img1.JPG)

output image:

![Output_Image_Scaled_0.7x](https://github.com/M-Moeini/Test/blob/main/Pictures/img1_BLF_DS.jpg)


## 3-Convolution Filters
1. Upload the desired image to content folder if you are using google colab.

2. The first input is the kernel. You can pass it such this: **[[1, 0, -1],[1, 0, -1],[1, 0, -1]]**
3. The second input is the image name. You can pass it such this: **img1.JPG**



**Note**: You can enter any kernel you want with any size


---
**Example**: kernel: [[1, 0, -1],[1, 0, -1],[1, 0, -1]], image name: img1.JPG


input image:

![Input_Image](https://github.com/M-Moeini/Test/blob/main/Pictures/img1.JPG)

output image:

![Output_Image_Scaled_2x](https://github.com/M-Moeini/Test/blob/main/Pictures/img1_ConvF.jpg)



## 4-Box Filter
1. Upload the desired image to content folder if you are using google colab.

2. give the inputs sepertaed by space as: **image_name m n**

**Note**: m and n are the properties of box filters


---
**Example**: img2.JPG 5 5


input image:

![Input_Image](https://github.com/M-Moeini/Test/blob/main/Pictures/img2.JPG)

output image:

![Output_Image_Scaled_2x](https://github.com/M-Moeini/Test/blob/main/Pictures/img2_boxF.jpg)




## 5-High Pass Filter
1. Upload the desired image to content folder if you are using google colab.

2. use convolution filter function
  
3. Pass your desired kernel for a high pass filter like: **[[0, -1, 0],[-1, 4, -1],[0, -1, 0]]** 



---
**Example**: kernel: [[0, -1, 0],[-1, 4, -1],[0, -1, 0]], image name: img1.JPG


input image:

![Input_Image](https://github.com/M-Moeini/Test/blob/main/Pictures/img2.JPG)

output image:

![Output_Image_Scaled_2x](https://github.com/M-Moeini/Test/blob/main/Pictures/img2_HPF.jpg)
