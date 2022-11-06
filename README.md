## Install PCL Library

* sudo apt install build-essential pkg-config
* sudo apt install cmake
* sudo apt -y install libpcap-dev libglu1-mesa-dev mesa-common-dev
* sudo apt -y install git-core freeglut3-dev libxmu-dev libxi-dev
* sudo apt -y install libflann-dev
* sudo apt -y install libflann1.9
* sudo apt -y install libboost-all-dev
* sudo apt -y install libeigen3-dev
* wget https://github.com/PointCloudLibrary/pcl/releases/download/pcl-1.12.1/source.tar.gz
* tar xvf source.tar.gz 
* pcl
* mkdir build
* cd build
* cmake ..
* make -j4
* sudo make install

## Buildare ply_downsampler
* git clone git@github.com:ivpcode/ply_downsampler.git
* cd ply_downsampler
* cmake .
* make -j4

