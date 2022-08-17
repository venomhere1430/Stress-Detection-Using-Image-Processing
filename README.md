# Stress-Detection-Using-Image-Processing
The main motive of our project is to detect stress using vivid Machine learning and Image processing techniques. Stress can place one at higher risk for diabetes, ulcers, asthma, migraine headaches, skin disorders, epilepsy, and sexual dysfunction In this project we try to go in the depth of this problem by trying to detect the stress patterns of people. we would like to apply image processing and machine learning techniques to analyze stress patterns and to narrow down the factors that strongly determine the stress levels. Machine Learning algorithms like CNN classifiers are applied to classify stress. Image Processing is used at the initial stage for detection, the person’s image is clicked by the camera which serves as input. By taking input as an image from video frames and output may be image or characteristics associated with that image.Real time face stress detection model. The model is image processing based model which is having two parts:Emotion Recognition,Stress level calculation The emotion recognition model will return the emotion predicted real time. The model classifies face as stressed and not stressed. A model is trained on the fer2013 dataset.The stress level is calculated with the help of eyebrows contraction and displacemnent from the mean position. The distance between the left and right eyebrow is being calculated and then the stress level is calculated using exponential function and normalized between 1 to 100.


###########################################################################
before executing our eyebrow_detection.py download below .dat file :::::
https://drive.google.com/drive/u/1/folders/1UqD4OS7_32l7hn6gMorlttwQJURfTGwl
###########################################################################

DESCRIPTION :
# 1) by using CNN algorithm we are trained our model {_mini_XCEPTION.102-0.66.hdf5} .... based on this trained model we are identifying emotions
# 2) based on those emotions we are predicting whether the person is under stress | not
# 3) and finally calculating the stress levels of a person based on distance b|w  eyebrows
