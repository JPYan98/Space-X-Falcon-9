# Space-X-Falcon-9
This project analysis the successgul landing of Falcon 9 first stage, and provides insight on how the rocket performs.

## Summary of methodologies
In this capstone project, we utilized a variety of methodologies to predict the successful landing of the Falcon 9 first stage. We started by collecting and wrangling data using RESTful APIs and web scraping, converting the information into a Pandas DataFrame for analysis. We conducted exploratory data analysis with Matplotlib and Seaborn to visualize data patterns and relationships. SQL was employed for efficient data extraction and manipulation. Interactive dashboards and maps were created using Plotly Dash and Folium to analyze launch records and site proximities. Finally, machine learning techniques, including SVM, classification trees, and logistic regression, were used to train and optimize models for predicting landing success, with hyperparameter tuning conducted through grid search to identify the best performing model.

## Summary of all results
The project revealed several key insights about Falcon 9 first-stage landings. Data collection through APIs and web scraping provided comprehensive datasets, which were cleaned and prepared for analysis. Exploratory data analysis identified significant patterns, such as the impact of launch site and payload mass on landing success. Interactive visualizations highlighted these patterns effectively. Machine learning models were trained to predict landing outcomes, with the logistic regression model showing the highest accuracy. This model's predictions suggest that specific conditions, like favorable weather and optimized payload weights, greatly enhance the probability of successful landings, providing valuable insights for optimizing launch operations and competitive bidding against SpaceX.

## Methodology
Data collection methodology:
~Data was collected using RESTful APIs and web scraping techniques, then organized into a Pandas DataFrame for analysis. 
Perform data wrangling
~The data was processed by cleaning and wrangling it using Python and Pandas to handle missing values and inconsistencies, ensuring it was ready for analysis. 
Perform exploratory data analysis (EDA) using visualization and SQL
~EDA was performed using visualization tools like Matplotlib and Seaborn, alongside SQL queries, to uncover patterns and insights within the data.
Perform interactive visual analytics using Folium and Plotly Dash
~Interactive visual analytics were conducted using Folium and Plotly Dash to create dynamic maps and dashboards that facilitated an in-depth analysis of launch site proximities and launch records. 
Perform predictive analysis using classification models
~Predictive analysis was conducted using classification models, including SVM, classification trees, and logistic regression, by building, tuning, and evaluating these models through hyperparameter optimization and performance testing on training and testing datasets.

## Data Collection Flowchart
Initiate Data Collection:
~Use RESTful API to access SpaceX database.
~Employ web scraping for supplementary data.
Data Aggregation:
~Consolidate data from API and web sources into Pandas DataFrame.
Data Cleaning:
~Handle missing values and inconsistencies.
~Ensure data quality for analysis.
Final Dataset:
~Ready-to-use, clean dataset for EDA and modeling.

## Data Collection - Space API
Data sets were collected by leveraging Beautifulsoup to gather structured data on rocket launches, including details such as launch dates, payloads, and landing outcomes. This process involved initiating API calls to access Wikipedia, retrieving the relevant data, and then consolidating this information into a Pandas DataFrame. The data was subsequently cleaned and processed to handle any missing values and ensure consistency, forming a comprehensive dataset ready for exploratory data analysis and modeling.

......
Please refer to PDF
