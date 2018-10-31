# Udacity data science nanodegree project for classifying disaster messages with machine learning

### Motivation:
This project has been conducted as a part of Udacity's Data Scientist Nanodegree. The Students were to build:
- An ETL pipeline to load csv files, transform and clean data and load to a sql database.
- A Machine learning pipeline 
- A web app that puts it all togheter and displays some visualisations for the data and predict categories for new messages

### Web
The complete project can be seen on www.brønstad.com/disaster

### Installations:
- python 3.6
- Flask
- numpy
- pandas
- sklearn
- nltk
- sqlalchemy
- re
- seaborn
- pickle

### Instructions
Run the following commands in the root directory.
1. Run the ETL pipeline to load data from csv files, clean and load into a database as specified in the third arg
 - python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db

2. Run a ML pipeline to trains and saves a model
 - python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl

3
 - Go to http://0.0.0.0:3001/

### Files:
The project contains a jupyter notebook for the ETL pipeline aswell as on for the ML pipeline.
a folder with data, 1 folder for the webapp and a folder for the model


### Licensing, Authors, Acknowledgements, etc.
Thanks to Figure Eight for the dataset



