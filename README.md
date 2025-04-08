# Project3_Group4

Datasource:
https://www.kaggle.com/datasets/ashishkumarjayswal/titanic-datasets

From the link above:
"
About Dataset
The Titanic Survival dataset is a widely-used dataset in the field of machine learning and data analysis. It contains information about the passengers on board the RMS Titanic, including whether they survived the shipwreck or not. Here is a description of the typical fields you may find in the Titanic Survival dataset:

Passenger Information:
This section includes data about the passengers, such as their names, gender, age, and passenger class (First, Second, or Third Class). This information provides insights into the demographics of the passengers on board.

Ticket Information:
Ticket information includes details about the passengers' ticket numbers, fares paid, and cabin information. This data can be used to analyze patterns related to ticket prices and cabin locations.

Travel Details:
Travel details provide information about the passengers' travel arrangements, such as the port of embarkation (Cherbourg, Queenstown, or Southampton) and the destination of the journey.

Family Relationships:
This section includes data about the family relationships of passengers, including the number of siblings/spouses (SibSp) and the number of parents/children (Parch) they were traveling with. These variables can be used to analyze the presence of family groups on board.

Survival Status:
The survival status field indicates whether a passenger survived the Titanic disaster or not. This binary variable is typically represented as 1 (survived) or 0 (did not survive). This field serves as the target variable for prediction models.

Other Relevant Factors:
Additional fields may be included to capture any other relevant factors that could potentially affect survival rates. These may include variables such as passenger ID, lifeboat numbers (if applicable), and any special circumstances related to the passenger's survival.

The Titanic Survival dataset is often used as a training dataset for classification and predictive modeling tasks. Researchers and data scientists use this dataset to explore patterns and factors that influenced the survival rates of passengers on the Titanic. By analyzing this dataset, one can gain insights into the demographics, socio-economic factors, and strategies for survival during the shipwreck."



Project Requirements and Fulfilments

Use at least one database (SQL or NoSQL, e.g., PostgreSQL, MongoDB, SQLite)
Must contain at least 100 records
 Dataset contains 890 rows of data

For Data Engineering: include at least two tables or collections
Include ETL workflows to transform and load data into the database (Data Engineering)
Use at least one JavaScript or Python library not covered in class
 We utilized data cleanup methods to create "Titanic_Cleaned.csv" and loaded the data into a sql database.


Include visualizations using tools like:
Python (Matplotlib, hvplot, etc.)
JavaScript (Plotly, Leaflet, etc.)
 We used a combination of visusalizations such as bar charts, scatter plots, pair plots, line graphs, and boxen plots.

A new visualization library

Include user interaction (required for Visualization, optional for Engineering):
HTML menus, dropdowns, or textboxes
Flask backend with API routes
Filtering or selecting data for custom views
 We used Dash to create an web browser view of analytics, with dropdown usability.

Include a method to display or serve data, such as:
Pandas DataFrame
Flask API with JSON output
 We used various pandas dataframes throughout. 

Final visualization should include at least three different views (Visualization track)
 We're including 5 visualizations in the presentation.

Use one additional library related to visualization or data engineering not taught in class
  Dash

Include documentation with:
Database selection reasoning
 SQL database was the right choice for building tables, and querying data to create visualizations.

ETL workflow diagram or ERD
 Quickdbd.com was used to create the ERD. Image included inside Resources.



Other resources used:
Chat GBT - this was used mainly for the Dash section, as it was a brand new type of coding and unfamiliar to us. This allowed us to structure to code correctly in order for everything to work correctly. 
