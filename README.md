# Recommendation Engine - suggesting similar apps to users based on their search interest on Google Play Store.
As part of this project, I have created a content based Recommendation Engine for suggesting similar apps to users based on their app search on Google Play store.

From customer's interest standpont, the key question that I have tried to answer is:
Are there any similar apps that I may be interested in?
An answer to the above question can be of huge benefit to the organization. If a customer is satisfied with our recommendation,
we will have greater number of hits and downloads for that app. It will be an opportunity for generating more revenue. 

The dataset contains app details from Google Play Store till February 2019.

## Table of Contents

* General Info
* Variable Description
* Screenshots
* Technologies and Methods
* Status
* Contact

## General Info

The reference to the dataset was obtained from [kaggle](https://www.kaggle.com/lava18/google-play-store-apps). There are a total of 2 datasets:
* Details of the Apps from Google Play Store
* First 100 most relevant reviews for majority of the app

## Variable Description

The App data set containing App details has 13 variables. The variable names and the description is mentioned below:
  - App:            Name of the App
  - Category:       Category of the App
  - Rating:         Average rating of the App
  - Reviews:        Total Number of reviews for the App
  - Size:           Size of the App when downloaded from Google Play
  - Installs:       Total Number of Installs
  - Type:           Whether Free or Paid app
  - Price:          Price of the App
  - Content Rating: Age Group the App is targetted at 
  - Genres:         Category the app belong to
  - Last Updated:   Date last updated
  - Current Ver:    Current Version of the App
  - Android Ver:    Base version of Android.

The Reviews data set containing top 100 reviews for apps has 5 variables. The variable names and the description is mentioned below:
  - App: Name of the App
  - Translated Review:      The user review for that App
  - Sentiment:              Sentiment of the user's review
  - Sentiment_Polarity:     Sentiment Polarity Score
  - Sentiment_Subjectivity: Sentiment Subjectivity Score
  
 ## Screenshots
 
 The below screenshot shows the generation of similar apps when "3D Bowing" is provided as input:
 
 ![Similar Apps for 3D Bowling](https://github.com/Sarthak-Mohapatra/Recommendation-Engine-for-apps-from-Google-Play-Store/blob/master/output%20ss.JPG)
 

## Technologies and Methods

* Python (Pandas, Numpy, Scikit-Learn)
* Microsoft Excel
* Content Based Recommendation
* Jupyter Notebook

## Status

Project is: *finished*

## Contact

If you loved what you read here and feel like we can collaborate to produce some exciting stuff, or if you just want to shoot a question,
please feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/sarthakmohapatra1990/) or email me [E-Mail](sarthakmohapatra1990@gmail.com).
