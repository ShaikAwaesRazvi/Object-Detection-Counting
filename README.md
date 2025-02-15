## YOLOv8 Object Detection Project
This project demonstrates the training and deployment of a YOLOv8 model for detecting and counting cell phones and persons in real-time video streams. The project utilizes the YOLOv8 model for object detection and the Deep SORT algorithm for tracking objects.

## Features:
- **Object Detection and Counting:** Counts cell phones and people in real-time from live video feeds.
- **Tracking Integration:** Optimized detection with tracking to ensure high accuracy.
- **Dynamic Environment Handling:** Capable of detecting and counting multiple objects in dynamic environments.
- **High Precision and Recall:** Achieved a precision of 0.9095 and a recall of 0.8380, using data augmentation for better performance.

## Installation
To set up the environment and install the necessary dependencies, follow these steps:

1. Clone the repository:

git clone https://github.com/Dineshkumarmjb/CV-final-project.git
cd CV-final-project


2. Create and activate a virtual environment:

python3 -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install the required dependencies:

pip install -r requirements.txt

## Usage

## Training
To train the YOLOv8 model, ensure your dataset is properly formatted and the data.yaml file is correctly set up. Then, run the training script provided in the repository.

## Testing
To test the trained YOLOv8 model and perform object detection and tracking in real-time video streams, run the testing script provided in the repository.
