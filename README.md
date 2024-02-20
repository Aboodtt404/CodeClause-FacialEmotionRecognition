# Emotion_detection_with_CNN

### Packages need to be installed
- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow
- pip install kaggle

### Train Emotion detector
- command --> python TranEmotionDetector.py

It will take several hours depends on your processor. (On i7 processor with 16 GB RAM it took me around 4 hours)
after Training , you will find the trained model structure and weights are stored in your project directory.
emotion_model.json
emotion_model.h5

copy these two files create model folder in your project directory and paste it.

### run your emotion detection test file
python TestEmotionDetector.py
