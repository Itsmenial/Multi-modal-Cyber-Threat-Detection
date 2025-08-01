# Multimodal Cyber Threat Detection System

## Overview
A machine learning-based system for detecting cyber threats using multiple modalities including image analysis and URL classification.

## Installation
\\\ash
pip install -r requirements.txt
\\\

## Setup
1. Download required model files from [Releases](link-to-releases)
2. Place models in appropriate directories:
   - \image_malware_detection/main/models/\
   - \suspicious_url_detection/models/\
   - \Backend/\

## Usage
### Image Malware Detection
\\\ash
cd image_malware_detection/main
python image_train_enhanced.py
python image_prediction_enhanced.py --image test.png
\\\

### URL Threat Detection
\\\ash
cd suspicious_url_detection
python predict.py --url "example.com"
\\\

## Model Files Required
- \image_isolation_model.pkl\ - Image malware detection model
- \url_threat_model.pkl\ - URL classification model
- Training datasets (see Releases)

## Download Models
Download pre-trained models from the [Releases](link-to-releases) page.
