# Tennis Broadcast Analysis

This repository contains the implementation of a deep learning pipeline for automated tennis broadcast analysis.

## Pipeline Components

1. Player detection and tracking using YOLO and ByteTrack
2. Tennis court localization using a 14-keypoint pose model
3. Ball detection with spatial filtering
4. Fusion of player, court, and ball coordinates into frame-level data
5. Overlay visualization generation

## Repository Structure

- training/ : model training scripts
- inference/ : full pipeline inference code
- models/ : trained model weights
- data/ : sample input video and CSV output
- results/ : overlay visualization results
- docs/ : supporting figures and notes

## Note

This repository supports reproducibility for the associated MDPI paper submission.
