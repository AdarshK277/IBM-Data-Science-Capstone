# IBM-Data-Science-Capstone
My submission of IBM Data Science Capstone Project

## About the Project
In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

## Project Flow
### 1. Data Collection Using SpaceX REST API
* Collecting required data from an API.
* Performing some basic data wrangling and formatting.

### 2. Data Collection Using WebScraping (BeautifulSoup)
* Extract Falcon 9 launch records HTML table from Wikipedia.
* Parse the table and convert it into a Pandas DataFrame.

### 3. Data Wrangling
Performing some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models.
* Exploratory Data Analysis
* Determine training labels.
