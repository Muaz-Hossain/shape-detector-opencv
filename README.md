# Real-Time Shape Detection using OpenCV

##  My Learning Journey Project

This isn't just another computer vision tutorial. This is my **hands-on journey** of building a real-time shape detection system from scratch. As someone learning OpenCV, I wanted to understand how shape detection actually works in practice.

## Why I Built This

I was tired of tutorials that show perfect results. I wanted to:
- Actually implement real-time video processing
- Understand why contours behave unpredictably
- Solve the challenge of classifying different shapes
- Build something that works with real video input

##  What It Does

A computer vision system that detects and classifies geometric shapes in real-time video:
- **Input**: Video feed (webcam or video file)
- **Processing**: Real-time at 29 FPS for 1080p video
- **Output**: Video with shapes marked (bounding boxes, labels, measurements)
- **Shapes detected**: Triangle, Square, Rectangle, Circle, Oval

##  The Technical Challenge

### What Made This Hard:
1. Contours are noisy - Getting 50+ contours when you only want shapes
2. Real-time processing - Making it fast enough for smooth video
3. Shape classification- Differentiating between similar shapes (square vs rectangle)
4. Parameter tuning - Finding the right thresholds for different lighting

### The "FINAL" Moments:
- When I finally understood `approxPolyDP` and how it simplifies contours
- When real-time processing actually worked without lag
- When the system correctly identified different shapes
- When I could explain the entire pipeline to myself


