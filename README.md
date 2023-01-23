# CONUHACKS2023-Eco Friendly
Participation in Conu Hacks 2023  
By: Siddhesh Mishra, [Devin Kuriya](https://github.com/devinkuriya), [Rahat Bhatti](https://github.com/bhattirahat)
## What it does?

Our Flutter app allows a user to take a picture of an object. This image is then sent to our trained Machine Learning model deployed on Microsoft Azure. This model will then return to us the probability of the object being recyclable, compostable, or landfill. The app returns the highest probability option to the user in the form of an alert.  

## How we built it  

We built our project using Flutter SDK for the mobile application. This was used so the app could be cross-platform for both IOS and Android. We also used Microsoft Azure to train a Machine Learning Model for image processing.  

## Challenges we ran into  

One of the challenges we faced was sending a POST request from our flutter application to the model for the image to be processed. Another challenge we faced was when trying to send our data to the MongoDB database to store the data received so that it could be then graphed using Grafana and then embedded into the application. We also tried to make a web application but the app kept crashing and due to fatigue and no sleep for 24 hours, we had no choice but to stop that and get some rest.  

## Accomplishments that we're proud of?  

We are very proud that the mobile application is fully functional and gives us the information we need were trying to get out of it. We are also very proud of having set up our Image processing model and trained our model with over 300 images and over 8 hours of training time.  

## What we learned?

We learned how to use Microsoft Azure and realized how easy it is to set up and can be used in so many different amazing projects. We also learned a lot about big data visualization from DRW using Grafana. We also learned a lot about Flutter application development.  

What's next for Eco Friendly?  

We would like to implement authentication and scale our application to multiple users. We would also like to show the user their past results and see how much of the different types of trash they have thrown in the past.  

## Built With:

