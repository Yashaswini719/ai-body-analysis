# AI Body Analysis API

An AI-powered body analysis API that detects human pose landmarks from an image and calculates relative body proportions using MediaPipe, OpenCV, and FastAPI.

## 🚀 Features

- Image upload
- Human pose detection
- 33 MediaPipe pose landmarks
- Landmark coordinate extraction
- Body proportion calculation
- FastAPI REST API
- JSON responses
- Image validation
- File-size validation
- Image-dimension validation
- Error handling
- Swagger/OpenAPI documentation
- Postman API collection

## 🔄 AI Pipeline

```text
User Image
    ↓
OpenCV
    ↓
MediaPipe Pose Detection
    ↓
33 Pose Landmarks
    ↓
Body Proportion Calculation
    ↓
FastAPI
    ↓
JSON Response