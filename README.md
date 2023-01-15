# Horn Classification System

## Introduction
This system is designed to classify different types of horn based on their sound recordings. It utilizes a dataset of horn sound recordings and corresponding labels to train a machine learning model. The trained model can then be used to classify new sound recordings of horns.

## Requirements
- Python 3.0
- scikit-learn
- pandas
- librosa
- numpy

## Usage
1. Run the `train.py` file to train the model using the provided dataset (`horn_data.csv`). The dataset should contain sound recordings of horns in the form of .wav files, and corresponding labels indicating the type of horn.
2. Run the `predict.py` file to classify a new sound recording of a horn. Input the file path of the sound recording as prompted.
3. Run the `test.py` file to evaluate the performance of the model using a test dataset.

## Note
- Ensure that the dataset used for training and testing are well labeled and diverse
- The system is only for educational and research purposes and is not intended for use in a production environment.
