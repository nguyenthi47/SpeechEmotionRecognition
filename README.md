#SPEECH EMOTION RECOGNITION

This project build a machine learning model to classify emotion from audio file. This project extracts the emotion from audio which is helpful to bring a better customer services through voice call, marketing strategies based on consumers voice features, or alert system for people to control their emotion when they are speaking

##**Technical approach:**
Extracting features from audio files (MCFFs), fetching these features into a Convolution Neural  Network to classify speech emotion into 5 categories which are calm, happy, angry, fearful, sad.
Dataset: RAVDESS (speech)
  (80% for training, 20% for testing)
Audio files characteristics and feature extraction
  Sample rate: 44100Hz
  Foe each audio, using LibROSA to extract the sound mfccs features.
  https://miro.medium.com/max/1400/1*0b1UYIC-tP-TpPmAOudwLQ.png
  @Jonathan Hui

