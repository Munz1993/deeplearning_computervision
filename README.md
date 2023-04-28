# deeplearning_computervision
analysis_of_correlation_between_inclass_emotion_and_academici_performance

This project is an ongoing research project based on computer vision libraries like TensorFlow, Keras, PyTorch, OpenCv etc
The objective of the project is to analyze if there exists a relationship between in-class emotion of students and their academic performance.

The correlation analysis is being conducted based on aggregate class attendance, not on individual basis. 
That is to say, emotion for all the students of a given class is assessed when a particular concept/topic is being taught to them.
Then that aggregate emotion value is being correlated with their average assignment scores for that particular concept/topic.

Following models have been used so far:
Face Detection
YOLO Version 3
HOG Face Detection
HaarCascade

Emotion Recognition
MobileNet

Data Preprocessing
2 Videos used for Analysis, more will be added later
Video Frames divided according to session info
Each session further subdivided into Begin, DOM, End in order to observe transition of emotion from beginnig to end when a particular concept is being delivered.
Frame for each of subsession extracted 

So far there is no correlation evident. The project is still going on.
