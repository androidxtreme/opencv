# NOTICE #

These projects have been reworked into [libfacerec](http://www.github.com/bytefish/libfacerec), which is also available in OpenCV 2.4 (contrib module, slight changes to fit into the OpenCV API). [libfacerec](http://www.github.com/bytefish/libfacerec) comes with unit tested algorithms for Eigenfaces, Fisherfaces and Local Binary Patterns Histograms and contains a lot of fixes for the algorithms. It compiles fine for OpenCV 2.3.1 on Windows and Linux and comes with an extensive documentation (API and tutorials), so you should really *consider it*.

I leave these projects here just for an educational purpose, because they might be interesting to someone. However, I can't give any support on these projects, because I provide unit tested versions of these algorithms in [libfacerec](http://www.github.com/bytefish/libfacerec) and I am only able to support one implementation. That's why I disabled the issue tracker for this project. 

If you want to learn the basics of Eigenfaces and Fisherfaces, please start with my guide on face recognition:

  * http://bytefish.de/pdf/facerec_python.pdf (Python, C++)
  * http://bytefish.de/pdf/facerec_octave.pdf (GNU Octave/MATLAB, C++)
  
It explains the basics and comes with source code in C++, Python and GNU Octave/Matlab.

# bytefish/opencv #

This repository contains OpenCV code and documents.

More (maybe) here: [http://www.bytefish.de](http://www.bytefish.de).

## colormaps ##

An implementation of various colormaps for OpenCV2 C++ in order to enhance visualizations. Feel free to fork and add your own colormaps.

### Related posts ###

  * http://bytefish.de/blog/colormaps_in_opencv

## machinelearning ##

Document and sourcecode about OpenCV C++ machine learning API including:

  * Support Vector Machines
  * Multi Layer Perceptron
  * Normal Bayes
  * k-Nearest-Neighbor
  * Decision Tree

### Related posts ###
  
  * http://www.bytefish.de/blog/machine_learning_with_opencv
  * http://www.bytefish.de/wiki/machine_learning_opencv

## eigenfaces ##

Eigenfaces implementation using the OpenCV2 C++ API. There's a very basic function for loading the dataset, you probably want to make this a bit more sophisticated. The dataset is available at [http://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html](http://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html).

### Related posts ###

  * http://www.bytefish.de/blog/pca_in_opencv
  * http://www.bytefish.de/blog/eigenfaces
  * http://www.bytefish.de/blog/fisherfaces
  
## lbp ##

Implements various Local Binary Patterns with the OpenCV2 C++ API:
  
  * Original LBP
  * Circular LBP (also known as Extended LBP)
  * Variance-based LBP

Basic code for spatial histograms and histogram matching with a chi-square distance is included, but it's not finished right now. There's a tiny demo application you can experiment with.

### Related posts ###

  * http://www.bytefish.de/blog/local_binary_patterns
  * http://www.bytefish.de/wiki/python/numpy/performance
  
## lda ##

Fisherfaces implementation with the OpenCV2 C++ API. Here's my [answer on stackoverflow.com](http://stackoverflow.com/questions/7574623/c-face-detection-recognition-implementations/7864357#7864357) and here's my [blog post on Fisherfaces in OpenCV](http://www.bytefish.de/blog/fisherfaces_in_opencv). If you want some insights how this stuff works, you can read through [my post and experiments with Fisherfaces and Eigenfaces](http://www.bytefish.de/blog/fisherfaces).

### Related posts ###

  * http://www.bytefish.de/blog/fisherfaces
  * http://www.bytefish.de/blog/lda_in_opencv
  * http://www.bytefish.de/blog/fisherfaces_in_opencv

