# Python-Probability-And-Statistics
Python Probability And Statistics

Python Data Analysis and Visualizations using Pandas

We are going to explore multiple datasets:

1. Making predictions about wine quality using linear regression

2. Python Distribution And Sampling on Movie Reviews

We will be working on fandango_score_comparison.csv which was originally created from FiveThirtyEight Github account. Each row represents a single movie. Each column contains information about how the online moview review services RottenTomatoes, Metacritic, IMDB, and Fandango rated the movie. Typically, the primary score shown by the sites will be the Critic score. Here are descriptions of some of the relevant columns in the dataset:
FILM -- the name of the movie.
RottenTomatoes -- the RottenTomatoes (RT) critic score.
RottenTomatoes_User -- the RT user score.
Metacritic -- the Metacritic critic score.
Metacritic_User -- the Metacritic user score.
IMDB -- the IMDB score given to the movie.
Fandango_Stars -- the number of stars Fandango gave the movie.
Visualizing Conditional Plots
In this notebook, we will explore seaborn visualization library, which is built on top of matplotlib. Seaborn has good support for more complex plots, attractive default styles, and integrates well with the pandas library. We will work on a new Titanic dataset compiled by Kaggle. Overview: The data has been split into two groups: I.	train.csv: Contains data on 712 passengers II.	test.csv: Contains data on 418 passengers Each row in both data sets represents a passenger on the Titanic, and some information about them. We'll be working with the train.csv file, because the Survived column, which describes if a given passenger survived the crash, is preserved in the file. The column was removed in test.csv, to encourage competitors to practice making predictions using the data. Here are descriptions for each of the columns in train.csv: • PassengerId -- A numerical id assigned to each passenger. • Survived -- Whether the passenger survived (1), or didn't (0). • Pclass -- The class the passenger was in. • Name -- the name of the passenger. • Sex -- The gender of the passenger -- male or female. • Age -- The age of the passenger. Fractional. • SibSp -- The number of siblings and spouses the passenger had on board. • Parch -- The number of parents and children the passenger had on board. • Ticket -- The ticket number of the passenger. • Fare -- How much the passenger paid for the ticker. • Cabin -- Which cabin the passenger was in. • Embarked -- Where the passenger boarded the Titanic.

3. Python probability and statistics using chi-squared tests

We will be working on jeopardy dataset to find out patterns in the questions that could help to win. Each row in the dataset represents a single question on a single episode of Jeopardy. Here are explanations of each column:
Show Number -- the Jeopardy episode number of the show this question was in.
Air Date -- the date the episode aired.
Round -- the round of Jeopardy that the question was asked in. Jeopardy has several rounds as each episode progresses.
Category -- the category of the question.
Value -- the number of dollars answering the question correctly is worth.
Question -- the text of the question.
Answer -- the text of the answer.

4. Python Probability and Statistics using Scipy Library

5. We will work on dataset from NBA. 

Here are some of the columns in the dataset:
player - The player's name
pts - The total number of points the player scored
ast - The player's total number of assists
fg - The player's field goal percentage for the season

6. Probability and Statistics in Python

In this dataset, we will describe and understand the dataset using Pthon python Probability and Statistics libraries. We are going to work on FiveThirtyEight team dataset on Movies critics scores and site's user scores. These scores are aggregated and the average score from both groups are included for each movie. We will be working on fandango_score_comparison.csv, which you can download from FiveThirtyEight Github repo. 
Here are some of the columns in the dataset:
FILM - film name.
RottenTomatoes - Rotten Tomatoes critics average score.
RottenTomatoes_User - Rotten Tomatoes user average score.
RT_norm - Rotten Tomatoes critics average score (normalized to a 0 to 5 point scale).
RT_user_norm - Rotten Tomatoes user average score (normalized to a 0 to 5 point scale).
Metacritic - Metacritic critics average score.
Metacritic_user_nom - Metacritic user average score (normalized to a 0 to 5 point scale).
Metacritic_norm - Metacritic critics average score (normalized to a 0 to 5 point scale).
Fandango_Ratingvalue - Fandango user average score (0 to 5 stars).
IMDB_norm - IMDB user average score (normalized to a 0 to 5 point scale).
Lets focus on the normalized user scores for now and generate histograms to better understand each sites distributions.
