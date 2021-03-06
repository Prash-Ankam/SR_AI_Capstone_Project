# SR_AI_Capstone_Project


## Music Genre Classification From Audio Files

### Objective:
- To analyse & extract the features from Audio Files
- To implement deep artificial neural network to classify the genres


### Data Set
The GTZAN Genre Collection dataset is used to develop genre classification algorithm.
The dataset consists of 1000 audio tracks each 30 seconds long. 
It contains 10 genres, each represented by 100 tracks. 
The tracks are all 22050Hz Mono 16-bit audio files in .wav format.
The size of the dataset is 1.2GB

   DataSet link is [here](https://www.kaggle.com/andradaolteanu/gtzan-dataset-music-genre-classification)

### Data Set Source
The dataset has been procured from Marsyas (Music Analysis, Retrieval and Synthesis for Audio Signals) is an open source software framework 
for audio processing with specific emphasis on Music Information Retrieval applications. 

### A Brief Description about features in Audio Files:
#### - Spectrogram:
A visual representation of frequencies over time
![image](https://user-images.githubusercontent.com/47745543/82432841-3c9b0200-9aae-11ea-95c9-a7ebed72ba77.png)
![image](https://user-images.githubusercontent.com/47745543/82429830-21c68e80-9aaa-11ea-8352-5b0588149122.png)

#### - Zero Crossing Rate:
Rate at which the signal changes signs (that is positive to negative)
![image](https://user-images.githubusercontent.com/47745543/82431199-fe9cde80-9aab-11ea-8692-6d03900bc8cc.png)

#### - Spectral Centroid: 
This parameter indicates where the center of mass of the signal is located   

![image](https://user-images.githubusercontent.com/47745543/82432691-0a89a000-9aae-11ea-883d-0cc6b0ae40c9.png)

#### - Spectral Rolloff:
The measure of shape of signal, frequency below which a specified percentage of the total spectral energy
![image](https://user-images.githubusercontent.com/47745543/82432519-ce563f80-9aad-11ea-8aed-cceb97c732d1.png)

#### - Mel- Frequency Cepstral Coefficients:
Small set of features which describe the shape of spectral signal
![image](https://user-images.githubusercontent.com/47745543/82431676-95699b00-9aac-11ea-9e8f-57bbfbf17979.png)

#### - Chroma Frequencies:
Describes entire spectral in 12 distinct semitones of musical octave
![image](https://user-images.githubusercontent.com/47745543/82432204-538d2480-9aad-11ea-9b09-12a6bbbee4dd.png)


### After taking required features.The Process is as follows:

   Extracting the Spectrogram for every Audio
   
   Extracting Features from Spectrogram
   
   Writing data to csv file
   
   Encoding the Labels
   
   Scaling the Feature columns
   
   
### The Model

   Neural Network used: ANN
   
   Optimizer used : Adam







