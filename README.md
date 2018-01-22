# PoC Face Recognition: Amazon Rekognition vs Dlib
In this PoC we have compared the performance of two options when analyzing images with faces of people. These options are Amazon Rekognition, a deep learning-based image and video analysis, and Dlib, an open source toolkit for making real world machine learning and data analysis applications in C++.

The problems we've used to test them are the following:

* __Face detection__: detect all the faces in an image
* __Face verification__: check whether a face corresponds to a particular individual (a binary problem)
* __Face identification__: check to which specific person an image of a face corresponds to (multiclass problem)
* __Face clustering__: obtain all unique people from a set of images

We have measured the accuracy and response times of both on each of these different problems. 
The goal is determine if there is some clear better choice, or however, the choice depends on some personal criteria.

