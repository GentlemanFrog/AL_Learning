# Plant Stress Detection — Project README

## Problem Statement

Detect early symptoms of metal toxicity in aquatic plants using computer vision. The goal is to identify stress responses before they become visible to the human eye, enabling faster intervention in contaminated water environments.

## Approach

1. **Image Collection:** Standardized microscopy images of plants grown in metal-contaminated water
2. **Object Detection:** YOLO/RF-DETR to detect fronds and leaflets
3. **SAHI:** Slice large images into patches to detect small objects
4. **Segmentation:** Measure plant size and growth over time
5. **Colorimetric Analysis:** Extract color features as stress indicators
6. **Time-Series Analysis:** Track changes across image collections
7. **VLM/LLM Integration:** Automated anomaly description (future work)

## Current Status

- [ ] Data collection and standardization
- [ ] Object detection model training
- [ ] SAHI implementation
- [ ] Segmentation pipeline
- [ ] Colorimetric analysis
- [ ] Time-series analysis
- [ ] Dashboard visualization
- [ ] VLM/LLM integration

## Data

*Data collection in progress. Images are being standardized and organized.*

## Results

*Results will be documented here as the project progresses.*

## Tech Stack

- Python, PyTorch, YOLO, SAHI
- OpenCV, Albumentations
- Streamlit (dashboard)
- MLflow (experiment tracking)
