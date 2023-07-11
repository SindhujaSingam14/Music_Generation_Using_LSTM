# Music Generation using LSTM

## Summary
This project aims to leverage the power of Long Short-Term Memory (LSTM) neural networks to generate music based on MIDI files. MIDI files contain musical information such as notes, durations, and velocities, making them suitable for training an LSTM model to learn the patterns and structures of musical compositions.


## Data Set Description 
The dataset consists of a collection of MIDI files containing piano notes. MIDI (Musical Instrument Digital Interface) is a standard file format that represents musical information and specifically capture piano performances or compositions.These MIDI events include note-on and note-off messages, which indicate when a note starts and ends, as well as additional control messages for attributes like velocity (volume), pitch bend, modulation, and sustain pedal usage.

## Project Steps

### Dataset Preparation 
Collected  a dataset of MIDI files that represent piano notes we want the model to learn from. 

### Data Preprocessing
Convert the MIDI files into a suitable format for training the LSTM model. This involves extracting the relevant musical features, such as notes, durations, and velocities, and encoding them into a numeric representation that the LSTM can understand.

### Model Training
Trained the LSTM model using the preprocessed dataset. Configured the model architecture which is ( Long Short Term Memory ) LSTM, hyperparameters, and training parameters according to the specific requirements. 

### Music Generation
After the model is trained, used it to generate new music. Provided a seed sequence input to the model, and it will generate a continuation or variation based on the learned patterns. Experimented with different seed sequences and model configurations to explore the creative potential of the LSTM-based music generation.

## Overview

The goal of this project is to provide a comprehensive solution for generating music by training an LSTM model on a dataset of MIDI files. The model will learn from the dataset's musical patterns and generate new melodies, harmonies, and rhythms that resemble the style and characteristics of the training data.
