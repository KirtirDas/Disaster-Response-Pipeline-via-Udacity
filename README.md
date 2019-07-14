



			Disaster Response Pipeline Project
Table of Contents:

I. Objective
II. Dependencies
III. Executing Program
IV. Screenshots

I. Objective:

This Project is part of Data Science Nanodegree Program by Udacity. The initial dataset is a collection of different tweets and messages from real-life disaster. The objective of the project is to build a web application which will help to categorize messages.

The Project is divided into 3 Sections as below:

Data Processing, ETL Pipeline to extract data from source, clean data and save them in a proper databse structure
Machine Learning Pipeline to train a model able to classify text message in categories
Web App to show search result for appropriate category in real time.

II. Dependencies:

Python 3.5+ (I used Python 3.7)
Machine Learning Libraries: NumPy, SciPy, Pandas, Sciki-Learn
Natural Language Process Libraries: NLTK
SQLlite Database Libraqries: SQLalchemy
Web App and Data Visualization: Flask, Plotly

III. Executing Program

1. Run the following commands in the project's root directory to set up your database and model.

    - To run ETL pipeline that cleans data and stores in database
        `python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db`
    - To run ML pipeline that trains classifier and saves
        `python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl`

2. Run the following command in the app's directory to run your web app.
    `python run.py`

3. Go to https://view6914b2f4-3001.udacity-student-workspaces.com
Execute the url in web browser it displays the webpage to search category for appropriate section.

4. Screenshots:
The web URL and search result screen is attached into the repo for reference.
