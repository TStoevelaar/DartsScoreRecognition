# DartsScoreRecognition
![Android Dev Challenge Banner](https://github.com/TStoevelaar/DartsScoreRecognition/raw/master/img/androidDevChallenge.png "Android Dev Challenge")
## Tell us what your idea is. 
---
*Darts is a great sport but for some people calculating the scores can be hard. The idea is to use the camera of your smartphone to “scan” the dartboard and recognize the score. This way a darts game could be tracked by your smartphone and you only have to focus on playing the game.*

## Tell us how you plan on bringing it to life. 
---
*The idea originated from my graduation project for the higher professional education study in software engineering. During this project I researched the possibilities of using ML for recognizing darts scores and I developed a prototype of the system.*

*The prototype used a keypoint detection model, based on TensorFlow’s PoseNet, to detect the location of the darts and the dartboard in the image from the camera. Using a perspective transform the location of the darts in the dartboard is calculated and used to calculate the score.*

*To train the model a tool was developed in unity to generate images of random darts scores. This tool generates around 1000 images in 1 minute. However the images are too consistent and need some processing to be used for training.*

*The model was developed with TensorFlow in Google Colab and converted to TensorFlow Lite to run on Android. The model did not generate the needed accuracy to use it to track an entire darts game. However the idea of using keypoint detection to locate the darts and the dartboard worked.*

***How I could use Google’s help:***

- By reviewing the way ML is used to recognize the darts score.
- By advising ways to optimise the ML model
- By advising ways to improve the dataset for the model

***Timeline:***

***November 2019:***

- Researching ways to improve the accuracy of the model

***December 2019:***

- Prototyping ways to improve the model accuracy

***January 2020:***

- Developing an improved keypoint detection model
- Improving the dataset for training

***February 2020:***

- Reviewing the model with the help of Google
- Reviewing the dataset with the help of Google
- Revising the model
- Revising the dataset

***March 2020:***

- Developing the Android application
- Implementing the TensorFlow Lite model

***April 2020:***

- Beta testing the Android application
- Finalising the Android application

## Tell us about you. 
---
*My name is Thomas Stoevelaar and I’m a 21 years old junior software developer from the Netherlands. I graduated higher professional education software engineering in July 2019 with the prototype of this project. I like playing darts which is why I chose this as the subject of my graduation project. I always liked to search ways to use software in darts and that is how I decided to use Machine Learning to recognize darts scores.*