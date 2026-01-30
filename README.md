# 📘 Digital Image Processing – Lab Tasks

This repository contains implementations of fundamental Digital Image Processing (DIP) techniques completed for the **Digital Image Processing** subject. The tasks include RGB color analysis, grayscale and binary conversion, Connected Component Labeling (CCL), and histogram equalization.


## 🧪 Task 1 – RGB Image Display
This task focuses on understanding RGB color representation in digital images.

### ✔ Operations Performed
- Displayed the **original RGB image**
- Extracted and visualized the **Red**, **Green**, and **Blue** channels
- Observed how each channel contributes to the final image

---

## 🧪 Task 2 – Connected Component (CC) Labeling
This task applies **Connected Component Labeling** to identify objects within an image.

### ✔ Operations Performed
- Converted the input image to **binary**
- Applied **Connected Component Labeling (CCL)**
- Displayed labeled regions using different colors or numeric labels
- Analyzed the number and structure of connected components

---

## 🧪 Task 3 – Coin Image Processing
A coin image is processed through multiple stages to identify objects.

### ✔ Operations Performed
- Displayed the **RGB image**
- Extracted and displayed **R**, **G**, and **B** component images
- Converted the image to **grayscale**
- Converted the grayscale image to **binary**
- Applied **Connected Component Labeling** to detect and count coin-like objects

---

## 🧪 Task 4 – Histogram Equalization
This task enhances the visual contrast of an image using histogram equalization.

### ✔ Operations Performed
- Converted the image to **grayscale**
- Computed the image histogram
- Applied **Histogram Equalization**
- Displayed and compared the **original** and **contrast-enhanced** images

---
## 🧪 Task 4 – Component-wise Histogram Equalization and Intensity Transformations

This task enhances image quality by applying histogram equalization and intensity transformation functions on individual components of an image.

### ✔ Operations Performed
- Separated the image into different components  
- Applied histogram equalization on each component individually  
- Applied different intensity transformation functions:
  - Log transformation  
  - Power-law (gamma) transformation  
  - Contrast stretching  
- Enhanced contrast and visibility within each component  
- Combined all processed components to generate a single enhanced colored image  

---

## 🧪 Task 5 – Noise Addition and Filtering Analysis

This task evaluates the effectiveness of different spatial filters on images corrupted by various types of noise.

### ✔ Operations Performed
- Applied Mean, Median, and Gaussian filters on the image  
- Applied Laplacian filter separately for edge enhancement  
- Added Salt & Pepper noise to the image  
- Added Gaussian noise to the image  
- Compared filtering results on noisy images  
- Observed that **Median filter** performs best for **Salt & Pepper noise**  
- Observed that **Gaussian filter** performs best for **Gaussian noise**

---

## 🛠 Tools & Technologies Used
- python 
- OpenCV
- Standard Digital Image Processing techniques

---

🧪 Task 8 – Image Restoration
This task explores techniques to recover the original content of an image from a degraded or noisy version.

✔ Operations Performed
- Noise Injection: Artificially degraded images using Gaussian noise, Salt & Pepper noise, and Motion Blur.
- Filtering & Deconvolution: Applied Median filtering for impulsive noise and Wiener/Inverse filtering to reverse blurring effects.
- Motion Blur Recovery: Specifically restored blurred images by modeling the degradation function.
- Quality Assessment: Computed the Peak Signal-to-Noise Ratio (PSNR) to objectively measure restoration quality.
- Comparative Analysis: Identified the optimal restoration method for each specific degradation type.

---

🧪 Task 9 – Color Image Processing
- This task focuses on manipulating color information across different mathematical representations to enhance or segment images.
✔ Operations Performed
- Channel Extraction: Separated the Red, Green, and Blue components to analyze individual color contributions.
- Color Space Conversion: Transformed images from RGB to specialized spaces including HSV (Hue/Saturation/Value), YCbCr (Luminance/Chrominance), and CIELAB (Perceptual Uniformity).
- White Balance Correction: Adjusted the color temperature to ensure neutral colors (whites/grays) are rendered accurately.
- Color Masking: Isolated specific objects by defining ranges within the HSV color space.
- Segmentation Comparison: Evaluated which color space provided the highest contrast and most robust segmentation for various objects.

---

🧪 Task 12 – Segmentation Techniques
This task focuses on partitioning an image into meaningful regions by grouping pixels based on intensity, color, and spatial similarity.

✔ Operations Performed

- Image Preprocessing: Converted the input image to grayscale and color formats as required for different segmentation techniques.

- Global Thresholding: Applied a fixed threshold value to segment the image into foreground and background regions.

- Local (Otsu’s) Thresholding: Automatically computed an optimal threshold based on image histogram statistics to improve segmentation accuracy.

- Adaptive Thresholding: Performed pixel-wise thresholding using local neighborhood information to handle uneven illumination.

- K-Means Segmentation: Implemented unsupervised clustering-based segmentation with varying cluster sizes (k = 2, 3, and 4) to analyze the effect of cluster count on region separation.

- Mean Shift Segmentation: Applied non-parametric clustering to group pixels based on spatial and color similarity without predefining the number of clusters.

- Visual Comparison: Displayed and compared the results of all segmentation methods to evaluate segmentation quality and region consistency.

- Method Analysis: Discussed the strengths and limitations of threshold-based and clustering-based segmentation techniques.
