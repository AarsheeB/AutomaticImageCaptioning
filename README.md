# Automatic Image Captioning Project

This repository contains the code for an automatic image captioning system using deep learning techniques. The system extracts features from images using a Convolutional Neural Network (CNN) and generates captions for those images using a Recurrent Neural Network (RNN).

## Overview

Automatic image captioning is a challenging task in computer vision and natural language processing. This project aims to automatically generate descriptive captions for images using deep learning models. The project consists of the following components:

1. **CNN (Encoder)**: Extracts features from images to represent them in a high-dimensional space.
2. **RNN (Decoder)**: Generates captions based on the features extracted by the CNN.
3. **Training Pipeline**: Trains the CNN and RNN models using a dataset of image-caption pairs.
4. **Evaluation**: Evaluates the performance of the trained models using metrics such as BLEU score.
5. **Inference**: Performs inference to generate captions for new unseen images.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/automatic-image-captioning.git
   cd automatic-image-captioning

2. Install dependencies:
   pip install -r requirements.txt

## Usage
### Data Preprocessing:
#### Preprocess the dataset (resizing, normalization, tokenization).
### Training:
#### Train the CNN (Encoder) and RNN (Decoder) models using the preprocessed dataset.
### Evaluation:
#### Evaluate the trained models using metrics such as BLEU score.
### Inference:
#### Use the trained models to generate captions for new unseen images.

