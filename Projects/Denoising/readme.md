Image_denoising : Remove Noise from image.


Requisites python and packages: 

python 3.9
opencv 4.1
PIL(python image library)
Numpy
skimage.restoration import estimate_sigma
os
time 

Overview :
To test your own images follow the below steps:

Step 1: Make a folder name Denoising
		1. Inside that folder first copy the Denoising.py file
		2. Also, make folder name Denoised_image and Original_image

Step 2: Copy all the images in Original_image which has to be denoised.

Step 3: Run on terminal type : python Denoising.py.

Step 4: The outputs will be saved in "Denoised_image" directory.

There are two folder directory:

1. Original_image  -- It consist input images
2. Denoised_image  -- Contain output images

To give path for input images : "C:\Users\vipen\Desktop\Denoising\Original_image"
To give path for output images : "C:\Users\vipen\Desktop\Denoising\Denoised_image"

'''

our time measurement is mainly based on image resolution not on image size

On 6GB RAM PC : 
(420, 540, 3) = 4.5 - 4.8 sec
(258, 540, 3) = 2.1 - 2.3 sec
(2200, 1700, 3) = 60 sec
(2338, 1654, 3) = 60 - 62 sec

On 16 GB RAM PC : 
(420, 540, 3) = 1.7 - 1.9 sec
(258, 540, 3) = 1.4 - 1.7 sec
(2338, 1654, 3) = 45 - 47 sec

'''