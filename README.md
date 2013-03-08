# CAMShift Object Tracker

This code tracks any colored object in a live video stream. The CAMShift algorithm uses color histograms to track a given object. Just select the object on the window and it will be tracked. You can run it on your laptop and your webcam will be used by default. There is a file called "CMakeLists.txt". This file will used to build the project (if you have built OpenCV using cmake). If not, just use the .cpp file in your project and build it. To build using command line, follow the steps below to get it up and running:

	$ cmake .
	$ make
	$ ./main 

The output will be displayed on a window and you can see the object being tracked.