# Face_Detection_OpenCV
<b>A simple face detection using OpenCV</b><br><br>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/OpenCV_Logo_with_text_svg_version.svg/180px-OpenCV_Logo_with_text_svg_version.svg.png"><br><br>
<b>Introduction to OpenCV-Python Tutorials</b><br>
<b>OpenCV</b><br><br>
OpenCV was started at Intel in 1999 by Gary Bradsky and the first release came out in 2000. Vadim Pisarevsky joined Gary Bradsky to manage Intel’s Russian software OpenCV team. In 2005, OpenCV was used on Stanley, the vehicle who won 2005 DARPA Grand Challenge. Later its active development continued under the support of Willow Garage, with Gary Bradsky and Vadim Pisarevsky leading the project. Right now, OpenCV supports a lot of algorithms related to Computer Vision and Machine Learning and it is expanding day-by-day.
<br><br>
Currently OpenCV supports a wide variety of programming languages like C++, Python, Java etc and is available on different platforms including Windows, Linux, OS X, Android, iOS etc. Also, interfaces based on CUDA and OpenCL are also under active development for high-speed GPU operations.
<br><br>
OpenCV-Python is the Python API of OpenCV. It combines the best qualities of OpenCV C++ API and Python language.
<br><br>
<b>OpenCV-Python</b><br><br>
Python is a general purpose programming language started by Guido van Rossum, which became very popular in short time mainly because of its simplicity and code readability. It enables the programmer to express his ideas in fewer lines of code without reducing any readability.
<br><br>
Compared to other languages like C/C++, Python is slower. But another important feature of Python is that it can be easily extended with C/C++. This feature helps us to write computationally intensive codes in C/C++ and create a Python wrapper for it so that we can use these wrappers as Python modules. This gives us two advantages: first, our code is as fast as original C/C++ code (since it is the actual C++ code working in background) and second, it is very easy to code in Python. This is how OpenCV-Python works, it is a Python wrapper around original C++ implementation.
<br><br>
And the support of Numpy makes the task more easier. Numpy is a highly optimized library for numerical operations. It gives a MATLAB-style syntax. All the OpenCV array structures are converted to-and-from Numpy arrays. So whatever operations you can do in Numpy, you can combine it with OpenCV, which increases number of weapons in your arsenal. Besides that, several other libraries like SciPy, Matplotlib which supports Numpy can be used with this.
<br><br>
So OpenCV-Python is an appropriate tool for fast prototyping of computer vision problems.
<br><br>
<b>OpenCV-Python Tutorials</b><br><br>
OpenCV introduces a new set of tutorials which will guide you through various functions available in OpenCV-Python. This guide is mainly focused on OpenCV 3.x version (although most of the tutorials will work with OpenCV 2.x also).
<br><br>
A prior knowledge on Python and Numpy is required before starting because they won’t be covered in this guide. Especially, a good knowledge on Numpy is must to write optimized codes in OpenCV-Python.
<br><br>
I have used the pre-modeled data "haarcascade_frontalface_default" You can get the data from <a href= "https://github.com/balayogistark/Face_Detection_OpenCV">here</a>.<br><br>
The Input image is, 
<br><br>
<img src="/humans.jpg">
<br><br>
The output of the face detection is, 
<br><br>
<img src="/result.jpg">
