\\ DIP Task 09 – Comprehensive Color Image Analysis

Overview
This project performs a detailed color image analysis using Python and popular image processing libraries. The script runs in Google Colab, allowing users to upload an image at runtime and explore how different color spaces and processing techniques affect image representation and segmentation.

Objectives
To upload and analyze a color image interactively
To convert a color image into grayscale
To extract and visualize individual RGB color channels
To study image behavior in multiple color spaces
To apply white balance correction
To perform color masking and segmentation
To compare segmentation results across color spaces

Tools & Libraries Used
Python
OpenCV (cv2)
NumPy
Matplotlib
Google Colab

Processing Steps
1. Image Upload & Grayscale Conversion
The user uploads an image at runtime. The image is converted to grayscale and displayed alongside the original color image for comparison.

2. RGB Channel Extraction
The Red, Green, and Blue channels are separated and visualized individually to observe their contribution to the overall image.

3. Color Space Conversions
The image is converted into multiple color spaces:
HSV (Hue, Saturation, Value)
YCbCr (Luminance and Chrominance)
Lab (Lightness and color components)
Each color space representation is displayed for visual analysis.

4. White Balance Correction
White balance is applied using the Gray World assumption, which normalizes the average intensity of color channels to produce a more natural-looking image.

5. Color Masking (HSV Space)
A color mask is created in the HSV color space to isolate a specific color (e.g., green). This demonstrates the effectiveness of HSV in color-based object detection.

6. Color-Based Segmentation
A simple segmentation technique is applied in another color space, such as thresholding on the Lab “a” channel, to segment objects based on color characteristics.

Results Visualization
All outputs are displayed using Matplotlib, including:
Original and grayscale images
Individual RGB channels
HSV, YCbCr, and Lab representations
White-balanced image
Color-masked result
Segmentation outputs
Visual comparison helps evaluate segmentation effectiveness across different color spaces.

Applications
Color-based object detection
Image enhancement and correction
Computer vision preprocessing
Digital image processing education

Conclusion
This task highlights the importance of color spaces in image analysis. By comparing grayscale, RGB, HSV, YCbCr, and Lab representations, the project demonstrates how different color models improve masking and segmentation performance for specific applications.