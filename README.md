# Personal Protective Equipment (PPE) Detection Repository

This repository contains code and scripts for training and using an object detection model for Personal Protective Equipment (PPE) detection. The model is trained using a dataset provided by roboflow.com.

## Repository Structure

The repository consists of two main parts:

1. Model Training: The `Personal_protective_Equipment_detector.ipynb` file contains code for training the object detection model. The model is trained using the Ultralytics framework and the YOLO (You Only Look Once) algorithm. The training data is sourced from roboflow.com and is stored in the appropriate format.

2. Object Detection: The `PPE_detection.ipynb` file contains code that utilizes the trained model (`ppe.pt`) to detect PPE items such as helmets and masks. The code can be used to process a video stream or a video file to identify and label PPE objects in the image.

## Getting Started

To use this repository, follow these steps:

1. Download the training dataset from roboflow.com: Visit roboflow.com and download a dataset that includes labeled PPE items such as helmets and masks. Make sure the data is in the appropriate format that can be used by the Ultralytics framework.

2. Model Training: Run the `Personal_protective_Equipment_detector.ipynb` script, adjusting the paths to the downloaded training dataset and other training parameters as needed. The script utilizes Ultralytics and the YOLO algorithm to train the object detection model.

3. Object Detection: After training the model, use the `PPE_detection.ipynb` script to detect PPE objects. Adjust the script to process a video stream or a video file according to your requirements and visualize the identified PPE objects.

## Acknowledgements

The dataset used for training the model is sourced from roboflow.com, a platform for computer vision datasets and annotation services.

For more information, refer to the documentation and tutorials provided by Ultralytics and roboflow.com.

