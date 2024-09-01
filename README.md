# Waste Detection System with YOLOv5

## Objective

The objective of this project was to develop an advanced waste detection system leveraging YOLOv5, a state-of-the-art object detection algorithm, to classify and identify waste materials across 13 distinct classes. The system aims to facilitate automated waste management by accurately detecting and categorizing various types of waste materials in images.

## Approach

1. **Image Annotation and Data Preparation:**
   - Utilized Python-based image annotation tools to label images with relevant waste material classes.
   - Developed a pipeline for automating data ingestion and validation to streamline the dataset preparation process.

2. **Model Training:**
   - Implemented YOLOv5 for object detection, configuring the model to handle the 13 material classes.
   - Trained the YOLOv5 model with the annotated dataset to achieve high accuracy in waste classification.

3. **System Development:**
   - Created a Flask-based application to handle image upload, model training, and live predictions.
   - Built and integrated a continuous integration and continuous deployment (CI/CD) pipeline using GitHub Actions to ensure smooth updates and deployments.

4. **Deployment:**
   - Dockerized the FastAPI application for consistent and scalable deployment.
   - Deployed the application on AWS using EC2, ECR, and IAM to provide robust, scalable production services.

## Results

- **Model Performance:**
  - Achieved a mean Average Precision (mAP) of 94.8% at IoU=0.50 (mAP50).
  - Achieved a mean Average Precision (mAP) of 78.2% at IoU=0.50:0.95 (mAP50-95) across the 13 waste material classes.

- **System Deployment:**
  - Successfully deployed a scalable, Dockerized FastAPI application on AWS, ensuring reliable performance in a production environment.

This project demonstrates a comprehensive approach to solving waste classification challenges using modern computer vision techniques and scalable deployment practices.
