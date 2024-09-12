# 3D Computer Vision Assignments

Welcome to my 3D Computer Vision assignments repository! This collection showcases the work I've completed as part of my course on 3D Computer Vision, covering a range of topics including image processing, camera calibration, quaternions, feature detection, and more. Each assignment reflects a deep dive into key concepts and hands-on implementations, demonstrating practical skills in the field of computer vision.

## Table of Contents

- [Assignment 1: Image Processing and Filtering](#assignment-1-image-processing-and-filtering)
- [Assignment 2: Camera Calibration](#assignment-2-camera-calibration)
- [Assignment 3: Quaternions and Image Mosaicing](#assignment-3-quaternions-and-image-mosaicing)
- [Assignment 4: Fundamental Matrix Estimation](#assignment-4-fundamental-matrix-estimation)
- [Assignment 5: Advanced Feature Detection and Matching](#assignment-5-advanced-feature-detection-and-matching)

## Assignment Details

### Assignment 1: Image Processing and Filtering
This assignment focuses on the basics of image processing, including Discrete Fourier Transform (DFT), spatial filters, and various smoothing and denoising techniques.

**Highlights:**
- Implemented DFT on images to explore frequency components.
- Applied spatial and denoising filters to enhance image quality.
- Experimented with various techniques to understand their effects on images.

[View Assignment 1](./HW1)

### Assignment 2: Camera Calibration
This assignment covers camera calibration techniques to extract camera parameters, which are crucial for 3D computer vision tasks.

**Highlights:**
- Performed camera calibration to determine intrinsic and extrinsic parameters.
- Used calibration techniques on checkerboard images for precise parameter extraction.

[View Assignment 2](./HW2)

### Assignment 3: Quaternions and Image Mosaicing
This assignment dives into quaternions for representing rotations and image mosaicing techniques to create seamless panoramas.

**Highlights:**
- Explored quaternions and their applications in 3D rotations.
- Implemented image mosaicing to stitch images into a single panoramic view.

[View Assignment 3](./HW3)

### Assignment 4: Fundamental Matrix Estimation
This assignment involves implementing the eight-point and normalized eight-point algorithms for estimating the fundamental matrix, a critical component in stereo vision.

**Highlights:**
- Implemented the eight-point algorithm (`estimateF(x1, x2)`).
- Implemented the normalized eight-point algorithm (`estimateFnorm(x1, x2)`).
- Visualized and compared epipolar lines from both estimates.

[View Assignment 4](./HW4)

### Assignment 5: Advanced Feature Detection and Matching
In this assignment, I implemented complex feature detection and matching techniques, including Canny Edge Detection, Harris Keypoint Detector, MSER, and SIFT feature matching.

**Highlights:**
1. **Canny Edge Detection**: Implemented from scratch, covering steps from grayscale conversion to hysteresis thresholding.
2. **Harris Keypoint Detector**: Compared a custom implementation with OpenCV’s version.
3. **MSER Algorithm**: Tuned hyperparameters to detect blobs in an image.
4. **SIFT Feature Matching**: Used SIFT to match templates and validate results against reference images.

[View Assignment 5](./HW5)
