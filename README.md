# license_plate_recognition
License Plate Recognition involves  
                   1) Number plate detection, 
                   2) Character segmentation, and 
                   3) Character recognition.
The accuracy of plate extraction relies on the character segmentation and character recognition. 

#STEPS
*Here, we, first, install all the dependencies like ocr, imutils.
*As for color images, converting them to grayscale is more efficient to work with.
*Perform Edge Detection - Canny, Sobel
*Find the contours and apply the mask
*Use EasyOcr to get text
*Vizualize the output

##References:

[ANPRWithPython]([https://github.com/nicknochnack/ANPRwithPython])
