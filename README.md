# twitter_project

------------



## Description

This is a tweet sentiment analysis project. The aim of this project is to load a database, clean and filter the data for further analysis. First, we will review the type of data we have and remove null values. Afterwards, we will get rid of unnecessary data and then use charts to visualize the percentage of positive, negative, and neutral tweets by user age, country, and time of day. Finally, we will use the "text" column to filter and tokenize it to build a predictive model that can take a sentence and predict whether it is positive, negative, or neutral. We will also obtain a corpus with the vocabulary from the database and the relationship between the words to find similar words.

- This project aims to clean a table of tweets for subsequent analysis, create graphs, and develop a predictive model to determine whether a phrase is positive, negative, or neutral.
- Installation: You will receive a `.whl` file that you will need to upload to Google Colab (`/content/packages`). Then, run the following code to install the package: 
pip install my_package==1.0.0 --find-links=/content/packages
Then you can install the requirements: pip install -r requirements.txt.
- Usage: Follow these steps to use the package in the correct order:
*Loading and Reviewing: Use the loading_reviewing code to load the .csv document and review all the information.
*Removing Data: Use the removing_data code to delete all columns and rows that are not needed for the rest of the analysis.
*Visualizing Data: Use the visualizing_data code to generate graphs showing the differences in the information about the tweet authors (country, age, and time of day).
*Tokenizing and Training: First, use the tokenizing code to tokenize the text and perform an initial analysis with a WordCloud.
Then, proceed to the train_test part to develop a predictive model based on our vocabulary. Optionally, use the similarity script to find similar words.


### Owner
- Rocio Martinez Veloso <rmartinezveloso@gmail.es>
