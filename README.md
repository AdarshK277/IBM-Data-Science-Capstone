# IBM-Data-Science-Capstone
My submission of IBM Data Science Capstone Project - SpaceX Falcon 9 First Stage Landing Prediction.

## About the Project - SpaceX Falcon 9 First Stage Landing Prediction
In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

## Project Flow
### 1. Data Collection Using SpaceX REST API
* Collecting required data from an API.
* Performing some basic data wrangling and formatting.

### 2. Data Collection Using WebScraping (Optional)
* Webscrape a Falcon 9 launch record HTML table from Wikipedia using BeautifulSoup.
* Parsing the table and convert it into a Pandas DataFrame.

### 3. Data Wrangling
Performing some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models.
* Exploratory Data Analysis (EDA).
* Determine training labels.

### 4. Exploratory Data Analysis Using SQL
* Exploratory Data Analysis (EDA).
* Load the dataset into the corresponding table in a Db2 database.
* Execute SQL queries to answer questions and gain insight.

### 5. Exploratory Data Analysis, and Feature Engineering Using Pandas, and Data Visualization Using Matplotlib and Seaborn
* Performing EDA and Feature Engineering using Pandas.
* Performing Data Visualization using Matplotlib and Seaborn.

### 6. Interactive Visual Analytics and Dashboards
* Launch site location analysis using Folium.
* Creating interative dashboards using Plotly Dash.

### 7. Machine Learning - Classification
* Create a column for the class.
* Standardize the data.
* Split into training and testing data.
* Find the best Hyperparameter for SVM, Classification Trees and Logistic Regression.
* Find the method which performs best using test data.
