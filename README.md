# EX.8 - Image Segmentation Using Thresholding Techniques in OpenCV
# Aim
To segment an image using Global Thresholding, Adaptive Thresholding, and Otsu's Thresholding techniques using Python and OpenCV.

# The program performs the following operations:

 Global Thresholding
 Adaptive Thresholding
 Otsu's Thresholding
# Software Used
 Anaconda – Python 3.7
 Jupyter Notebook / VS Code
 OpenCV (cv2)
 NumPy
 Matplotlib
 Algorithm
# Step 1:
Import the required libraries: OpenCV, NumPy, and Matplotlib.

# Step 2:
Load the input image using OpenCV.

# Step 3:
Convert the input image into grayscale format.

# Step 4: Global Thresholding
Select a fixed threshold value.
Apply thresholding to separate foreground and background pixels.
Display the thresholded image.
# Step 5: Adaptive Thresholding
Compute threshold values for small regions of the image.
Apply Adaptive Mean Thresholding.
Apply Adaptive Gaussian Thresholding.
Display the segmented images.
# Step 6: Otsu's Thresholding
Automatically determine the optimal threshold value.
Apply Otsu's thresholding technique.
Display the segmented image.
# Step 7:
Compare the results obtained from Global, Adaptive, and Otsu's thresholding methods.

Program developed by
# Name: Harini V K
# Register No: 212225220036

# Program

# Original Grayscale Image
The grayscale version of the input image is displayed.
Serves as the input for thresholding operations.
```
plt.subplot(2, 2, 1)
plt.imshow(cv2.cvtColor(image, cv2.COLOR_BGR2RGB))  # Convert from BGR to RGB for display
plt.title("Original Image")
plt.axis('off')

```
# Global Thresholding
Original image is displayed.
Thresholded image is displayed.
A fixed threshold value is used for segmentation.
Pixels are classified as foreground or background.

```
plt.subplot(2, 2, 2)
plt.imshow(global_thresholded, cmap='gray')
plt.title("Global Thresholding")
plt.axis('off')

```
# Adaptive Thresholding
Original image is displayed.
Adaptive Mean Thresholded image is displayed.
Adaptive Gaussian Thresholded image is displayed.
Threshold values vary across different regions of the image.
Suitable for images with uneven illumination.

```
plt.subplot(2, 2, 3)
plt.imshow(adaptive_thresholded, cmap='gray')
plt.title("Adaptive Thresholding")
plt.axis('off')

```
# Otsu's Thresholding
Original image is displayed.
Otsu segmented image is displayed.
Optimal threshold value is calculated automatically.
Produces improved segmentation for bimodal histograms.

```
plt.subplot(2, 2, 4)
plt.imshow(otsu_thresholded, cmap='gray')
plt.title("Otsu's Method")
plt.axis('off')

# Show the plot
plt.tight_layout()
plt.show()

```
# Output

<img width="507" height="395" alt="image" src="https://github.com/user-attachments/assets/e709389b-a720-4bba-b143-b4a628dd2301" />

<img width="402" height="295" alt="image" src="https://github.com/user-attachments/assets/b807fa2d-c86f-4aa1-9ac2-2c54cf745273" />

<img width="367" height="305" alt="image" src="https://github.com/user-attachments/assets/40f1286b-71fa-4b1f-b710-1e33dd0db179" />

<img width="326" height="300" alt="image" src="https://github.com/user-attachments/assets/fb4073e6-f8e0-4131-b666-5ca69103299f" />

# Result
Thus, image segmentation is successfully performed using Global Thresholding, Adaptive Thresholding, and Otsu's Thresholding techniques in OpenCV.









# 
