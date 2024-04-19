# YOLOv8_FigmaWebPage_Detector

This repository implements a Figma Web Page Detection model utilizing the YOLOv8 architecture. The model is designed to detect and localize web page elements within images.

**Dataset**

The dataset used for training and evaluation comprises three result images. Each image underwent annotation using the Computer Vision Annotation Tool (CVAT) software to mark relevant web page elements. These annotated images serve as the groundwork for training the YOLOv8 model.

**Annotation Conversion**

The annotated images were converted to the YOLOv1.1 format for compatibility with the YOLOv8 architecture. This conversion process ensures seamless integration of the annotated data with the chosen object detection framework.

**Configuration File (.yaml)**

A configuration file in the YAML format was crafted to specify the model architecture, hyperparameters, and dataset configurations. This file serves as a blueprint for training and deploying the YOLOv8 model for web page detection tasks.

**Model Deployment**

The YOLOv8 model, configured with the provided YAML file, is deployed using Ultralytics, a comprehensive deep learning library. Ultralytics facilitates efficient training, evaluation, and inference of the model, ensuring optimal performance in web page detection tasks.

**Usage**

_**To utilize the Figma Web Page Detection model, follow these steps:**_

Prepare the dataset containing annotated images.
Convert the annotations to the YOLOv1.1 format.
Configure the YAML file according to the desired model specifications.
Deploy the YOLOv8 model using Ultralytics for training or inference tasks.
For detailed instructions on training, evaluation, and inference procedures, refer to the documentation provided within the repository.

