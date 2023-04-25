# Capuchin Bird Call Detection

This project aims to build a deep learning model that can detect the presence of capuchin bird calls in audio clips. Capuchin birds are a rare and endangered species that live in the Amazon rainforest. Their calls are distinctive and can be used as an indicator of biodiversity and habitat quality.

The code consists of two main parts:

- Data loading and visualization: This part uses os, matplotlib, tensorflow_io and IPython.display libraries to load, process and play the audio clips. It also defines a function to convert the audio clips to 16 kHz mono wav files, which are suitable for the model input.
- Model building and training: This part uses tensorflow and keras libraries to build a convolutional neural network (CNN) that can classify the audio clips as capuchin or non-capuchin. It also uses callbacks, metrics and plots to monitor the model performance and accuracy.

The code requires the following dataset from Kaggle: https://www.kaggle.com/datasets/kenjee/z-by-hp-unlocked-challenge-3-signal-processing

The dataset contains two folders: Parsed_Capuchinbird_Clips and Parsed_Not_Capuchinbird_Clips. The former contains 100 audio clips of capuchin bird calls, while the latter contains 100 audio clips of other bird calls or background noises.

To run the code, you need to install the following libraries:

- os
- matplotlib
- tensorflow
- tensorflow_io
- IPython.display
- warnings

You can install them using pip or conda commands.

To run the code, you need to execute the following steps:

1. Import the required libraries.
2. Load and play the audio clips using os and IPython.display.
3. Define and apply the Loading_wav_16k_mono function to convert the audio clips to 16 kHz mono wav files using tensorflow_io.
4. Build and train the CNN model using tensorflow and keras.
5. Evaluate and visualize the model performance using metrics and plots.

The code is commented and documented for better understanding and readability.