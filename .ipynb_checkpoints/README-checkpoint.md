# OpenCV Basics – Image Processing Fundamentals

This repository contains a Jupyter Notebook exploring the **fundamental concepts of image processing using OpenCV**.  
It is intended as a **learning-oriented project** covering core techniques such as color spaces, filtering, thresholding, histograms, and edge detection.

---

## 📌 Objectives

- Understand how digital images are represented and processed
- Learn basic OpenCV functions through hands-on examples
- Visualize the effect of different image processing techniques
- Build a strong foundation for advanced computer vision tasks

---

## 🛠️ Tools & Libraries Used

- **Python**
- **OpenCV (cv2)**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 📂 Repository Contents

- `openCV_basics.ipynb`  
  Main notebook containing explanations, code, and visual results.

- Sample images (`.jpg`, `.png`)  
  Used for demonstrating different OpenCV operations.

- `.gitignore`  
  Ignores auto-generated and unnecessary files.

---

## 📘 Topics Covered

### 1️⃣ Image Loading & Display
- Reading images using `cv2.imread()`
- Displaying images using OpenCV and Matplotlib
- Understanding BGR vs RGB formats

---

### 2️⃣ Color Space Conversions
- RGB
- Grayscale
- HSV
- LAB
- YCrCb
- Adding and removing alpha channels

Functions used:
- `cv2.cvtColor()`

---

### 3️⃣ Image Filtering & Smoothing
- Box Filter (Average Blur)
- Gaussian Blur
- Median Blur
- Bilateral Filter (edge-preserving)

Functions used:
- `cv2.boxFilter()`
- `cv2.GaussianBlur()`
- `cv2.medianBlur()`
- `cv2.bilateralFilter()`

---

### 4️⃣ Thresholding Techniques
- Global Thresholding
- Otsu’s Thresholding
- Adaptive Thresholding
  - Mean
  - Gaussian

Functions used:
- `cv2.threshold()`
- `cv2.adaptiveThreshold()`

---

### 5️⃣ Edge Detection
- Concept of edges as object boundaries
- Canny Edge Detection algorithm
- Effect of threshold values on detected edges

Function used:
- `cv2.Canny()`

---

### 6️⃣ Histograms
- Grayscale histograms
- RGB color histograms
- Understanding intensity distribution

Functions used:
- `cv2.calcHist()`
- `matplotlib.pyplot`

---

## 🧠 Key Learnings

- Different color spaces serve different purposes in image processing
- Filtering helps reduce noise but affects edges differently
- Thresholding converts images into binary representations
- Adaptive methods handle uneven illumination better
- Canny edge detection provides thin and continuous edges
- Histograms help analyze brightness, contrast, and color composition

