<img width="1361" height="411" alt="Screenshot 2025-07-23 155541" src="https://github.com/user-attachments/assets/0b9e8f1a-249e-4ba4-8b92-c054aac9e1fa" />
# Background Subtraction – Digital Image Processing

This project implements and compares various background subtraction techniques for motion detection in video sequences or image streams. These methods help detect moving objects by separating the dynamic foreground from the static background.

# Implemented Techniques

1. *Simple Gaussian:
   - Assumes each pixel intensity follows a Gaussian distribution.
   - A pixel is considered foreground if it deviates significantly from the estimated mean.

2. *Gaussian Mixture Model (GMM):
   - Models each pixel with multiple Gaussian distributions.
   - Adapts well to dynamic scenes (e.g., waving trees, lighting changes).

3. *Mean Filter:
   - Uses the average of past frames to estimate the background.
   - Foreground is detected when the difference exceeds a threshold.

4. *Median Filter:
   - Computes the median of past pixel values for a stable background.
   - Effective against noise and repetitive background motion.

5. *Approximate Median Filter:
   - Faster alternative to exact median.
   - Incrementally updates the background estimate pixel-wise.

# Requirements

- Python 3.x
- OpenCV
- NumPy
  
 # How to Run
 
1. Clone the repository
2. install libraries
3. python filename.py
 
