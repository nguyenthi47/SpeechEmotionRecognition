# SPEECH EMOTION RECOGNITION

This project build a machine learning model to classify emotion from audio file. This project extracts the emotion from audio which is helpful to bring a better customer services through voice call, marketing strategies based on consumers voice features, or alert system for people to control their emotion when they are speaking

## **Technical approach:**
Extracting features from audio files (MCFFs), fetching these features into a Convolution Neural  Network to classify speech emotion into 5 categories which are calm, happy, angry, fearful, sad belongs to 2 genders: male and female.

#### Dataset: RAVDESS (speech)
  (80% for training, 20% for testing)
#### Audio files characteristics and feature extraction
  Sample rate: 44100Hz  
  For each audio, using LibROSA to extract the sound mfccs features and tag the emotion label  
  @Jonathan Hui - Visualiza MFCCs features extracting  
  ![alt text](https://miro.medium.com/max/1400/1*0b1UYIC-tP-TpPmAOudwLQ.png)
  
  MFCCs features and labels for it  
  ![Screenshot from 2020-06-03 16-18-51](https://user-images.githubusercontent.com/48004894/83607611-7ee83700-a5b6-11ea-8f35-60bdc05ba1c6.png)
  
  CNN Model  
  ![Screenshot from 2020-06-03 16-25-47](https://user-images.githubusercontent.com/48004894/83607908-f7e78e80-a5b6-11ea-800d-3500abd95f86.png)

### Evaluation
Accuracy is about 90%
