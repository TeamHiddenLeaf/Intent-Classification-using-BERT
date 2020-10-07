# Intent-Classification-using-BERT


![1_3nys8S3J6vFCPmu8uQW8Wg](https://user-images.githubusercontent.com/66754032/95029977-bef91c80-0671-11eb-9c07-243884af9150.png)

- Recognizing intent (IR) from text is very useful these days. Usually, you get a short text (sentence or two) and have to classify it into one (or multiple) categories.

- Multiple product support systems (help centers) use IR to reduce the need for a large number of employees that copy-and-paste boring responses to frequently asked questions. Chatbots, automated email responders, answer recommenders (from a knowledge base with questions and answers) strive to not let you take the time of a real person.

- This repo will show you how to use a pre-trained NLP model that might solve the (technical) support problem that many business owners have. I mean, BERT is freaky good! It is really easy to use, too!

# In our project, we have utlized following intents: 

- SearchCreativeWork (e.g. Find me the I, Robot television show)

- GetWeather (e.g. Is it windy in Boston, MA right now?)

- BookRestaurant (e.g. I want to book a highly rated restaurant for me and my boyfriend tomorrow night)

- PlayMusic (e.g. Play the last track from Beyoncé off Spotify)

- AddToPlaylist (e.g. Add Diamonds to my roadtrip playlist)

- RateBook (e.g. Give 6 stars to Of Mice and Men)

- SearchScreeningEvent (e.g. Check the showtimes for Wonder Woman in Paris)

# Dataset & Model Training:

- We have utilized 13,784 records for model training.

- We have trained the model through 5 epochs with 12405 samples in each epoch (0.9915 accuracy).

- The model has performed pretty well with a test accuracy of 0.9771.

# Prediction Snapshot

<img width="547" alt="Capture" src="https://user-images.githubusercontent.com/66754032/95029943-92dd9b80-0671-11eb-8e10-7c67b4e82557.PNG">

#### Credits: Venelin Valkov

Happy Coding!

