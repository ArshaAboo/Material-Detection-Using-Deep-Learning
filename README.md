# Material-Detection-Using-Deep-Learning
Train deep learning models to classify materials of objects from their images into different categories.

This project explores material classification for smart waste management using deep learning techniques. It leverages Convolutional Neural Networks (CNNs) and Vision Transformers, trained and optimized through Neural Architecture Search (NAS) with TensorFlow and Keras. After experimenting with various architectures, the best-performing CNN model achieved an accuracy of 86% on the dataset of object images.
The dataset used is an extension of the Flickr Material Database (FMD) and incorporates additional classes relevant to waste management. 
https://people.csail.mit.edu/lavanya/fmd.html

To make the solution practical for edge devices, the models were compressed using techniques such as quantization, pruning, and weight clustering. These steps significantly reduced the model size—by about 70%—while maintaining nearly the same level of accuracy. The final optimized models were deployed and tested on a Raspberry Pi, enabling efficient inference on a device with limited memory and computational power.
