# PPE-Violation-Detection
## Overview
This project is a comprehensive Personal Protective Equipment (PPE) detection system designed to enhance workplace safety compliance. The system leverages advanced machine learning techniques and modern software development practices to provide real-time PPE detection and alerting.

## Features
- **Dataset**: Utilizes a dataset of 10,000 annotated images curated through Roboflow.
- **Model**: Trained using YOLOv7, optimized with NVIDIA DGX A100 for accelerated processing.
- **Alert System**: Integrated with Gmail API via Google Cloud to notify users of non-compliance.
- **Real-time Detection**: Capable of detecting PPE in real-time from video feeds.
- **Containerization**: The entire project is containerized using Docker and deployed on an NVIDIA DGX A100.
- **Frontend**: A minimalist Flask frontend for easy monitoring of detection processes.

## Installation

### Prerequisites
- Docker
- NVIDIA Docker Toolkit
- Python 3.8+
- Flask
- YOLOv7 dependencies
- Google Cloud credentials for Gmail API

### Clone the Repository
```bash
https://github.com/SAM8402/PPE-Violation-Detection
cd PPE-Violation-Detection
```
### Install Python Dependencies
```bash
pip install -r requirements.txt
```
### Run the Application
```bash
python app.py
```
### Usage
- Real-time Detection
- Connect your video feed to the system.
- Access the Flask frontend at http://localhost:5000 to monitor detection in real-time.

### Alert System
- Ensure your Google Cloud credentials are properly set up to enable email notifications for non-compliance. The system will automatically send alerts to designated users.

### Acknowledgements
- Roboflow for the dataset curation tools.
- NVIDIA for providing the DGX A100.
- Google Cloud for the Gmail API.
