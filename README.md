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

## 🧪 Task 6 – Frequency Domain Filtering using FFT

This task focuses on analyzing images in the frequency domain and separating low-frequency and high-frequency components using Fourier Transform–based filtering.

### ✔ Operations Performed
- Imported the input image and converted it to grayscale for frequency analysis
- Computed the 2D Fast Fourier Transform (FFT) of the image to transform it from spatial to frequency domain
- Shifted the zero-frequency component to the center of the spectrum for better visualization
- Computed and displayed the magnitude spectrum of the FFT image
- Created a low-pass filter mask to preserve low-frequency components representing smooth image regions
- Applied the low-pass mask to the FFT image to suppress high-frequency details
- Created a high-pass filter mask to preserve high-frequency components representing edges and fine details
- Applied the high-pass mask to the FFT image to suppress low-frequency components
- Performed inverse FFT to reconstruct spatial-domain images from both low-frequency and high-frequency components
- Displayed and compared the low-frequency (smoothed) and high-frequency (edge-enhanced) images

---

## 🧪 Task 7 – Frequency Domain Filtering (LPF & HPF)

This task focuses on image enhancement and analysis using frequency domain filtering techniques by selectively preserving or suppressing low-frequency and high-frequency components.

### ✔ Operations Performed
- Imported the input image and converted it to grayscale for frequency domain processing
- Computed the 2D Fast Fourier Transform (FFT) of the image and shifted the zero-frequency component to the center
- Designed Ideal Low Pass Filter (LPF) to preserve low-frequency components responsible for smooth regions
- Designed Butterworth Low Pass Filter (LPF) with adjustable order for smooth frequency transition
- Designed Gaussian Low Pass Filter (LPF) for gradual attenuation of high frequencies
- Applied LPF masks in the frequency domain and reconstructed spatial images using Inverse FFT
- Designed Ideal High Pass Filter (HPF) to emphasize edges and fine details
- Designed Butterworth High Pass Filter (HPF) for controlled edge enhancement
- Designed Gaussian High Pass Filter (HPF) to smoothly extract high-frequency components
- Applied HPF masks and reconstructed spatial images using Inverse FFT
- Visually compared the effects of Ideal, Butterworth, and Gaussian filters in both low-pass and high-pass cases
- Performed spatial domain Gaussian filtering and compared its result with frequency domain filtering

---

## 🧪 Task 8 – Image Restoration

This task explores techniques to recover the original content of an image from a degraded or noisy version.


### ✔ Operations Performed
- Noise Injection: Artificially degraded images using Gaussian noise, Salt & Pepper noise, and Motion Blur.
- Filtering & Deconvolution: Applied Median filtering for impulsive noise and Wiener/Inverse filtering to reverse blurring effects.
- Motion Blur Recovery: Specifically restored blurred images by modeling the degradation function.
- Quality Assessment: Computed the Peak Signal-to-Noise Ratio (PSNR) to objectively measure restoration quality.
- Comparative Analysis: Identified the optimal restoration method for each specific degradation type.

---

## 🧪 Task 9 – Color Image Processing

- This task focuses on manipulating color information across different mathematical representations to enhance or segment images.
- 
### ✔ Operations Performed
- Channel Extraction: Separated the Red, Green, and Blue components to analyze individual color contributions.
- Color Space Conversion: Transformed images from RGB to specialized spaces including HSV (Hue/Saturation/Value), YCbCr (Luminance/Chrominance), and CIELAB (Perceptual Uniformity).
- White Balance Correction: Adjusted the color temperature to ensure neutral colors (whites/grays) are rendered accurately.
- Color Masking: Isolated specific objects by defining ranges within the HSV color space.
- Segmentation Comparison: Evaluated which color space provided the highest contrast and most robust segmentation for various objects.

---

## 🧪 Task 10 – Image Compression

This task focuses on reducing image size while maintaining acceptable visual quality using transform-based compression techniques.

### ✔ Operations Performed
- Loaded and preprocessed the grayscale input image for compression
- Applied JPEG-like compression using 8×8 block-based Discrete Cosine Transform (DCT)
- Quantized DCT coefficients using a standard JPEG quantization matrix
- Reconstructed the compressed image using inverse DCT
- Computed performance metrics including Compression Ratio (CR), Mean Squared Error (MSE), Peak Signal-to-Noise Ratio (PSNR), and Rate–Distortion (RD)
- Visually compared the original and compressed images to evaluate compression efficiency

---

## 🧪 Task 11 – Morphological Operations

This task explores the use of morphological techniques to analyze and manipulate the structure of objects in binary images.

