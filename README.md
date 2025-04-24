# AutomaticNumberPlateDetection
This project demonstrates an end-to-end solution for Automatic Number Plate Detection (ANPD), a computer vision task aimed at detecting and extracting vehicle license plates from video footage. The solution is designed to work on real-time video footage.

## Project Overview

The project was implemented in two ways:

- **Google Colab Pro** – for model development and quick prototyping.
- **Amazon Web Services (AWS)** – for a scalable cloud-based deployment pipeline.

---

## Tech Stack

### Development Environments:
- **Google Colab Pro**: Used for initial experimentation, model training, and visualizations.
- **Jupyter Notebook**: `.ipynb` format used for structured development and easy visualization.

### Cloud Deployment:
- **AWS S3**: Storage for raw video inputs and model outputs.
- **AWS SageMaker**: Model training and inference at scale.
- **AWS IAM**: Handles permissions and security.
- **AWS CloudWatch**: For logging and monitoring.
- **AWS DynamoDB / RDS**: Optional for storing metadata and processed results.

### AI / ML:
- **YOLOv8**: Pretrained model for object detection, fine-tuned for number plate localization.
- **OpenCV**: For image preprocessing, video frame manipulation, and post-processing.
- **PyTorch**: Model architecture and training framework.
