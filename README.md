# Soccer Match Winner Prediction Model
This repository contains code for a machine learning model that predicts the winner of soccer matches from the Spanish soccer league (La Liga) using match data from the 2023-24 season.
## Project Steps:

1. Scraped historical match data with Python using the Requests library.
2. Parsed and cleand the data using the BeautifulSoup library.
3. Created a dataframe using the Pandas library.
4. Created initial predictors to train machine learning model.
5. Designed a RandomForestClassifier machine learning model using the Scikit-learn library.
6. Improved precision using rolling averages of 8 data categories.
7. Retrained model with increased precision.
