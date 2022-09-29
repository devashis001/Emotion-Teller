# Emotion-Teller
# Emotion_Recognition--Neural-Networks::[68.68% Validation Accuracy]
Human facial expressions can be easily classified into 7 basic emotions: happy, sad, surprise, fear, anger, disgust, and neutral. Our facial emotions are expressed through activation of specific sets of facial muscles.
* The aim is to classify the emotion on a person's face into one of **seven categories**, using deep convolution neural networks.
* The algorithm is based on the type of database used inorder to get maximum validation accuracy. Further changes in algorithm may be required according to the database used.

# Dependencies
1. NumPy
2. Keras
3. Pandas
4. Tensorflow (as backend)
5. Jupyter
6. openCv2

# Important Components
* Download the fer2013.tar.gz file from [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
* Move the downloaded file to the datasets directory inside this repository.
* Trained model Face Detection -> [haarcascade_frontalface_default.xml]
* Trained model JSON -> [model1.h5]
