# Speech Emotion Recognition

# Mentors 
1. Aditya Gupta
2. Arpit Verma

# Teams

**Team 1** 
Anand Patwa
Aryan Singh
Darshit Trevadia
Pushpanshu Tripathi
Shreyasi Mandal
Parth Govil
Aakarshika Singh

**Team 2**
Aarjav Jain
Aryan Agarwal
Rajat Singh
Saaransh Agarwal
Sarthak Kohli
Samrudh BG

**Team 3**
Dheeraj Agarwal
Viplav Patel
Mirge Saurabh Arun
Samriddhi Gupta
Varun Singh
Nitesh Pandey
Rashmi GR

**Team 4**
Anmol Agarwal
Srajan Jain
Rishabh Mukati
Pranav Singh
Sarah Kapoor
Sahil Bansal

**Team 5**
Gaurav Kumar
Tarun Agarwal
Ankit Yadav
Harsh Patel
Gulshan Kumar
Aakash Kumar Bhoi

# Abstract
Detection of emotions is natural for humans, but it is a very difficult task for computers, since accessing the depth behind content is difficult and that’s what speech emotion recognition (SER) sets out to do. It is a system through which various audio speech files are classified into different emotions such as happy, sad, anger and neutral by computers.

# Objective
In this project, using RAVDESS dataset (which contains around 1500 audio file inputs from 24 different actors (12 male and 12 female) who recorded short audios in 8 different emotions) we will train an NLP-based model which will be able to detect among the 8 basic emotions, as well as the gender of the speaker i.e. Male voice or Female voice. After training we can deploy this model for predicting with live voices.

# Deliverables
1. Learn the basics of Python, ML/DL, NLP, librosa and sklearn; literature review; analyzing the dataset; and feature extraction. 
2. Building and training the model on the training data, followed by testing on test data.
3. Testing the model on live voices and collecting the results.

# Dataset
The RAVDESS is a validated multimodal database of emotional speech and song. The database is gender balanced consisting of 24 professional actors, vocalizing lexically-matched statements in a neutral North American accent. Speech includes calm, happy, sad, angry, fearful, surprise, and disgust expressions, and song contains calm, happy, sad, angry, and fearful emotions. All conditions are available in face-and-voice, face-only, and voice-only formats.

# Feature Extraction
Feature extraction is important in modeling because it converts audio files into a format that can be understood by models.

1. MFCC (Mel-Frequency Cepstral Coefficients)- It is a representation of the short-term power spectrum of a sound, based on linear cosine transformation of a log power spectrum on nonlinear mel frequency scale.
2. Chroma- It closely relates to the 12 different pitch classes. It captures harmonic and melodic characteristics of music.
3. Mel Scale- It is a perceptual scale of pitches judged by listeners to be in equal in distance from one another. 
4. Zero Crossing Rate (ZCR)- It is the rate at which a signal changes from positive to zero to negative or from negative to zero to positive.
5. Spectral Centroid- It is the center of 'gravity' of the spectrum. It is a measure used in digital signal processing to characterize a spectrum.

# Model Implementation

MLP (Multi-Layer Perceptron) Model
The  arrays containing features of the audios are given as an input to the MLP Classifier that has been  initialized. The Classifier identifies different categories in the datasets  and classifies them into different emotions.

Convolutional Neural Network (CNN)
The activation layer called as the RELU layer is  followed by the pooling layer. The specificity of the CNN layer is  learnt from the functions of the activation layer. 

RNN-LSTM Model
We used RMSProp optimizer to train the RNN-LSTM model, all  the experiments were carried with a fixed learning rate. Batch  Normalization is applied over every layer and the  activation function used is the SoftMax activation function.

# Results
The accuracies obtained by different teams  are as follows:

**Team 1**
MLP Model: 63%, CNN Model:73%, LSTM Model: 72%

**Team 2**
MLP Model: 60%, CNN Model:70%, LSTM Model: 60%

**Team 3**
MLP Model: 62%, CNN Model:71%, LSTM Model: 68%

**Team 4**
MLP Model: 71%, CNN Model:78%, LSTM Model: 75%

**Team 5**
MLP Model: 66%, CNN Model:72%, LSTM Model: 66% (Emotion recognition)
MLP Model: 99%, CNN Model:99.5%, LSTM Model: 97% (Gender recognition)

# Demonstration
The video demonstration of the project can be found on the following link:
https://drive.google.com/drive/folders/1t0T0X54XUQ5zpvyOXhztZbLY6y9wd9nN?usp=sharing


# Documentation
The documentation can be accessed at the following link:
https://www.overleaf.com/project/60cc4cd9e461496da6c8ce1c


# Poster
The poster can be viewed at the following link:
https://drive.google.com/file/d/1BMaU_J68fACNt-fm1vPc5KO0vJqWQ2WH/view


# References
1. Python basics: https://github.com/bcs-iitk/BCS_Workshop_Apr_20/tree/master/Python_Tutorial. 
-Shashi Kant Gupta, founder BCS. 
2. Intro to ML: https://youtu.be/KNAWp2S3w94 Basic CV with ML: https://youtu.be/bemDFpNooA8 
3. Intro to CNN: https://youtu.be/x_VrgWTKkiM  Intro to DL: https://youtu.be/njKP3FqW3Sk
4. Feature Extraction: https://www.kaggle.com/ashishpatel26/feature-extraction-from-audio , https://youtube.com/playlist?list=PL-wATfeyAMNqIee7cH3q1bh4QJFAaeNv0 ,           https://medium.com/analytics-vidhya/understanding-the-mel-spectrogram-fca2afa2ce53
5. Research paper: https://ijesc.org/upload/bc86f90a8f1d88219646b9072e155be4.Speech%20Emotion%20Recognition%20using%20MLP%20Classifier.pdf
6. Research Paper on SER using CNN: https://www.researchgate.net/publication/341922737_Multimodal_speech_emotion_recognition_and_classification_using_convolutional_neural_network_techniques
7. K Fold Cross Validation: https://machinelearningmastery.com/k-fold-cross-validation/
8. Research Paper for LSTM Model in SER: http://www.jcreview.com/fulltext/197-1594073480.pdf?1625291827
9. Dataset: https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio.









