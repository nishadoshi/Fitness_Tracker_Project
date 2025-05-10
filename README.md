Hi! This project was a capstone project for my data science major. 
This dataset was taken from kaggle: 
https://www.kaggle.com/datasets/jijagallery/fitlife-health-and-fitness-tracking-dataset/data

I perfomed general EDA first and then I focused on my main goal of the project: 
Can I reccomend a workout for a user given their health and fitness metrics? 

If we walked through this code, I first started with cleaning and organizing the data, changing baseline references and getting a better understanding of the data. 
Followed by clustering on my train data and splitting my data by acitvity type. 
I used linear regression for my model choice because most of my data showed linear relationships, there was no need to look further, even though I did try some other models
such as random forest to see if I am missing any underlying patterns. 
I then did analysis on my models and learned what is truly affecting my response variable (calories burned)
Clustered my test set and ran tests to reccomend a workout for a user. 
To note: Some important patterns were not being showing significant, such as age, so I had to consider tradeoff between certain health metrics and what would actually be a feasible workout for that person. 

Thank you! 
