## Dustbin Detection using YOLOv8

### Overview
This project focuses on implementing YOLOv8, a state-of-the-art object detection model, to detect dustbins within images. The model is trained on a custom dataset created with the LabelImg tool, ensuring accurate labeling for precise detection.

### Requirements
- Python 3.x
- PyTorch
- OpenCV
- LabelImg
- YOLOv8 implementation (e.g., Darknet or a PyTorch implementation)

### Installation
1. Install Python 3.x.
2. Install required libraries: PyTorch, OpenCV.
3. Install LabelImg for dataset labeling.
4. Obtain or implement YOLOv8 model for object detection.

### Dataset Preparation
1. Collect a diverse dataset of images containing dustbins.
2. Label each dustbin within the images using LabelImg, ensuring accurate bounding box annotations.

### Model Training
1. Split the labeled dataset into training and validation sets.
2. Train the YOLOv8 model using the labeled dataset, adjusting hyperparameters as necessary.
3. Validate the trained model on the validation set to ensure accuracy and generalization.

### Inference
1. Utilize the trained YOLOv8 model to perform inference on new images.
2. Process images through the model to detect dustbins, obtaining their coordinates.

### Usage
1. Provide the input image to the trained model.
2. Receive the output with detected dustbin coordinates.

### Credits
- YOLOv8: [YOLO: Real-Time Object Detection](https://pjreddie.com/darknet/yolo/)
- LabelImg: [LabelImg Tool](https://github.com/tzutalin/labelImg)
