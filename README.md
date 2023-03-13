# M4 Group Assignments
Group members: Nadia, Nikolaj & Nicklas

This repository contains group assignments for BDS M4. A seperate folder is created for each assignment and the repository currently holds:
- [Group Assignment 1 - Notebook](Group_Assignment_1/Group_Assignment_1.ipynb)
- [Group Assignment 2 - CNN - Notebook](Group_Assignment_2/Group_Assignment_2_CNN.ipynb)
- [Group Assignment 2 - LSTM - Notebook](Group_Assignment_2/Group_Assignment_2_LSTM.ipynb)
- [Group Assignment 3 - Notebook](Group_Assignment_3/Group_Assignment_3.ipynb)
- [Group Assignment 4 - Notebook](Group_Assignment_4/Group_Assignment_4.ipynb)


## Group Assignment 1
This folder contains an Airbnb price prediction model created with Pytorch and demonstrated in Gradio.

The notebook goes through the following process:

1. Data preprocessing
2. Feature engineering
3. Definition and training of a neural network model with Pytorch
4. Experimentation with hyperparameters
5. Model evaluation
6. Model demonstration in Gradio

An example model is imported as default for experimentation with hyperparameters, based on which 6 experiments are conducted. The experiments touch upon the following types of hyperparameters:

Experiment 1: Activation Function

Experiment 2: Loss Function

Experiment 3: Hidden Layers

Experiment 4: Epochs

Experiment 5: Learning Rate

Experiment 6: Loss Function


The models are then evaluated on the test data by means of R^2 and MSE and the best performing model is demonstrated in Gradio.

If wanted, the other models can be implemented and demonstrated in Gradio as well.



## Group Assignment 2
This folder contains a CNN image classification model and a LSTM temperature prediction model created with pytorch.

The notebooks go through the following process:
1. Data preprocessing
2. Feature engineering
3. Definition and training of a neural network model with Pytorch
4. Experimentation with hyperparameters
5. Model evaluation



## Group Assignment 3
This folder contains a Netflix recommendation model created with SBERT and demonstrated in Gradio.

Based on a user-defined text-input, the model recommends a Netflix movie/TV-series which matches the search-prompt as much as possible.

The notebook goes through the following process:
1. Data preproccesing and feature engineering
2. Modelling using SBERT and cosine similarity
3. Demonstrating the model in Gradio


## Group Assignment 4
This folder contains a fine tuned Japanese speech recognition model and have been fine tuned with the Common Voice dataset.


The notebook contains the following:
1. Preprocessing the data
2. Training
3. Pushing the model to Hugging Face Hub
4. Gradio
5. Gradio with Google API

Links:
- [Japanese Fine Tuned Whisper Model](https://huggingface.co/NadiaHolmlund/Japanese_Fine_Tuned_Whisper_Model)
- [Real-time demo for Japanese speech recognition](https://huggingface.co/spaces/NadiaHolmlund/Japanese_Fine_Tuned_Whisper_Model)
- [Japanese to English translator](https://huggingface.co/spaces/NadiaHolmlund/Japanese_Fine_Tuned_Whisper_Model_2)
- [Convert Japanese speech to text, get pronunciation and translation to English](https://huggingface.co/spaces/NadiaHolmlund/Japanese_Fine_Tuned_Whisper_Model_3)

