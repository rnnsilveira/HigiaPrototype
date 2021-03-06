# Higia Prototype - School of AI Health Hackathon 2019 - Campinas, Brazil

## Introduction

Increasingly, hospitals are focusing on the improvement of quality indicators. Monitoring of hand hygiene is part of this quality improvement process. **Hand hygiene is widely regarded as the most effective preventive measure for health care-associated infection**. According to the WHO, **hospital infections can kill up to 2.3M people every year**, hand washing would be able to reduce infection cases by 70% and bed availability can be increased up to 40% and grant an **economic burden of €13–24 billion year**.

Hospitals generally use observers to monitor hand hygiene because direct observation is considered the criterion standard for evaluating hand hygiene compliance. However, **direct observation is generally able to capture only a very small fraction of hand hygiene opportunities**. Observers typically use relatively short observation periods and electronic counters, on the other hand, record 24 hours per day and offers an extra safe guard to the process.

## Our solution

![AppIcon](https://user-images.githubusercontent.com/29995158/55290443-cfa84280-53a9-11e9-86a4-cd3b8f6a9bee.png)

We built a product that is able to identify the hand wash efficiency using AI and is also able to evaluate the hand hygiene complience. 

## Business

The simple gesture of properly wash the hands will impact on the availability of beds in the ICU and it also moves around $9 to $21 B accourding to the World Health Organization.

We have a scalable model to fit the demands of our client. We will charge $0.50 per check and from our calculations, we will have 20% gross profit.

We only have on competitor, Infectrack, but their solution do not support bacterial check, neither the guarantee of hands washed.

## Hands on - Code

### How to train the model using CreateML

Open ModelTrainer.playground, start the project, set some parameters in order to enhance your model accuracy (# of Iteration, and Augumentation sub-sections), and then drag and drop your dataset sliptted into folder categories.

<img width="1552" alt="Screenshot 2019-03-31 at 02 03 49" src="https://user-images.githubusercontent.com/29995158/55285090-d5c30280-535a-11e9-8447-41df1d48403e.png">

After your model training is complete, just drag and drop your test set to evaluate your model.

<img width="1552" alt="Screenshot 2019-03-31 at 09 56 01" src="https://user-images.githubusercontent.com/29995158/55289294-3bcf7a00-539b-11e9-919c-b9135d32a439.png">

After evaluation, our model was 79% accurate. This level of accuracy can be explained by the limited dataset, all data was created by us during the night. In order to improve it, we also used a 5-fold cross validation method to get our best model.

### Minimum Viable Product (MVP)

Once we had our model, we were able to export it as a **.mlmodel** extension. This kind of extension can be converted to other common models, like TensorFlow, and then, be used on other platforms as well.

As we wanted to proof the concept building a MVP as an iOS app to demonstrate the potential use of this technology, we used the model just like it was.

Now it is time to check how the MVP behaves.

If your hand is clean, you are allowed to get in!

![Yes 2019-03-31 11_45_01](https://user-images.githubusercontent.com/29995158/55290639-19922800-53ac-11e9-9dd9-f1c6bcf635e4.gif)

If your hand is dirty, sorry, but you will have to wash it!

![NoLast](https://user-images.githubusercontent.com/29995158/55290751-7c37f380-53ad-11e9-8711-c170805b25d0.gif)

### Road map

For the next steps, we would like to make it more scalable, in a more afordable hardware and integrate it to a cloud platform, where the client is able to check the data in real time.

### About the team - Higia

**Alex** - Business

**Alice** - Healthcare

**Renan** - AI/Dev

**Thaís B.** - Business

**Thaís H.** - Design


