# Forensic Vision Suite 🕵️‍♂️🦴

Inspired by forensic investigation series like *Bones*, this project explores the intersection of **Computer Vision** and **Forensic Science**. As a Data Science student primarily focused on NLP, I am building this suite to master image processing and deep learning.

## 🚀 Level 1: Geometric & Morphological Analysis
The first phase focuses on "Hard Science" — using mathematical computer vision to extract precise data from raw images.

### Key Features:
*   **Perspective Rectification:** Corrects camera lens distortion and angled shots to "flatten" evidence (footprints, tire tracks) for accurate analysis.
*   **Automated Measurement:** Uses Otsu’s Thresholding and Contour Analysis to calculate the physical dimensions (Length/Width) of evidence automatically.
*   **Forensic Filtering:** Implements HSV color-space masking to isolate specific traces (like crime scene tape or biological evidence) from noisy backgrounds.
*   **Morphological Cleaning:** Uses Erode/Dilate operations to remove digital noise from evidence masks.

### Tech Stack:
*   **Python**
*   **OpenCV** (Image Processing)
*   **NumPy** (Matrix Math)

### Sample Output:
| Original Evidence | Processed & Measured |
|---|---|
| ![Original](data/footprint.jpg) | ![Result](outputs/measured_footprint.jpg) |

---
## 📈 Roadmap
- [x] **Level 1:** Basics, Geometry, and Measurement.
