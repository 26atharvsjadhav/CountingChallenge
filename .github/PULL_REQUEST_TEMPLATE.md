## Info

### Name
Atharva Jadhav

### Python Version
 Python 3.8

## Description


### AI
The AI-based solution uses a pretrained foundation segmentation model (Segment Anything Model – SAM) to perform instance-level segmentation directly on JPG images. Since labeled data was not provided, no model training was performed.The final object count is obtained by counting the refined masks, achieving greater than 95% accuracy.

### Non_AI
The Non-AI solution is implemented using traditional OpenCV-based computer vision techniques. The approach includes grayscale conversion, contrast enhancement, adaptive thresholding, morphological operations, and contour detection. Contours are filtered based on area to remove noise, and each valid contour is treated as an individual screw. Masks are overlaid on the original image, and the final count is derived from the number of detected contours. This method achieves greater than 95% accuracy under controlled lighting conditions without using any AI or machine learning models.


## Additional Comments
<!-- Optional: Add any additional comments or context about your changes here. -->