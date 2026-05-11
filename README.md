# OpenCV-Image-Processing-Basics

## AIM

To write a Python program using OpenCV to perform the following operations:
1. Read and display an image.
2. Adjust the brightness of an image.
3. Modify the contrast of an image.
4. Generate a third image using bitwise operations.
5. Split and merge images in RGB and HSV color spaces.
## SOFTWARE REQUIRED
1. Anaconda – Python 3.7
2. Jupyter Notebook
3. OpenCV (cv2)
4. NumPy
5. Matplotlib
## PROGRAM DEVELOPED BY

Name: Aaron I
Register Number: 212223230002

## ALGORITHM
Step 1: Read and Display an Image
Load the image Eagle_in_Flight.jpg in grayscale mode using cv2.imread().
Print the image width, height, and number of channels.
Display the image using matplotlib.pyplot.imshow().
Save the image as a PNG file using cv2.imwrite().
Step 2: Convert and Display Color Image
Read the saved image and convert it into a color image using cv2.cvtColor().
Display the color image and print its dimensions.
Step 3: Crop, Resize, and Flip
Crop the eagle from the image.
Resize the cropped image by a factor of 2.
Flip the image horizontally.
Step 4: Annotate Apollo Launch Image
Read Apollo-11-launch.jpg.
Add the text:
Apollo 11 Saturn V Launch, July 16, 1969
Draw a magenta rectangle around the rocket and launch tower.
Display the final annotated image.
Step 5: Brightness Adjustment
Read Boy.jpg.
Create a matrix of ones using NumPy.
Increase brightness using cv2.add().
Decrease brightness using cv2.subtract().
Display original, brighter, and darker images.
Step 6: Contrast Adjustment
Multiply pixel values by scaling factors 1.1 and 1.2.
Generate higher contrast images.
Display original and modified images.
Step 7: RGB Channel Splitting and Merging
Split the image into Blue, Green, and Red channels.
Display each channel separately.
Merge the channels back into the original image.
Step 8: HSV Channel Splitting and Merging
Convert the image to HSV color space.
Split into Hue, Saturation, and Value channels.
Display each channel.
Merge the channels and convert back to RGB.
Step 9: Bitwise Operations
Apply bitwise operations such as AND, OR, XOR, and NOT to generate transformed images.
## OUTPUT
Read and display grayscale and color images.

Cropped, resized, and flipped images.

Apollo 11 image with text and rectangle annotations.

Brighter and darker versions of Boy.jpg.

Higher contrast images.

RGB and HSV channels displayed separately.

Merged images reconstructed successfully.

Images generated using bitwise operations.

## RESULT

Thus, the Python program was successfully implemented using OpenCV to read and display images, adjust brightness and contrast, perform bitwise operations, and split and merge images in RGB and HSV color spaces.
