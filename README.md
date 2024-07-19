# Signature Detection and Verification on Documents Using YOLOv5 and VGG16

## Overview

This project aims to detect and verify signatures on scanned documents using the YOLOv5 object detection model and the VGG16 deep learning model. The process involves collecting and labeling a tobacco dataset for detection and using a Kaggle dataset for verification, training the models, and evaluating their performance to achieve accurate real-time signature detection and verification.

- **Real-time Detection**: Utilizes YOLOv5 for efficient and accurate signature detection.
- **Signature Verification**: Employs VGG16 for verifying detected signatures.

## Setup Instructions

### Prerequisites

- Python 3.8 or later
- Git
- Jupyter Notebook or JupyterLab or Google Colab

### Installation

1. **Clone the Repository**

    ```sh
    git clone https://github.com/your-username/signature-detection-yolov5.git
    cd signature-detection-yolov5
    ```

2. **Install Dependencies**

    ```sh
    pip install -r requirements.txt
    ```

### Usage

- #### YOLOv5 - Signature Detection:

1. **Add YOLO formatted tobacco dataset to Yolov5 folder**
   - I took it from [here](https://drive.google.com/drive/folders/1ttDGq_T2dprXJl0Y1lQP1ys64c0_a_hU) 

3. **Add YAML in Yolov5 folder**

4. **Edit given train.py in lines 499 and 503 to add your drive path**

5. **Run code and make sure to edit paths as per your requirements**


- #### VGG16 - Signature Verification:

1. **Add Kaggle Dataset for Signature Verification**
    - I used [this](https://www.kaggle.com/datasets/robinreni/signature-verification-dataset) dataset

2. **Train VGG16 Model using provided notebook**

- #### Use the test and verify notebooks to execute detection and verification

### Results

- **YOLOv5 Model**: Successfully detected signatures with high accuracy, enhancing document processing efficiency.
- **VGG16 Model**: Achieved reliable verification of signatures, providing high confidence in matching signatures.
