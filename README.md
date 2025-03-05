# Lane Line Detection

## Overview
This project detects lane lines in images and videos using computer vision techniques. It applies edge detection, region masking, and Hough Transform to identify lane lines on the road.

## Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib

## Features
- Detects lane lines in static images
- Works with video input for real-time lane detection
- Uses Canny Edge Detection for feature extraction
- Applies Region of Interest (ROI) masking
- Implements Hough Transform to detect lane lines

## Usage
### Detecting Lanes in an Image
```python
python detect_lanes.py --image test.jpg
```

### Detecting Lanes in a Video
```python
python detect_lanes.py --video test_video.mp4
```

## How It Works
1. Convert the image to grayscale.
2. Apply Gaussian Blur to smooth the image.
3. Use Canny Edge Detection to detect edges.
4. Define a Region of Interest (ROI) to focus on the lane area.
5. Apply Hough Line Transform to detect lane lines.
6. Overlay detected lanes on the original image.

## Contribution
Feel free to fork this repository and submit pull requests for improvements.
