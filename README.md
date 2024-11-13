# ocular-disease
## Disease Recognition Using Ocular Images 
This project is aimed at using neural networks and transfer learning to perform ocular disease recognition.


## Overview
Medical diagnoses often face challenges like time consumption and human errors, which can lead to fatal misclassifications and late detections. To address this, I was tasked with developing a computer-based system to diagnose cataracts from ocular images. The system will use a dataset of human-annotated eye images to classify normal and cataract-affected eyes. This technology aims to accelerate eye disease diagnosis and can potentially be expanded to detect other diseases.

The notebook details a model created for analyzing ocular images to detect cataracts. The dataset comprises human-annotated, quality-controlled images labeled for classification. This system can assist medical experts in diagnosing or validating diagnoses. The model employs a Convolutional Neural Network (CNN) with VGG16 for transfer learning. Image data was processed with an image generator and divided into 75% for training (with 20% used for validation) and 25% for testing. The model achieved an accuracy of 89.86%, correctly classifying 257 out of 286 test images. The confusion matrix highlighted 8 false positives, where cataract cases were incorrectly labeled as normal. Overall, the model demonstrated strong performance suitable for real-world application.


The full notebook is available here: https://github.com/juwonlo-tech/ocular-disease/blob/main/Disease_recognition_using_ocular_images_.ipynb




