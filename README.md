# 🧠 OpenCV Basics — Learn by Doing 👨‍💻

Welcome to **OpenCV Basics**, a hands-on journey through the foundational concepts of OpenCV, the most powerful computer vision library used by AI engineers, researchers, and developers across the world.

This repository documents my personal experiments, notes, and code samples as I explored and practiced essential OpenCV concepts. It's perfect for anyone who wants to get a practical grip on OpenCV from scratch.

> 📍 [Explore the repo on GitHub →](https://github.com/rusiru-erandaka/Opencv_basics)

---

## 🧐 What is OpenCV?

**OpenCV (Open Source Computer Vision Library)** is an open-source machine learning and computer vision library designed to provide a unified infrastructure for real-time image and video processing. It's written in C/C++ but has bindings for Python, Java, and more.

Common applications of OpenCV include:

- 🔍 Object detection & recognition
- 🖼 Image processing & transformations
- 📸 Real-time face recognition
- 🧮 Feature extraction
- 🎥 Video analysis & motion tracking

---

## 💡 What You’ll Learn from This Repository

This repository includes organized examples and experiments demonstrating the following fundamental OpenCV operations:

| Topic | Description |
|-------|-------------|
| `Image Reading/Writing` | Load, display, and save images using `cv2.imread()`, `cv2.imshow()`, and `cv2.imwrite()` |
| `Image Resizing and Cropping` | Resize images and extract specific parts using slicing |
| `Color Spaces` | Convert between BGR, RGB, and Grayscale using `cv2.cvtColor()` |
| `Drawing Shapes` | Draw lines, rectangles, circles, and put text on images |
| `Image Thresholding` | Understand binary, adaptive, and Otsu thresholding |
| `Blurring and Filtering` | Apply Gaussian Blur, Median Blur, Bilateral Filter, etc. |
| `Edge Detection` | Use Sobel, Laplacian, and Canny edge detectors |
| `Contours and Bounding Boxes` | Detect and draw contours, find object boundaries |
| `Video Capture` | Read and process frames from a webcam or video file |
| `Mouse Events` | Interact with image windows via mouse callbacks |

---

## ⚙️ Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy (for matrix operations, if needed)

You can install the required dependencies via:


```bash
pip install opencv-python numpy
```

##  🚀 Running the Code

### Clone this repository:
 ```bash
git clone https://github.com/rusiru-erandaka/Opencv_basics.git
cd Opencv_basics
```

### Open any script in your preferred IDE or run directly using:

```bash
python script_name.py
```

## 🧠 Key OpenCV Concepts (Crash Summary)

### 📘 BGR vs RGB

OpenCV loads images in BGR (Blue-Green-Red) format, not RGB. Be cautious when displaying or converting images.

### 🔄 Color Conversions

```bash
gray = cv2.cvtColor(img, cv2.COLOR_BGR2GRAY)
```

### 📏 Resize, Crop

```bash
resized = cv2.resize(img, (width, height))
cropped = img[y1:y2, x1:x2]
```

### 🧱 Drawing Shapes

```bash
cv2.rectangle(img, (x1, y1), (x2, y2), color=(255, 0, 0), thickness=2)
```

## 🙌 Contributions

This repository is for self-learning, but feel free to fork and extend it with your own experiments! Good Luck.




