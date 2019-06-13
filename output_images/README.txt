This folder contains the output images from my project solution
Output images from every step of the algorithm, can also be found in the Advanced Lane Line.html.
The structure of the folder is:

Output_images
	|
	|__ Camera_cal> Calibration output and Chessboard corners
	|
	|__ Undistorted> Undistorted Images
	|
	|__ Thresholded> Binary images: after color thresholding, HLS and Sobel transformation
	|
	|__ Perspective> Bird-eye view of the thresholded images
	|
	|__ Final_Images> The final output of the algorithm: 
			Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position

Please note: The output images of the "finding the lines" step (Histogram Peaks, Sliding Window and Fitting Lane Curves) 
	can be found in the Advanced Lane Line.html