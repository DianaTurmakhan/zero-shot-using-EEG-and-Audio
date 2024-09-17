# Zero-Shot Classification using EEG and Audio

Zero-shot learning (ZSL) aims to classify unseen classes by using knowledge of seen classes. This repository implements a ZSL approach combining EEG and audio data. We use a two-modal framework to map features from both EEG and audio modalities into a shared semantic space.

The approach focuses on:
- EEG signals captured during tasks related to emotion classification.
- Audio signals used for speech and sound classification.
- Mapping features into a two-dimensional semantic space for five classes.
The system uses **triplet loss** to ensure that features from the same class across modalities are close together while those from different classes are far apart.

## Model Architecture

The model architecture includes:
- A feature extractor for EEG signals.
- A feature extractor for audio signals.
- A shared semantic space where both EEG and audio features are projected for classification.


### Prerequisites

To run the code, you need the following dependencies:
- Python 3.8 or above
- PyTorch
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

### Usage
To explore the model and results, open the Jupyter notebook:
- Data preprocessing for EEG and audio signals.
- Feature extraction.
- Training the zero-shot classification model with triplet loss.
- Evaluating the model on test data.
