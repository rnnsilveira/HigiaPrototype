# Higia Prototype - School of AI Health Hackathon 2019 - Campinas, Brazil

## Introduction

Lorem ipsum

## Real problem

Lorem ipsum

## Our solution

Lorem ipsum

## Hands on - Code

### How to train the model using CreateML

Open ModelTrainer.playground, start the project, set some parameters in order to enhance your model accuracy (# of Iteration, and Augumentation sub-sections), and then drag and drop your dataset sliptted into folder categories.

<img width="1552" alt="Screenshot 2019-03-31 at 02 03 49" src="https://user-images.githubusercontent.com/29995158/55285090-d5c30280-535a-11e9-8447-41df1d48403e.png">

After your model training is complete, just drag and drop your test set to evaluate your model.

<img width="1552" alt="Screenshot 2019-03-31 at 02 39 21" src="https://user-images.githubusercontent.com/29995158/55285237-60593100-535e-11e9-95ec-5c41a8e564f6.png">

As we had to create our own data set, it was limited. In order to improve the accuracy, we used a 5-fold cross validation method to get our best model.

### Minimum Viable Product (MVP)

Once we had our model, we were able to export it as a .mlmodel extension. This kind of extension can be converted to other common model as TensorFlow and then, be used on other platforms as well.

As we wanted to proof the concept building a MVP as an iOS app to demonstrate the potential use of this technology, we used the model just like it was.
