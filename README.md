# moushumi_portfolio
# Project 1: [Bird Image Classifier](https://github.com/moushumi-das/Deep_learning)
For this Data Science project I have used deep learning for image classification.

## Data
I have used the following chrome extention to download the data from google images. [Fatkun Batch Download Image](https://chrome.google.com/webstore/detail/fatkun-batch-download-ima/nnjjahlikiabnchcpehcpkdeckfgnohf?hl=en)

## Overview 
In this project, I have built a bird classsifier to itentify singing bird from different part of the world. This could be useful for someone who is interested to know about singing birds. They could take picture of a bird and an app could provide the some information about those singing birds. This is the underlying model for building something with those capabilities. 

After minimal tuning, I was able to get the model to predict the bird's type with 93% accuracy. In most of the cases this would meet the need of an end user of the app. In order to get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results.



![](./Netflix/top_countries.png) 
![](./Netflix/rating.png)
![](./Netflix/movie_duration.png)

# Project 2: [Image_Classifications_With_OpenCV](https://github.com/moushumi-das/Image_Classifications_With_OpenCV)
For this Data Science project I have used OpenCV python  for image classification.

## Data
For this project, I have made my own dataset by scraping google image using the [Fatkun Batch Download Image](https://chrome.google.com/webstore/detail/fatkun-batch-download-ima/nnjjahlikiabnchcpehcpkdeckfgnohf?hl=en) chrome extention.

## Objective: 
In this project, I have built a image classsifier to itentify the image of female tennis players.

**Steps:**
   1. Get Data: We need data to train our model. 
   2. Prepare Data: Clean, normalize, and get data in a form that we can feed into our model
   3. Train Model: Trained data using Support Vector Classification(SVC), Logistic Regression, and Random Forest Classification
   4. Evaluate model performance
   5. Parameter tuning
