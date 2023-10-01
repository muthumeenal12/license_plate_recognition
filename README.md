# license_plate_recognition
License Plate Recognition involves  
                   1) Number plate detection, 
                   2) Character segmentation, and 
                   3) Character recognition.
The accuracy of plate extraction relies on the character segmentation and character recognition. 

##STEPS:
1. Here, we, first, install all the dependencies like ocr, imutils.
2. As for color images, converting them to grayscale is more efficient to work with.
3. Perform Edge Detection - Canny, Sobel
4. Find the contours and apply the mask
5. Use EasyOcr to get text
6. Vizualize the output

##References:

[ANPRWithPython] ([https://github.com/nicknochnack/ANPRwithPython])
