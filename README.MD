# TEXTURE EXTRACTION FEATURES USING GLCM #
——————————————————————————————————————————
- TEXTUREFEATUREGLCM.m 
-- source code file

- The code given in folder is to extract the basic features of image user provide:-
 	a. Energy
 	b. Entropy
	c. Homogeneity
	d. Contrast
1. To execute the code in the TEXTUREFEATUREGLCM.m file, paste ( the file in the directory) matlab.
2. Then before executing the code user need to add/paste image in the app folder of application (application directory) 
3. Pass the image name to the image reader command as given below:-
     `i = imread(‘img.jpg');`
     Here img.jpg is the image to be passed.
4. All set to run!! Run the code !!
5. The output produced 
 	a. Above mentioned texture values are shown in vector features=[ ].
	b. Image and its grey scale equivalent is sub plotted.
	c. Also the graph is shown of above texture values.


# TEXTUREFEATUREGLCM_GUI.mlapp (UI) #
———————————————————————————————————————————-
- To run the application install the application by going to the app section in matlab and choose the install app button and select the .mlapp file.
- Open the app and press the INSERT button to select the image from your system files.

