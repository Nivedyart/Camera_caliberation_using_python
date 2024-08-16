# Camera_caliberation_using_python


The process of estimating the parameters of a camera is called camera calibration. This means we have all the information (parameters or coefficients) about the camera required to determine an accurate relationship between a 3D point in the real world and its corresponding 2D projection (pixel) in the image captured by that calibrated camera.

 Here is a python script to automatically find the camera calibration parameters using a 6x8 checkerboard pattern.

 - Data : Images captured in my mobile phone.
 - Output: Caliberation parameters are obtained with the help of camera matrix and distortion matrix.
 
- Camera matrix:

  - Focal lengths (fx, fy): 3851.17150, 3914.32526
  - Optical center (cx, cy): 2064.16708, 891.491145

This matrix indicates the focal lengths and the optical center of the camera. These values are high, which is expected for a camera with a significant zoom factor or a high-resolution sensor.

- Distortion matrix:

  - Radial distortion coefficients (k1, k2, k3): 0.291742399, -0.530679131, -11.5582992
  - Tangential distortion coefficients (p1, p2): 0.00323212242, 0.00137522143

These coefficients represent the lens distortion parameters, which correct the image for barrel or pincushion distortion (radial) and correct for slight tilts and de-centering (tangential).
