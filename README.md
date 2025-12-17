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

