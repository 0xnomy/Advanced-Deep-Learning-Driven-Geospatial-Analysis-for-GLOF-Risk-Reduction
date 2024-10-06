# Advanced Deep Learning Driven Geospatial Analysis for GLOF Risk Reduction

This repository contains the work associated with the research paper titled **"Advanced Deep Learning Driven Geospatial Analysis for GLOF Risk Reduction: A Case Study from Pakistan’s Northern Mountain Ranges."** The paper was submitted to the **ICET Conference at GIKI** but was not accepted. This repository serves as a comprehensive collection of all the efforts and methodologies employed in the research.

The dataset used for this research is available at IEEE DataPort. However, to gain access, you will need to email the researcher who created the dataset. Please reach out to them directly to request access.

Dataset: https://ieee-dataport.org/documents/glacial-lakes-detection-dataset 

## Repository Structure

The repository consists of several files that encompass different deep learning models and techniques used for glacial lake outburst flood (GLOF) detection and segmentation. Below is a brief description of each file:

1. **DeepLabV3+ ResNet + Dice Loss GLOF Detection**
   - Implementation of the DeepLabV3+ model with a ResNet backbone, utilizing the Dice loss function for improved segmentation accuracy.

2. **DeepLabV3+ ResNet + Crossentropy GLOF Detection**
   - A variant of the DeepLabV3+ model also based on ResNet, this version employs cross-entropy loss for training, aimed at optimizing pixel-wise classification.

3. **Inference yolov8-seg GLOF Detection**
   - Code for performing inference using the YOLOv8 segmentation model to detect glacial lakes and assess the associated risks of GLOF.

4. **lake_segmentation_yolov8_old**
   - An older implementation of the YOLOv8 model for lake segmentation, which may contain different hyperparameters or architectural choices from the latest version.

5. **U-Net + EfficientNetB0 GLOF Detection**
   - This file implements a U-Net architecture with an EfficientNetB0 backbone, designed for pixel-level segmentation of glacial lakes. The model employs cross-entropy loss and achieves an IoU score of 69.1%.

6. **U-Net GLOF - Paper Replication**
   - A codebase focused on replicating findings from an existing paper utilizing U-Net for GLOF segmentation tasks.

7. **U-Net + ResNet Backbone GLOF Detection**
   - An implementation of U-Net using a ResNet backbone, designed to leverage ResNet's feature extraction capabilities for better segmentation performance.

8. **YoloV8-Seg, IoU GLOF Detection**
   - Implementation of the YOLOv8 model focused on segmentation tasks with a focus on optimizing the IoU score, showcasing its application in GLOF detection.

## Research Paper

The paper was submitted to International Conference on Emerging Technologies (ICET-GIKI) but was rejected. If you want to checkout the paper please reach out to me on LinkedIn.

## Contribution and Contact

Feel free to reach out if you have any questions or WOULD LIKE TO WORK ON SIMIALAR RESEARCH PROJECTS. Contributions and suggestions are welcome!

https://linkedin.com/in/naumanmurad

https://www.kaggle.com/naumanalimurad
