

# Palm Movement Detection using Optical Flow

## Overview

This project detects the movement direction of a person's palm using
dense Optical Flow.

The system identifies four possible movement directions:

- Right
- Left
- Up
- Down

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

## Approach

1. Read consecutive video frames.
2. Convert frames to grayscale.
3. Calculate dense optical flow using Farneback's method.
4. Convert optical flow vectors into magnitude and direction.
5. Remove small movements using a magnitude threshold.
6. Create histograms of movement directions.
7. Identify the dominant direction.
8. Process the complete video to detect palm movements.

## Results

The optical-flow direction histograms are used to identify whether
the palm is moving:

- RIGHT
- LEFT
- UP
- DOWN

## Project Structure

```text
Palm_Movement_Optical_Flow/
│
├── Palm_Movement_Optical_Flow.ipynb
├── README.md
└── palm-movement.mp4
