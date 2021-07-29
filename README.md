# Speech Recognition
The objective of this project is to leverage the TensorFlow Speech Commands Dataset in order to build a speech recognition model to better understand the technology behind speech-based virtual assistants.

# Data Science Process Steps
Data Understanding/Preparation
- The TensorFlow Speech Commands Dataset contains 65,000 one-second long audio clips of 30 different words recorded by thousands of different people.
- The labels that the Kaggle competition asked participants to predict were yes, no, up, down, left, right, on, off, stop, and go.
- As part of the data preparation process, the audio clips were processed to their respective waveforms and spectrograms (see Jupyter notebook/PDF for more information).

Modeling/Evaluation
- The Minimum Viable Product (as of July 29, 2021) achieved a train accuracy of 26.0% and a test accuracy of 26.9%.
- When evaluated against the Kaggle dataset, the model achieved an accuracy of ~20%.

Future Improvement Ideas
- The goal over the next week is to improve the accuracy of the model.


Link to Kaggle competition:
https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/overview
