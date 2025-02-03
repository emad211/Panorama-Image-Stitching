# Panorama Image Stitching using SIFT & Multi-band Blending 🌄🖼️

## 📌 Introduction
This project implements **image stitching** using **SIFT feature matching, homography transformation, and multi-band blending**. The goal is to merge multiple images into a seamless panorama using advanced computer vision techniques.

## 🚀 Features
- **Feature Extraction & Matching**:
  - Using **SIFT (Scale-Invariant Feature Transform)** to detect keypoints.
  - Applying **Brute-Force Matcher (BFMatcher)** for feature matching.
  - Computing **Homography Matrix** to align overlapping images.
- **Blending Techniques**:
  - **Simple Blending** with `cv2.addWeighted`.
  - **Mask-based Blending** for seamless merging.
  - **Multi-band Blending** using **Gaussian & Laplacian Pyramids**.
- **Panorama Reconstruction**:
  - Warping images with **cv2.warpPerspective**.
  - Combining **Left, Middle, and Right** images into one panorama.

## 📂 Project Structure
```
📦 Panorama-Image-Stitching
├── 📜 machine_vision.ipynb   # Jupyter Notebook with full implementation
├── 📜 Left.jpg               # Left image
├── 📜 Middle.jpg             # Middle image
├── 📜 Right.jpg              # Right image
├── 📜 README.md              # Project documentation
```

## 🛠️ Installation
Ensure you have Python installed, then install the required dependencies using:
```bash
pip install opencv-python numpy matplotlib
```

## 📌 How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook machine_vision.ipynb
   ```
2. Run all cells sequentially to execute feature detection, homography computation, and panorama blending.

## 📊 Results Analysis
- **Feature Matching Visualization**: Checking SIFT keypoints.
- **Homography Estimation**: Evaluating image alignment.
- **Final Panorama**: Merging Left, Middle, and Right images.

## 📧 Contact
For any inquiries or collaboration opportunities, reach out to:
📩 Email: emad.k50000@gmail.com

## ⭐ Contribute
Feel free to fork this repository, report issues, or submit pull requests to improve the project.

🔹 **Developed by Emad K | Open Source & Research-Oriented**

