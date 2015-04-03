This directory contains the sample Makefile
that instructs on how to compile C++ codes 
for opencv and also shell scripts used earlier 
for exporting LD_LIBRARY_PATH and PKG_CONFIG_PATH.
Reference links:
1. http://answers.opencv.org/question/14611/example-of-makefile/
2. https://isrishblog.wordpress.com/2012/10/17/makefile-for-opencv-project/

Installing opencv using CMAKE
cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=<path to opencv folder (parent folder of /build)> -D BUILD_ZLIB=ON -D BUILD_PYTHON_SUPPORT=ON ..

export LD_LIBRARY_PATH=${LD_LIBRARY_PATH}:/home/rshukla/openCV_new/opencv/lib/

