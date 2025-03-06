# Sign-Language-Alphabet-Detector
Built a Sign Language Alphabet Detector using Machine Learning and Computer Vision to recognize and classify hand signs in real time. This project leverages Python, OpenCV, and TensorFlow/Keras to train a model on sign language alphabets, enabling seamless communication for individuals with hearing impairments.

Structure:
Sign-Language-Alphabet-Detector
|-collect_imgs.py
|-create_dataset.py
|-inference_classifier.py
|-train_classifier.py
|-data(folder)

Libraries that are used:
+ opency-python
+ scikit-learn
+ mediapipe
+ matplotlib
+ pickle
+ numpy

Steps to use this ML model:
---------------------------

1) Clone the repository.
2) Open the folder in any IDE you prefer, but i recommend Pycharm.
3) Create a new folder named data, which we will use later to capture images, label them and train the model with.
4) after that run the collect_imgs.py file to capture images of you, these data will be used to train the model.(use sign language alphabets, and capture them properly otherwise it would lead to errors)
5) After you have captured the data it would store them in the data folder, you can view them as 0,1,2 folders.
6) Now run the create_dataset.py file it would label the images you captured and create your very own dataset to use.
7) Now you will see a new file named data.picle, this would be used to train the model.
8) After you have successfully created the dataset, run the train_classifier.py to train the model according to the dataset you have created.
9) Again you will see a new file named model.p.
10) After completing every step now you can run the inferences_classifier.py it would use the model.p file and detect the hand gestures.
11) You can adjust the number of classes(how many alphabet letters), which camera to use.
12) Enjoy!

Thank You!
Contact:
linkedIn - www.linkedin.com/in/raheesh-ramsy-19897b294
Email - ramzyraheesh@gmail.com
WhatsApp - +94 074 220 9477



