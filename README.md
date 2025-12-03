# Advanced Image Processing Techniques in Python

![Python](https://img.shields.io/badge/python-3.11-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-completed-brightgreen)

---

## **Overview**
This project demonstrates several fundamental **image processing techniques** using Python. It covers:  

- Image zooming (zoom in & zoom out with custom bilinear interpolation)
- Logarithmic and Power-Law (Gamma) transformations for grayscale images
- Intensity level quantization
- Region-based histogram equalization for contrast enhancement

The project uses Python libraries such as **Pillow**, **OpenCV**, **NumPy**, and **Matplotlib**. It serves as a practical reference for understanding image enhancement, resizing, and pixel-level manipulations.

---

## **Features**
- Zoom images in and out while preserving image quality
- Apply log transformation to enhance dark regions
- Apply power-law (gamma) transformation for brightness adjustments
- Reduce grayscale intensity levels using quantization
- Apply histogram equalization to specific regions (ROI) of an image
- Interactive ROI selection for local image enhancement (Task 4)

---

## **Tasks Overview**

### **Task 1: Image Zoom In and Zoom Out**
- Resize images using custom bilinear interpolation
- Zoom out an image by reducing its DPI
- Zoom back to original size
- Libraries: Pillow, Matplotlib  

### **Task 2: Log Transformation and Power-Law (Gamma) Transformation**
- Enhance grayscale images using pixel intensity transformations
  - **Log Transformation:** Expands darker pixel values
  - **Power-Law Transformation:** Adjusts brightness using gamma correction
- Libraries: OpenCV, NumPy, Matplotlib

### **Task 3: Reducing Intensity Levels (Quantization)**
- Reduce the number of grayscale intensity levels to simplify or compress images
- Input: Desired number of intensity levels (must be a power of 2)
- Libraries: OpenCV, NumPy, Matplotlib

### **Task 4: Region-Based Histogram Equalization**
- Improve local contrast by applying histogram equalization to a selected region (ROI)
- Interactive mouse-driven ROI selection (best on local machines, e.g., VS Code)
- Libraries: OpenCV, NumPy, Matplotlib


---

## **Installation & Setup**
1. Clone the repository:
2. Installation:
```bash
git clone <your-repo-url>
pip install pillow opencv-python matplotlib numpy


