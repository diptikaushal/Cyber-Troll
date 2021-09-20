# Cyber-Troll Prediction Service

This is a web application designed to show the project structure for a machine learning model deployed using flask. This project features a machine learning model that has been trained to detect whether or not an online comment is a `Cyber-Troll` or `Non Cyber-Troll`. This application acts as an interface for a user to submit new queries. The machine learning model was built training Support Vector Machine (SVM) model.


The SVM and BoW models are used in the production and testing setting in order to be able to predict user-submitted queries, so they can be serialized via python's pickle functionality and stored within the `/model_assets` folder. 

In order to detect whether or not an online comment is from a cyber troll, you can visit https://cybertroll-dipti-101803601.herokuapp.com/ and submit the review, to recieve predictions through a simple user interface. 

I have applied a supervised learning model to perform binary classification on the given set of reviews. Accuracy is used to measure the performance of the trained model.

The dataset used for the training of the model has 20000+ reviews. The train accuracy is observed to be 0.97 and test accuracy is 0.85.

## Methodology

![](Methodology.png)
