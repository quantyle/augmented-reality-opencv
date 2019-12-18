# Augmented Reality Concept OpenCV 

This program demonstrates the usage of SURF for feature extraction and image orientation tracking. A video file is rendered over a QR code `QR.png`, then the 3D transformations are applied to orient the video over the QR code. You can find a demonstration of the code here: `https://youtu.be/yNvmfDJDXFM`

## Requirements

1. Ubuntu 18.04
2. OpenCV 3.2.x & Contrib 

## Usage

1. Install OpenCV and contrib modules: `sudo chmod +x install-opencv.sh && ./install-opencv.sh`
2. Configure CMakeLists.txt: `cmake CMakeLists.txt`
3. Build: `make -j8`

