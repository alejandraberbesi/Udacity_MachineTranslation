# Machine Translation Project

# Introduction

The core objective of this project was to build a deep neural network that functions as part of an end-to-end pipeline capable of translating English text into French.

The project delves into the fundamental stages of creating such a system:

* Preprocessing: Transforming raw text data into numerical sequences suitable for neural network input.

* Model Building: Designing and training various neural network architectures that learn to map English sequences to French probability distributions. This involves exploring different network types and ultimately designing an improved model.

* Prediction: Utilizing the trained model to generate French translations for new English input sentences.

# Project Details and Context

The development process within the accompanying Jupyter Notebook (machine_translation.ipynb) guides users through key concepts in sequence-to-sequence modeling:

* Dataset: The project utilizes a small-vocabulary English-French dataset, which allows for reasonable training times while still demonstrating complex deep learning concepts.

* Text Preparation: This involves crucial steps like tokenizing words into unique integer IDs and applying padding to ensure all input sequences are of uniform length.

* Neural Network Architectures: The notebook explores and requires implementation of various models, including:

        Basic Recurrent Neural Networks (RNNs).

        RNNs enhanced with Word Embeddings for richer word representations.

        Bidirectional RNNs to leverage context from both past and future words in a sequence.

        The Encoder-Decoder architecture, a foundational concept for sequence-to-sequence tasks.

        Finally, a custom, more advanced model is built, combining learned techniques to achieve higher translation quality.

* The project primarily uses Keras (with TensorFlow backend) for neural network development, along with Numpy for numerical operations.

## Contribution Note

Please be aware: The code, text, images, and other files found in this repository are NOT my intellectual property. They originate from and belong to the Udacity NLP Nanodegree Program. My contributions to this project were exclusively within the designated 'IMPLEMENTATION' sections of the machine_translation.ipynb notebook, where I developed the required functionalities as part of the Nanodegree curriculum. For comprehensive details regarding intellectual property, please consult the CODEOWNERS file within this repository.
