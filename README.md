# ocular-disease
## Disease Recognition Using Ocular Images 
This project is aimed at using neural networks and transfer learning to perform ocular disease recognition.


## Overview
Medical diagnoses often face challenges like time consumption and human errors, which can lead to fatal misclassifications and late detections. To address this, I was tasked with developing a computer-based system to diagnose cataracts from ocular images. The system will use a dataset of human-annotated eye images to classify normal and cataract-affected eyes. The aim is to accelerate eye disease diagnosis and can potentially be expanded to detect other diseases.

The notebook details a model created for analyzing ocular images to detect cataracts. The dataset comprises human-annotated, quality-controlled images labeled for classification. This system can assist medical experts in diagnosing or validating diagnoses. The model employs a Convolutional Neural Network (CNN) with VGG16 for transfer learning. Image data was processed with an image generator and divided into 75% for training (with 20% used for validation) and 25% for testing. The model achieved an accuracy of 89.86%, correctly classifying 257 out of 286 test images. The confusion matrix highlighted 8 false positives, where cataract cases were incorrectly labeled as normal. Overall, the model demonstrated strong performance suitable for real-world application.


Snapshot of augmented data after initial data exploration: 

<img width="540" alt="Screenshot 2024-11-12 at 9 35 45 PM" src="https://github.com/user-attachments/assets/b21ba50c-3848-463a-b923-df3a09643ea2">



Snapshot of the model's evaluation without normalization 

<img width="368" alt="Screenshot 2024-11-12 at 9 37 15 PM" src="https://github.com/user-attachments/assets/7fd8fb76-881a-46e8-831d-74fdab6e142b">

The full notebook is available here: https://github.com/juwonlo-tech/ocular-disease/blob/main/Disease_recognition_using_ocular_images_.ipynb




