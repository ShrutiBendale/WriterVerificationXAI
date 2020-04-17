# Writer Verification, Explainable AI

The purpose of this project is to compare handwritten samples of the letter ‘and’ of two writers and verify if the handwriting samples are of the same writer. Initially, 15 handcrafted features were identified, and the images were annotated for these features. These 15 features of all the images were used to generate a Bayesian model and calculate the conditional probability tables. A combinational Bayesian model with 30 features and one hypothesis node was created to compare two images and generate the output (similar/not similar) at the hypothesis node. We also create a Siamese Convolutional Neural Network to take the handcrafted features of two images and generate the prediction. Finally, instead of having to manually annotate the images, we use an Autoencoder combined with CNNs to generate features for the images.

## Overview

The problem of handwriting identification is to interpret intelligible handwritten input automatically, which is of great interest in the pattern recognition research community because of its applications to many fields. As one of the fundament problems in designing practical recognition systems, the recognition of handwritten digits is an active research field. Immediate applications of the digit recognition techniques include postal mail sorting, automatic address reading and mail routing, bank check processing, etc. Most importantly, one of the applications is handwriting verification for digital forensics analysis where we have to identify if two given handwriting samples are by the same writers.

In this project we were given handwritten ‘and’ samples of images. The project was divided into 4 parts:

<ol>
  <li><b>Annotations: </b><br>
  The first task was to annotate the given images based on the given 15 features.</li>
  <li><b>Probabilistic Approach: </b><br>
  The second task was to use these labelled features to create a combined Bayesian Network for two images and that can be used to identify the similarity of the images.</li>
  <li><b>Deep Learning Approach: </b><br>
  The third task was to get the similarity of two images using a deep neural model. For this purpose, we use the Siamese Convolutional Neural Network approach to predict the labels.</li>
  <li><b>Representation Learning Approach: </b><br>
  The final task uses representation learning to learn the features from the images. We then convert these features to human explainable features to get the features in terms of the 15 characteristics we had identified.</li>
</ol>

### Note:
**Refer the 'Final Report.pdf' document for a detailed explanation.**<br>
Task2 folder contains the .ipynb file for the hybrid Bayesian model.<br>
Task3 folder contains the .ipynb file for the Siamese Combitional Neural Network model.<br>
Task4 folder contains the .ipynb file for the hybrid model that consists of an autoencoder combined with 15 CNNs. 
