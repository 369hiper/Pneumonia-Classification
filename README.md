# Pneumonia-Classification
Using Computer Vision, Deep Learning and CNN to Classify Images with 97% accuracy.
#Pneumonia Diagnosis

Problem Statement:
Automated defect detection in medical imaging has become the emergent field in several medical diagnostic applications. Automated detection of X-Ray is very crucial as it provides information about abnormal tissues which is necessary for planning treatment. The conventional method for defect detection in magnetic resonance brain images is human inspection. This method is impractical for large amount of data. So, automated X-Ray detection methods are developed as it would save Dermatologist time.

1. •    Image Acquisition.
2. •    Resizing the Image
3. •    Denoising the Image
4. •    Image Segmentation
5. •    Deep Learning Methods

A Convolutional Neural Network that is able to detect whether a patient has pneumonia, both bacterial and viral, or not, based on an X-ray image of their chest. Implements transfer learning, using the first 16 layers of a pre-trained VGG19 Network, to identify the image classes.
By completing the following steps, the following files are created:
1. •	model.h5 - This stores a '.h5' version of the Convolutional Neural Network model trained.
2. •	plot.jpg - This displays statistics regarding the training process of the model.

The final accuracy obtained by the model exceeds 90%.

Algorithm Used:
# What All was Done
'1. •	I also used VGG-16 is a convolutional neural network that is trained on more than a million images from the ImageNet database . The network is 16 layers deep and can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. Very Deep Convolutional Networks for Large-Scale Image Recognition
2. •	In the context of artificial neural networks, the rectifier is an activation function defined as the positive part of its argument.

•	I used the Following Optimizations:
  1. o	loss = categorical_crossentropy
  2. o	optimizer = adam
  3. o	Metrics = Accuracy

1. •	Deep Learning is one most common technique for Image Classification. 
2. •	Although, Convolution Neural Network(VGG-16) Seems to Return Relatively Better Result. However, It’s Computationally Expensive and Time Consuming.
3. •	I was Able to get 97.16 % of Accuracy and 88% Validation Accuracy. Which is Pretty Awesome.

