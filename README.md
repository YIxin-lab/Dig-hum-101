# Features of "Successful" Movies and Its Classifier 

![This is an image](https://miro.medium.com/max/1400/1*N0-ikjPv4RUVvS-6KCgLPg.jpeg)

## Research Questions ##
### 1.What are some of the features of the "successful" movies? ###
### 2. Is movie popularity a better representation for success of movie than the movies score? ###
### 3. What is the performance of the classifer with higher accuracy? ###

Abtract: This project explores the features of the "successful" movies and then build classfiers to see which metric is a good representation of movies' success. My project is innovative in the following ways: First, I define successful as business successful. If a movies makes double of its budget, I will give it a 1; otherwise, a 0. Second, to take the number of people voting of the movies into consideration, I also use weighted average. Average_score = 0.999 * average_vote + 0.001 * vote_count. Thus, the average score is more fair.
To find the features of the "successful" movies, I used data visualization. I made barplot for the average of popularity of "successful movies" and "unsuccessful movies", barplot of their average scoure, and the most common types of movies in "successful movies." I found that comedies, drama and comedy-romance are the most common three genres Successful movies tend to be more popular. Successful movies tend to have higher average_score. I then built two classifiers using logistic regreesion. One was trained on "popularity" and the other was trained on average_score. I found that average_score has a higher accuracy of 0.68 and is thus a better representation of whether a movies is successful or not. This might suggest some interesting phenomenon in the real world. Maybe popular movies spent more budget on marketing so it is not as succssful. Or people are more willing to pay for what they enjoy compared to what is trendy. My research project opens a floor for people to discuss further questions about movies and modern society.  

