# opencv

how to use:
1/ cmake .
2/ make
3/ ./testTwo -vid gmmtest.wmv

Now, we just read until frame 150. Baseline timing was: 5726.67ms

How to install opencv:

wget https://codeload.github.com/Itseez/opencv/zip/3.1.0    unzip 3.1.0.zip   cd 'opencv home'    mkdir build    mkdir personInstall    cd build   cmake -D CMAKE_BUILD_TYPE=Release -D CMAKE_INSTALL_PREFIX=../personInstall ..    make -j   make install


Then you also need to modify the CMakeList.txt:


set the OPENCV_DIR to the build folder that you just created. 


Bingo!


