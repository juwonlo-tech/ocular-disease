# ocular-disease
## Disease Recognition Using Ocular Images 
This project is aimed at using neural networks and transfer learning to perform ocular disease recognition.


## Abstract

The notebook contains a model developed to analyze the ocular images and detect whether an eye image is mormal or has cataract. The dataset contains quality controlled human anotataed image data clasifying eye images into different labels. The system developed can be used by medical experts to validate diagnosis, or for initial diagnosis. Convolutional Neural Network and VGG16 for transfer learning were used to create the model. The images were loaded to the network using the image generator and split into 25% for testing and 75% for training- 20% of which was used for validation. The evaluation of the model shows that the model has an accuracy of 89.86%. It was able to accurately classify 257 of the 286 images in the test data. Looking at the confusion matrix, the critical result is the 8 false positives in the prediction (8 images labelled as normal but are cataract). Overall, the performance of the model is very good and can be safely implemented in real-life application.

## Use Case

Medical experts have tried to accurately detect and diagnose diseases based on examinations, tests, scans, and images. These diagnoses are time-consuming and are subject to human errrors. Misclassification can be fatal and late diagnosis can be life-threatning. To utilize the power of computers, I have been approached to develop a system to diagnose an eye disease- cataract based on the eye image. The system will be trained on the human annotated ocular images dataset to classify normal eye images and cataract eye images. A system can be built on this to accelerate the diagnosis on eye diseases and expanded to include other dieases.

The full notebook is available here:




