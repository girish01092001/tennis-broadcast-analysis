# Tennis Broadcast Analysis

An end-to-end computer vision pipeline for analyzing tennis broadcast videos using court keypoints, player tracking, and ball detection.

## Features

- Court keypoint detection (14 landmarks)
- Player detection and tracking
- Tennis ball detection
- Homography-based court mapping
- Annotated video output
- CSV tracking data export
![id1_id2_court_ball_overlay_raw-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/87edd2e9-38df-45e7-93db-cbf103eeca9f)

## Project Structure
data/ - input video and output CSV
inference/ - main pipeline scripts
training/ - model training code
models/ - trained weights
results/ - output videos

## Outputs

- Annotated video → `results/`
- Tracking CSV → `data/`
