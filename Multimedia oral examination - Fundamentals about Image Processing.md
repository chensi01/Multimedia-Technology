# Multimedia oral examination - Fundamentals about Image Processing

------

[TOC]

------

## 1.how image is kept and processed by computer

 Images are represented as of matrix or function with variables of x,y or different color channels in computer.

------

## 2.Why edges?

Edges are more informative,they already carry most of the information to outline an objecuse and use less number of pixels than color blocks.

------

## 3.Operate image as a multi-variable function?
We can operate images as multi-variable function and perform Fourier Transform,Taylor expansion and Search for extremal maximum and minimum values.
These operations can achieve Image/Video Compression.
Perform Gaussian Convolution can filter edges which are informative.

Phase means frequencies on which the signal distributed.Magnitude means the quantity of energy distributed in each phase.Phase carries more information than magnitude.

------

## 4.Operate image as a matrix - Geometric Image Transformations

There are some basic linear transformations,such as Translation，Rotation，Scaling and Affine.
Image Translation moves image along x, y directions or both as a whole.
Image Rotation rotates image along x, y directions or both as a whole.
Image scaling achieves zoom-in or zoom-out effect.
Image Reflection is known as mirroring.If we mirror x and y both, it is then equivalent to rotating 180 degree.
Image affine is a combination of some basic transformations such as Translation，Rotation，Scaling.

------

## 5.Geometrical Invariance 

Some geometrical transformation including scale,rotation,flip,translation invariance,do not affect human's vision system, so image features also need to be robust to these transformations.