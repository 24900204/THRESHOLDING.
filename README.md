# THRESHOLDING
## Aim
To segment the image using global thresholding, adaptive thresholding and Otsu's thresholding using python and OpenCV.

## Software Required
1. Anaconda - Python 3.7
2. OpenCV

## Algorithm

### Step1:
Import the required libraries such as OpenCV (cv2) and Matplotlib (pyplot) for image processing and visualization.

### Step2:
Read the input image using cv2.imread() and convert it into grayscale using cv2.cvtColor() (only if the image is in color).

### Step3:
Apply Global Thresholding using cv2.threshold() by selecting a fixed threshold value to segment the image.

### Step4:
Apply Adaptive Thresholding using cv2.adaptiveThreshold() to segment the image based on local pixel intensity variations.

### Step5:
Apply Otsu’s Thresholding using cv2.threshold() with cv2.THRESH_OTSU to automatically determine the optimal threshold value and display all results using matplotlib.

## Program

```python
# Load the necessary packages





# Read the Image and convert to grayscale




# Use Global thresholding to segment the image




# Use Adaptive thresholding to segment the image




# Use Otsu's method to segment the image 




# Display the results





```
## Output

### Original Image
<br>
<br>
<br>
<br>
<br>

### Global Thresholding
<br>
<br>
<br>
<br>
<br>

### Adaptive Thresholding
<br>
<br>
<br>
<br>
<br>

### Optimum Global Thesholding using Otsu's Method
<br>
<br>
<br>
<br>
<br>


## Result
Thus the images are segmented using global thresholding, adaptive thresholding and optimum global thresholding using python and OpenCV.
