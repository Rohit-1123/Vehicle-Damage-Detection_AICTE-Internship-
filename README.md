

 Vehicle Damage Detection
=================================

### Using Mask R-CNN (Detectron2)

This project implements an AI-based solution for detecting **vehicle body damage** such as dents, scratches, cracks, and other irregular deformities. It uses **Mask R-CNN** (via the Detectron2 framework by Facebook AI Research) to perform:

-   Object Detection
-   Instance Segmentation
-   Damage Localization
-   Damage Highlighting using Masks + Bounding Boxes

- - -

 Technologies Used
--------------------

-   Detectron2 (Mask R-CNN)
-   Python 3.x
-   OpenCV
-   NumPy
-   Pillow (PIL)
-   Matplotlib
-   Google Colab or Linux environment (recommended)

- - -

Getting Started
------------------

### Clone the Repository

cd Vehicle-Damage-Detection

- - -

Detectron2 Installation Notice
---------------------------------

Detectron2 **does not support Windows natively**.

### Recommended — Google Colab

Detectron2 installs easily and provides GPU support.

- - -

Install Other Dependencies
-----------------------------

pip install opencv-python numpy pillow matplotlib tqdm jupyter

- - -

Run the Notebook
-------------------

Launch:

jupyter notebook

Then open:

Vehicle\_damage\_detection.ipynb

- - -

Notebook Features
--------------------

-   Dataset visualization
-   Full Detectron2 configuration
-   Mask R-CNN training pipeline
-   Validation & metrics
-   Image-by-image detection
-   Segmentation mask overlay
-   Saving model + predictions

- - -

Model Architecture
---------------------

This project uses:

-   **Mask R-CNN**
-   **ResNet-50 Backbone**
-   **Feature Pyramid Network (FPN)**

Optimized for segmenting irregular damage shapes such as dents, scratches, and cracks.

- - -

Custom Script — custom.py
----------------------------

This file handles:

-   Dataset registration
-   Data transformations & augmentations
-   Visualization utilities for masks + bounding boxes
-   Prediction helper functions
-   Custom training logic

- - -


Output Example
-----------------

The model produces:

-   Segmentation masks over damaged areas
-   Bounding boxes
-   Class labels
-   Confidence scores


- - -

📝 Future Improvements
----------------------

-   Add **YOLOv8** version for faster inference
-   Implement **real-time webcam damage detection**
-   Convert model to **ONNX / TensorRT**
-   Add **damage severity classification**
-   Build a **desktop app** (Tkinter) or **web app** (Flask/Streamlit)

- - -

