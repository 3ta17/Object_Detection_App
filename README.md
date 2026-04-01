# Azure Computer Vision Object Detection App

## Overview
This project is a Python-based web application that uses the Azure Computer Vision API to detect objects and extract tags from uploaded images.  
The application is built with Streamlit and allows users to upload an image, visualize detected objects with bounding boxes, and display descriptive tags.

---

## Features
- Upload an image via a web interface
- Detect objects using Azure Computer Vision API
- Draw bounding boxes with labels on detected objects
- Extract and display image tags
- Simple and interactive UI using Streamlit

---

## Technologies Used
- Python
- Streamlit
- Azure Computer Vision API
- Pillow (PIL)
- REST API integration

---

## How It Works
1. User uploads an image through the Streamlit interface
2. The image is sent to Azure Computer Vision API
3. The API returns:
   - Detected objects with coordinates
   - Image tags
4. The app:
   - Draws bounding boxes around detected objects
   - Displays object labels
   - Shows extracted tags below the image

---

## Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/object-detection-app.git
cd object-detection-app
