# HorizonStabilization

This is a copy of code submitted to the Matlab File Exchange: https://www.mathworks.com/matlabcentral/fileexchange/47606-horizon-stabilization

This toolbox accompanies the article:
Schwendeman, M. and J. Thomson (2015). A Horizon-Tracking Method for Shipboard Video Stabilization and Rectification. Journal of Atmospheric and Oceanic Technology; 32(1):164-176. DOI:10.1175/JTECH-D-14-00047.1

It contains functions to: 
1) Detect the horizon using the Hough Transform (for which either the image processing or computer vision toolbox is needed). 
2) Calculate the exact camera pitch and roll from the horizon orientation. 
3) Stabilize multiple images taken from varying camera angles. 
4) Rectify images to a flat sea-surface using a known camera height. 
5) Estimate the errors in the stabilization or rectification if the uncertainty in camera orientation is known.

Included are two scripts and a set of sample images which are intended to guide the user in the usage of these functions.

It was written using Matlab version 2014a, and requires either the Computer Vision System Toolbox or Image Processing Toolbox. It is covered by the BSD license.
