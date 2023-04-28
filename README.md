# Capuchin Bird Call Detection

This project aims to build a deep learning model that can detect the presence of capuchin bird calls in audio clips. Capuchin birds are a rare and endangered species that live in the Amazon rainforest. Their calls are distinctive and can be used as an indicator of biodiversity and habitat quality.
![image](https://user-images.githubusercontent.com/7029092/235248959-a3aadbec-9a8f-49f7-bc47-8efc25ef08e9.png)

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

# Results  

![image](https://user-images.githubusercontent.com/7029092/235249279-507dc5c9-1d84-45fb-b3e1-d91f509b3bad.png)
![image](https://user-images.githubusercontent.com/7029092/235249359-c239e0f2-638a-4a6d-8301-588565993116.png)
The Visualization shows the training loss and validation loss over the course of the training epochs. 
The model loss and accuracy values are also provided in the comment for reference. The model achieved a loss of 0.034 and an accuracy of 94%, for one of the sample recording giving useful  informationfor assessing the performance of the model. I have predicted the presence of Capuchin Bird sounds for the entire data set