### ✔ Operations Performed
- Converted the input image into a binary image suitable for morphology
- Applied erosion and dilation to modify object boundaries
- Performed opening to remove noise and small objects
- Performed closing to fill gaps and connect nearby regions
- Extracted object boundaries using morphological subtraction
- Filled holes in objects using morphological reconstruction
- Removed noise using morphological filtering techniques
- Detected and labeled basic geometric shapes using morphological preprocessing and contour analysis


---

## 🧪 Task 12 – Segmentation Techniques

This task focuses on partitioning an image into meaningful regions by grouping pixels based on intensity, color, and spatial similarity.

### ✔ Operations Performed
- Image Preprocessing: Converted the input image to grayscale and color formats as required for different segmentation techniques.
- Global Thresholding: Applied a fixed threshold value to segment the image into foreground and background regions.
- Local (Otsu’s) Thresholding: Automatically computed an optimal threshold based on image histogram statistics to improve segmentation accuracy.
- Adaptive Thresholding: Performed pixel-wise thresholding using local neighborhood information to handle uneven illumination.
- K-Means Segmentation: Implemented unsupervised clustering-based segmentation with varying cluster sizes (k = 2, 3, and 4) to analyze the effect of cluster count on region separation.
- Mean Shift Segmentation: Applied non-parametric clustering to group pixels based on spatial and color similarity without predefining the number of clusters.
- Visual Comparison: Displayed and compared the results of all segmentation methods to evaluate segmentation quality and region consistency.
- Method Analysis: Discussed the strengths and limitations of threshold-based and clustering-based segmentation techniques.

  ---

  # 🧬 Melanoma Detection Using Dermoscopic Images (PH2 Dataset)

This project presents a **machine learning–based melanoma detection system** developed using **dermoscopic images from the PH2 dataset**.  
The system follows a complete pipeline including **image preprocessing, lesion segmentation, feature extraction, model training, evaluation, and deployment using Streamlit**.

⚠️ **Note:**  
This system is trained **only on PH2 dermoscopic images** and is **not intended for clinical or real-world medical diagnosis**.

---

## 🧪 Task 1 – Lesion Mask Generation

Dermoscopic images are processed to generate accurate binary masks representing lesion regions.

### ✔ Operations Performed
- Loaded original **PH2 dermoscopic images**
- Converted images to **grayscale**
- Applied **Gaussian blurring** for noise reduction
- Used **Otsu’s thresholding** to segment lesions
- Applied **morphological opening and closing** to refine masks
- Generated **binary masks** where:
  - **White region → Lesion area**
  - **Black region → Background / skin**

📁 Output Folder:  
`Generated_Masks/`

---

## 🧪 Task 2 – Image Segmentation (Lesion Isolation)

Using the generated masks, lesion regions are isolated from the original images.

### ✔ Operations Performed
- Applied binary masks to original images
- Retained **only the central lesion region**
- Removed surrounding skin and image edges (set to black)
- Ensured **lesion-only visibility** for accurate feature extraction

📁 Output Folder:  
`Segmented_Images_2/`

---

## 🧪 Task 3 – Feature Extraction

Handcrafted features are extracted from segmented lesion images to form a structured dataset for machine learning.

### ✔ Features Extracted
- **Mean Intensity**
- **Standard Deviation of Intensity**
- **Lesion Area (pixel count)**
- **Mean Red Channel Value**
- **Mean Green Channel Value**
- **Mean Blue Channel Value**
- **Target Label**
  - `1 → Melanoma`
  - `0 → No Melanoma`

📁 Output File:  
`Feature_Extracted_V2.xlsx`

---

## 🧪 Task 4 – Machine Learning Model Training

Two separate machine learning approaches were implemented:

### ✔ Random Forest Classifier
- Trained on extracted features
- Saved as a reusable model file

📦 Model File:  
`RF_Model_V2.joblib`

---

### ✔ K-Fold Cross Validation (k = 5)
- Applied **Stratified K-Fold Cross Validation**
- Evaluated model stability and performance
- Metrics calculated for each fold:
  - Accuracy
  - Sensitivity (Recall)
  - Specificity
- Final model trained on the full dataset and saved separately

📦 Model File:  
`KFold_Model.joblib`

---

## 📊 Evaluation Metrics

The following metrics are used to assess performance:

- **Confusion Matrix**
- **Accuracy**
- **Sensitivity (Recall)** – Critical for melanoma detection
- **Specificity**

These metrics help evaluate both **classification accuracy** and **medical relevance**.

---

## 🖥️ Streamlit Dashboard (Deployment)

A user-friendly **Streamlit web application** is developed to test melanoma prediction on PH2 images.

### ✔ Dashboard Features
- Upload dermoscopic images
- Automatic feature extraction
- Melanoma prediction using trained model
- Confidence score display
- Dataset usage disclaimer

📸 **Streamlit Dashboard Preview:**

![Streamlit Dashboard](img/dashboard.png)

---

## 🚀 How to Run the Streamlit App

1. Clone the repository
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt

