# Gaze Tracker Project for DRDO 👁✨

## Overview 📄

This repository contains the comprehensive codebase and models developed during my internship at DRDO for a gaze-tracking system. The project centers on tracking gaze direction and analyzing eye movements using a variety of methodologies, including raw data collection, preprocessing, and model training. The repository also includes supporting scripts for visualization and prediction.

**Important Note:** This repository only includes the code and model files. The dataset used for training the models is **NOT INCLUDED** due to specific reasons, including privacy and confidentiality concerns.

---

## Repository Contents 📂

### Raw Data Collection Code:

- The script (Eye_Tracker_Recording.py) records eye-tracking data using webcam or dedicated eye-tracking hardware.

- Captures real-time gaze data and saves it in a structured format.

###  Data Preprocessing Code:

- Scripts for cleaning, normalizing, and preparing the collected data for model training.

- Includes handling missing data, feature scaling, and augmentation techniques.

### Model Architectures:

- Contains multiple deep learning models in the following files:

  1. `Model3.keras`

  2. `Model4.keras`

  3. `Model5s.keras`

- After rigorous testing, Model4.keras was identified as the most effective model for this task.

### Grid Paradigm Visualization:

- Code to generate JPEGs representing the grid paradigm used in experiments, aiding in data interpretation and model input generation.

### Model Prediction Code:

- Main script (Gaze_Tracker_Prediction.py) for running the trained models on test data.

- Outputs the predicted gaze direction and visualizations for better understanding.

### Markdown-Annotated Code:

- Several scripts include Markdown annotations that describe individual methods.

- Users can review these annotations to identify and test the methods that best suit their needs.

## How to Use the Repository 🛠️

### Input Requirements:

- Eye-Tracking Data: Captured using the Eye_Tracker_Recording.py script or imported from compatible datasets.

- Grid Paradigm JPEGs: If applicable, these are used to represent spatial positions for gaze tracking.

### Output:

- The models predict the gaze direction and other relevant metrics based on the processed inputs.

### Running the Prediction Pipeline:

- Collect raw data using Eye_Tracker_Recording.py.

- Preprocess the collected data using the preprocessing scripts provided.

- Load one of the trained models (recommended: Model4.keras).

- Run the Gaze_Tracker_Prediction.py script to obtain predictions.

## Key Features ✨

-Supports both webcam-based and hardware-assisted gaze tracking.

- Annotated scripts for easy understanding and customization.

- Includes multiple pre-trained models with varying performance characteristics.

- Real-time prediction capability with visual feedback.

---

## Disclaimer ⚠️

- The dataset included in this repository is provided strictly for research purposes. Ensure compliance with all ethical and legal guidelines before use.

- The models and code are provided "as-is" and may require fine-tuning for specific applications.

## Acknowledgments 🙏

- I am grateful to DRDO for the opportunity to work on this project. Special thanks to my mentors and colleagues for their guidance and support throughout the internship.
- I am also grate to the authors of https://www.mdpi.com/2076-3417/11/19/9068. This repo contains the ocde to implement this paper.
  
License

This project is licensed under the MIT License. See the LICENSE file for details.

