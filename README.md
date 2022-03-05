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

# Requirements
Requirements to execute the python Jupyter Notebook(.ipynb) file
	1) You need to install the latest version(good to have) or python interpreter. 
	2) You can install any platform such as pycharm, Visual Studio Code etc to run your code.
	3) Also, if you want to execute .ipynb files, the system should have anaconda-opensource platform which 
		will help to compile, run and execute your notebook.
	4) Install the required input videos .
	5) You need to modify the paths of input where your videos are there.Otherwise an error will be generated.
	5) Run the cells one by one.
	5) If given folders do not exist then it will automatically create in current directory.
	6) Output files will be generated, extracting the characters from giver Cement Bags.

---------------------------------------------------------

# Solution :
	We have done using OpenCV - computer vision technique, which is the most useful library to work with the video processing, Image-
	Processing data, Applying different different filters, removing noise, sharpen the image etc.
	so, after loding the required modules, we extract the images from 2 different videos and store it inside the sample_images
	folder. thenafter in order to sharpen the image(become more brighter) we apply the filter and we assign middle value as 13 using 
	trial and error.after that we checked with conversion of BGR to HSV image and again checking in BGR images.
	
	The output images will contain detected characters format in given cement bags....
	2 folders . 1) contains HSV images
		    2) contains Grayscale Images	 

	In both the files, the output images will show the extracted label (characters) in both the forms, either in Grayscale image,	
	or in HSV image..
	
	you might feel, like little bit blur kind of an images that the output has generated but, we have tried all the noise-removal 
	filters, function and so on and come up with the best solution
