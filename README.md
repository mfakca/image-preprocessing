# image-preprocessing

[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Naereen/badges)

Basic methods used in image preprocessing

## 1. Blur:
In most cases, the raw data that we gather has noise in it (unwanted features that makes the image hard to perceive). Removing these noises from the image increases our model accuracy. I applied Gaussian Blur. Sigma is directly proportional to blur. As it increases, the blur increases.

![image](https://github.com/mfakca/image-preprocessing/blob/main/outputs/blur.png)

## 2. Segmentation:
Image Segmentation is the process by which a digital image is partitioned into various subgroups (of pixels) called Image Objects, which can reduce the complexity of the image, and thus analysing the image becomes simpler.

![image](https://github.com/mfakca/image-preprocessing/blob/main/outputs/segmentation.png)

## 3. Erosion:
Erosion washes away the structure of the foreground image making the boundaries thinner. This is achieved with the convolution of the structuring element with the original image.

![image](https://github.com/mfakca/image-preprocessing/blob/main/outputs/erosion.png)

## 4. Dilation:
Dilation is the opposite technique that of erosion. It adds structure to the original image depending on the convolution of the structuring element with the original image.

![image](https://github.com/mfakca/image-preprocessing/blob/main/outputs/dilation.png)
## 5. Edge Detection
![image](https://github.com/mfakca/image-preprocessing/blob/main/outputs/edge_detection.png)

