# Space_X_Falcon_9
### Space X Falcon 9 First Stage Landing Prediction

In this capstone, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website, with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

### Data collection with Webscraping and Data wrangling
In this lab, you will make a get request to the SpaceX API. You will also do some basic data wrangling and formating. You will be performing web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled `List of Falcon 9 and Falcon Heavy launches`
https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches

#### _Objectives_
 * Write Python code to manipulate data in a Pandas data frame.
 * Convert a JSON file into a Create a Python Pandas data frame by converting a JSON file
 * Create a Jupyter notebook and make it sharable using GitHub
 * Use data science methodologies to define and formulate a real-world business problem.
 * Use your data analysis tools to load a dataset, clean it, and find out interesting insights from it.

For more details: 
  * 001_jupyter_labs_spacex_data_collection_api.ipynb
  * 002_jupyter_labs_spacex_webscraping.ipynb

### Exploratory Data Analysis (EDA)
Make use a RESTful API and web scraping. Convert the data into a dataframe and then perform some data wrangling.

#### _Objectives_
 * Create scatter plots and bar charts by writing Python code to analyze data in a Pandas data frame
 * Write Python code to conduct exploratory data analysis by manipulating data in a Pandas data frame
 * Write and execute SQL queries to select and sort data
 * Use your data visualization skills to visualize the data and extract meaningful patterns to guide the modeling process.

For more details: 
  * 003_jupyter_labs_spacex_data_wrangling.ipynb
  * 004_jupyter_labs_EDA_sql_sqllite.ipynb

### Predictive Analysis(Classification)
In this module, we'll use machine learning to determine if the first stage of Falcon 9 will land successfully. Data will be split into training data and test data to find the best Hyperparameter for SVM, Classification Trees, and Logistic Regression. Then find the method that performs best using test data.

#### _Objectives_
 * Split the data into training testing data.
 * Train different classification models.
 * Hyperparameter grid search.
 * Use your machine learning skills to build a predictive model to help a business function more efficiently.

For more details: 
  * 007_jupyter_labs_Machine_Learning_Prediction.ipynb

### Interactive Visual Analytics and Dashboards
Build a dashboard to analyze launch records interactively with Plotly Dash as well as build an interactive map to analyze the launch site proximity with Folium python Library.

#### _Objectives_
 * Build an interactive dashboard that contains pie charts and scatter plots to analyze data with the Plotly Dash Python library
 * Calculate distances on an interactive map by writing Python code using the Folium library
 * Generate interactive maps, plot coordinates, and mark clusters by writing Python code using the Folium library
 * Build a dashboard to analyze launch records interactively with Plotly Dash.
 * Build an interactive map to analyze the launch site proximity with Folium.
 
For more details: 
  * 005_jupyter_labs_EDA_dataviz.ipynb
  * 006_jupyter_labs_launch_site_location.ipynb  
  * 008_python_spacex_dash_app.py 
  
### Final Report
  * CG_Data_Science_Capstone_Presentation.pdf 
