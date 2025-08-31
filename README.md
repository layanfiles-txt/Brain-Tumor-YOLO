Brain Tumor Detection using YOLOv5

Project Overview

This project uses YOLOv5 to detect brain tumors in medical images. The model was trained on a custom dataset and can predict tumors in new images with bounding boxes.


Files in this repository

best.pt → Trained YOLOv5 model weights

data.yaml → Dataset class information

test_model.ipynb → Jupyter notebook for testing images

requirements.txt → Python packages needed

images/ → Sample images for testing


Requirements

Make sure you have Python 3.8+ installed. Install dependencies with:

pip install -r requirements.txt


Dependencies include: torch, opencv-python, matplotlib, ultralytics, etc.


How to Use

Clone this repository:

git clone https://github.com/yourusername/Brain-Tumor-YOLO.git


Open test_model.ipynb in Jupyter Notebook.

Run the cells to load the model and test images.

The model will display images with “Tumor” bounding boxes if detected.

Optional: Replace sample images in images/ with your own medical scans.


Notes

This project contains only one class: Tumor.

Results may vary depending on image quality and tumor size.


References

YOLOv5: https://github.com/ultralytics/yolov5

Dataset source: https://universe.roboflow.com/namdp2810-gmail-com/brain-tumor-1c9z9