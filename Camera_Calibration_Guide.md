# Camera Calibration Guide

## Introduction

Camera calibration is a crucial step in computer vision and photography. It involves estimating the intrinsic and extrinsic parameters of a camera to correct for lens distortion and obtain accurate measurements from images.

### Why Calibrate Your Camera?

Calibrating your camera ensures:
- **Accurate Measurements**: Corrects for lens distortions that can affect measurements.
- **Improved Image Quality**: Reduces image distortions, improving overall image quality.
- **Consistency**: Ensures consistent results across different images and cameras.

## Taking Calibration Images

### Equipment Needed:
- **Camera**: The camera you intend to calibrate.
- **Calibration Pattern**: Usually a chessboard pattern(preferably a chess board 8x8) with known dimensions.

### Steps to Capture Calibration Images:

1. **Prepare the Calibration Pattern**:
   - Print or display a high-quality calibration pattern. Ensure it's flat and undistorted.

2. **Set Up Your Camera**:
   - Place the calibration pattern on a flat surface (e.g., table or wall).
   - Ensure the pattern is well-lit with even lighting to avoid shadows.

3. **Capture Images**:
   - Use a variety of orientations and distances from the pattern.
   - Ensure the entire pattern is visible in each image, with clear and sharp corners.

4. **Store Images Properly**:
   - Save images in a folder dedicated to calibration.
   - Ensure filenames are clear and sequential for easy reference.

## Common Mistakes to Avoid:

- **Incorrect Pattern Size**: Use the correct dimensions for the calibration pattern.
- **Poor Lighting**: Ensure uniform and adequate lighting to avoid shadows.
- **Blurry Images**: Maintain sharp focus to accurately detect pattern corners.
- **Incomplete Pattern**: Ensure the entire pattern is visible in each image.
- **Pattern position in Image**: Ensure that throughout the images, the pattern is covering the whole image canvas. 
- **Variable Distance**: The distance between the chessboard and the camera does not need to be constant. In fact, varying the distance and angles helps the calibration process by providing a more comprehensive set of data points.
- **Overlap**: Ensure there is some overlap in the visible corners between consecutive images to maintain continuity in the detected points.

## Camera Calibration Process

To calibrate your camera:

1. **Capture Calibration Images**: Use the "Testing_Camera.ipynb" notebook to capture images of the calibration pattern from different angles and distances.

2. **Calibrate Using OpenCV**: Use the "camera_calibration.ipynb" notebook to process the captured images. This notebook will calculate the camera matrix and distortion coefficients based on the detected corners of the calibration pattern.

3. **Apply Calibration Parameters**: Once calibrated, you can use the obtained camera matrix and distortion coefficients to undistort images captured with the calibrated camera.

