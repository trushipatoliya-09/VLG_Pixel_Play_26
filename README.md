# VLG Pixel Play '26 - Anomaly Detection
**By Trushi Patoliya** | **Final Rank: 19** | **Best Score: 0.26976**

## Project Overview
This project addresses the challenge of identifying abnormal events in corrupted video streams using the Avenue dataset. 

## Technical Methodology
1. **Data Preprocessing:** Resolved format errors by cleaning frame IDs (e.g., converting `01_00939` to `1_939`) to match competition requirements.
2. **Feature Extraction:** Implemented **Temporal Frame Differencing** using OpenCV to identify motion-based anomalies.
3. **Refinement:** Applied **Rolling Window Smoothing** and **Training-Set Calibration** to reduce noise and improve model stability, lifting the score from 0.248 to 0.269.

## How to Run
The included `.ipynb` notebook can be run on Kaggle or locally with OpenCV, Pandas, and NumPy installed.
