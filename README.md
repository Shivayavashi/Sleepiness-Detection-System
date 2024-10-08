# Sleepiness-Detection-System :sleeping:

The sleepiness detection model is developed with python programming language.Convolutional Neural Networks is a type of artificial neural network which is most popularly used for image and object classification.The detection system is built using 3 models - dlib and open-cv , 3 layer CNN model ,4 layer CNN model. These models are developed in visual studio and then the best model is found to be the 4 layer CNN model which gives the maximum accuracy of 96% with low training and validation loss.

Technologies used: <br>
1.Kaggle kernel- It is used to build the CNN models for the sleepiness detection system.<br>
2.Visual studio - It is used to build the 3 py models for the System. <br>
3.Python 3.9.6 <br>

Dataset used : 
https://www.kaggle.com/datasets/serenaraju/yawn-eye-dataset-new

<li> Dlib model:Dlib's shape detector is used to map the coordinates of the facial landmarks of the input video and drowsiness detected by monitoring aspect ratios of eyes and mouth.The maximum accuracy obtained for the Dlib model is 95%. </li>
<li>3 layer CNN model:
The maximum accuracy obtained from the 3 layer Sequential CNN model is 99% for the training dataset and 95% for the testing data.</li>
<li>4-layer CNN model:
The maximum accuracy obtained by the 4 layer Sequential CNN model for both the training and testing data is 97% and on an average the accuracy was 96%.</li>
