# Eye for the blind
To create a deep learning model which can explain the content of an image in the form of speech through caption generation with attention mechanism on Flickr8K dataset. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 

This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by CNN-based encoder and this will be decoded by an RNN model.

The project is an extended application of Show, Attend and Tell: Neural Image Caption Generation with Visual Attention paper.
https://arxiv.org/abs/1502.03044

The dataset is taken from the Kaggle website and it consists of sentence-based image description having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

# Project Pipeline
The project pipeline can be briefly summarized in the following four steps:

1. Data Understanding: Here, you need to load the data and understand the representation.

2. Data preprocessing: In this step, you will process both images and captions to the desired format.

3. Train/Test Split: Combine both images and captions to create the train and test dataset.

4. Model-Building: This is the stage where you will create your image captioning model by building Encoder , Attention and Decoder model.

5. Model Evaluation: Evaluate the models using greedy search and BLEU score.
