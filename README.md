# Diabetic-Retinopathy-Detection
Diabetic Retinopathy is the leading cause of blindness in the working-age population of the developed world.The goal of this model  is to push an automated detection system to the limit with realistic clinical potential.

# Model Overview
The model uses a VGG16 network with completely trainable parameters.

Optimizer-Adam(lr=0.0001 initialy,with rate decay)

Loss=categorical_crossentropy

Metrics=Accuracy

Custom Layer-Fully Connected(1000,with Dropout@0.3)

# Performance Parameters
The Dataset is relatively small.

Train Accuracy-0.99

Val_Accuracy-0.79

# References
Kaggle Kernels

Keras Documentation

# Hosted On
Kaggle

Dataset-https://www.kaggle.com/c/diabetic-retinopathy-detection/overview
