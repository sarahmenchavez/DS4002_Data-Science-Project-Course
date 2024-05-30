# Project name and introduction
Data Science Barbie: Chick Flicks and Data Tricks<br>
Mary Ellen Schuster, Sarah Menchavez, Elizabeth Peterson<br>
DS 4002 Project 1<br>

## Software and platform
To perform this analysis, we used a python environment in Virtual Studio code.<br>
The platform used was MacOS.<br>
The add-on packages needed are: 
- import pandas as pd
- import nltk
- from sklearn.model_selection import train_test_split
- from sklearn.linear_model import LinearRegression
- from sklearn.metrics import mean_squared_error, r2_score
- from nltk.sentiment.vader import SentimentIntensityAnalyzer
- from nltk.corpus import stopwords<br>
## Documentation map
LICENSE: gives instructions on how to use and cite this repository<br>
<br>
README.md: guidebook for navigating this repository<br>
<br>
assignment_1.ipynb: all of our data inputting, cleaning, analyzing, and visualizing for this project<br>
<br>
barbie_Cleaned.csv: the cleaned barbie review dataset<br>
<br>
barbie_data.csv: the raw barbie review dataset<br>
<br>
barbie_data_vader_scores.csv: the cleaned barbie review dataset with the VADER score column<br>
<br>
packages.txt: packages needed for installation<br>
<br>
words.txt: dictionary of words used for training <br>

## Instructions for reproduction
To reproduce our results: <br>
- Read in and clean barbie review data set until you have two columns: written review and number rating<br>
- Use spacy to extract and identify most common adjectives in the reviews<br>
- Apply VADER sentiment analysis to the reviews and add the VADER score as a column to the dataset<br>
- Apply a linear regression model to the data to see if the VADER scores correlate to the user's number rating<br>
- Use the R^2 and Mean Squared Error values to determine the efficacy of the model <br>
