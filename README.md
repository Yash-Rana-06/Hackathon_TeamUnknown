				MINEd Hackathon: 2022
Track: Applied ML for Manufacturing Industry 's problem (JK-Lakshami-cement)

Team Name : TeamUnknown
Team Leader: Rana Yash : 9429180769
Team Members
Omkarsinh Rana
Darshan Ramani
Raviya Vatsal
Rathod Mayur

--------------------------------------------------------
-> So, basically we have input-dataset in the form of video files..
-> and we need to identify the the labels(week number) from the passing Cement bags.
-> if cement bag doesn't contain any serial number or anything, should create sql query.
-> Solution :
	We have done using OpenCV - computer vision technique, which is the most useful library to work with the video processing, Image-
	Processing data, Applying different different filters, removing noise, sharpen the image etc.
	so, after loding the required modules, we extract the images from 2 different videos and store it inside the sample_images
	folder. thenafter in order to sharpen the image(become more brighter) we apply the filter and we assign middle value as 13 using 
	trial and error.after that we checked with conversion of BGR to HSV image and again checking in BGR images.
	
	The output images will contain detected characters format in given cement bags....
	2 folders . 1) contains HSV images
		    2) contains Grayscale Images	 
