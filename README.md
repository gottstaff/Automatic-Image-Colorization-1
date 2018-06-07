# Automatic-Image-Colorization

Our task is to convert given grey-scale image into colorized(RGB) image.

## Introduction

Given a grayscale image input, our objective is to find out its believable color image without any manual intervention. Accomplishing this task is a difficult problem because there is often no “correct” attainable color for a given image as the color of the t-shirt can be anything from white to red or black.  

## Lab Color Space

It is also known as [CIELAB color space](https://en.wikipedia.org/wiki/CIELAB_color_space). 

It is expressed in three numerical values *(L,a,b)* as
- **L(Luminance)** for the lightness 
- **a** for the green–red color components
- **b** for the blue–yellow color components

![image](images/lab_space.jpg)

Each and every image while training phase is first converted to the Lab color space then passed it further for processing. The Luminance(L) channel is nothing but the grayscale image of the color image given for the training.

*Why do we use Lab color space?*
> The reason for using this over RGB because euclidean distance in Lab is more similar to how humans perceive color differences.

## Approaches

Here to build a solution, we are exploring various options from traditional hand-picked features to modern deep learning techniques.

### 1. Feed Forward Neural Network

### 2. Combination of Feed Forward Neural Network and Hand Picked Features

### 3. Convolutional Neural Network (CNN)


## References

1. [Colorful Image Colorization](https://arxiv.org/pdf/1603.08511.pdf) by Richard Zhang, Phillip Isola, and Alexei A. Efros
2. [Automatic Colorization of Grayscale Images](http://cs229.stanford.edu/proj2013/KabirzadehSousaBlaes-AutomaticColorizationOfGrayscaleImages.pdf)
