# Automated-Image-Caption-Generator-Using-CNN-and-LSTM

Problem Statement:
The goal of this project is to develop an intelligent image captioning system that can
automatically generate meaningful textual descriptions for given images. This system
should be able to understand the contents of an image and describe it in natural
language using deep learning techniques.


Explanation:
This project uses a combination of Convolutional Neural Networks (CNN) for extracting
image features and Long Short-Term Memory (LSTM) networks for generating the image
captions. The InceptionV3 model, pre-trained on ImageNet, is used to encode image
features, while the decoder is an LSTM model that generates captions word-by-word
based on the encoded image representation and previously generated words.
Key steps in the project:
- Preprocessing of image and caption data.
- Feature extraction from images using InceptionV3.
- Tokenization and vectorization of captions.
- Building and training an encoder-decoder model.
- Evaluating the model using BLEU scores and generating captions for new images.

  
Dataset Link
The Flickr8k dataset used in this project can be downloaded from Kaggle:
https://www.kaggle.com/datasets/adityajn105/flickr8k
