OpenCV Basics Guide

Welcome to the OpenCV Basics Guide! This repository provides a structured and beginner-friendly path to learn computer vision using OpenCV with Python.

📚 Table of Contents

Introduction to OpenCV

Image Processing

Drawing and Geometries

Video Processing

Color Spaces

Object Detection

Mini Projects

Resources and Cheatsheets

Setup Instructions

1. Introduction to OpenCV

📌 Topics Covered:

What is OpenCV?

Installing OpenCV

Reading and displaying images

Basic image properties (shape, dtype, size)

Saving images

📄 Files:

basic_operations.py: How to read, display, and save an image.

2. Image Processing

📌 Topics Covered:

Converting images to grayscale

Blurring (Gaussian, median, bilateral)

Edge detection (Canny)

Morphological operations (dilation, erosion, opening, closing)

📄 Files:

grayscale_blur_edges.py

morphology.py

3. Drawing and Geometries

📌 Topics Covered:

Drawing shapes (lines, rectangles, circles)

Adding text on images

Mouse events (e.g., drawing with mouse)

📄 Files:

shapes_text.py

mouse_events.py

4. Video Processing

📌 Topics Covered:

Reading video streams (webcam, video files)

Writing video to file

Frame-by-frame processing

📄 Files:

webcam_read.py

video_record.py

5. Color Spaces

📌 Topics Covered:

BGR to RGB conversion

HSV color space

Color masking and object segmentation

📄 Files:

hsv_conversion.py

masking_colors.py

6. Object Detection

📌 Topics Covered:

Contour detection and bounding boxes

Face detection using Haar Cascades

Motion detection using frame differencing

📄 Files:

contour_detection.py

face_detection_haar.py

motion_detection.py

7. Mini Projects

📌 Projects:

Virtual Paint App: Track color markers and draw on screen.

Face Blur: Detect and blur faces in live video.

Basic Object Tracking: Track a colored object in video stream.

📄 Files:

virtual_paint.py

face_blur.py

basic_tracking.py

8. Resources and Cheatsheets

✅ Cheatsheets Include:

OpenCV functions quick reference

HSV color ranges for masking

Morphological operations guide

📄 Files:

reference_links.md

cheatsheets/ folder (to be filled with useful PDFs/images)

9. Setup Instructions

✅ Step-by-Step:

Clone this repository:

git clone https://github.com/your-username/opencv-basics-guide.git
cd opencv-basics-guide

Create and activate a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install required packages:

pip install -r requirements.txt

Run a script:

python 01_Introduction_to_OpenCV/basic_operations.py


