# Automated Visual Inspection Dataset Pipeline (UR10e + Calibrated 2D Camera)

This repository accompanies my Master’s thesis work on automating image dataset generation and label creation for industrial visual inspection. The system uses a UR10e robot and a calibrated 2D camera to capture multi-view images and generate consistent training data without manual annotation.

## What it does (high level)
- Robot-guided multi-view image capture of components in a defined workspace
- Camera intrinsic calibration and hand–eye calibration (camera ↔ robot)
- Frame transformations and 2D projection for automated label generation
- Dataset export (e.g., YOLO/COCO-ready structure) + visual verification overlays

## Tech stack
- Python, OpenCV, NumPy
- UR robot pose capture (RTDE)
- Camera calibration + hand–eye calibration workflow

## Status
Code is currently being cleaned up and documented as part of thesis completion and internal review.  
**I will publish a runnable version after the thesis is submitted and the repository is refactored for public release.**

In the meantime, I can share:
- A short demo video / screenshots of the pipeline output (overlays, capture setup)
- A technical walkthrough of the architecture and calibration workflow upon request

## Notes
Some components may remain private depending on third-party or institute constraints.
