# Image_Caption_Generator
This project implements an **Image Caption Generator** that combines **Convolutional Neural Networks (CNNs)** and **Long Short-Term Memory (LSTM)** networks to generate meaningful captions for images. The model is trained on the **Flickr8k** dataset and utilizes pre-trained DenseNet201 for feature extraction from images.

## Project Overview
Image captioning is a task that generates a textual description of an image. This project focuses on building a deep learning pipeline that uses:
  - CNN (DenseNet201) for extracting image features.
  - LSTM for generating the textual captions based on the image features and previously generated words.
  
The model is evaluated using the **BLEU score** to compare the generated captions with the ground truth.
