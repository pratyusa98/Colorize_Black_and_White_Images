# Colorize_Black_&_White_Images

This Deep Learning Project aims to provide colorizing black & white images with Python.

In image colorization, we take a black and white image as input and produce a colored image. We will solve this project with OpenCV deep neural network.

For colorizing black and white images we will be using a pre-trained 

          caffe model :- https://code.naturkundemuseum.berlin/mediaspherefornature/colorize_iiif/raw/master/experimental/model/colorization_release_v2.caffemodel
          
          prototxt file:- https://github.com/pratyusa98/Colorize_Black_and_White_Images/blob/main/model/colorization_deploy_v2.prototxt
          
          NumPy file:- https://code.naturkundemuseum.berlin/mediaspherefornature/colorize_iiif/raw/master/experimental/model/pts_in_hull.npy

The prototxt file defines the network and the numpy file stores the cluster center points in numpy format.

![ml](https://pyimagesearch.com/wp-content/uploads/2019/02/bw_colorization_opencv_adrian_janie.jpg)

### Summary:
This repo guides you how to build a deep learning project to colorize black and white images. It first introduces you to Lab color space and why it is favorable for our problem statement. Then step by step it describes how to implement black and white image colorizer.
