# Project3_Group4

**Project Participants:** Joseph Milotta, Luis Carlos Lopez, Leonardo Rios, & Oliver von Mizener

## Datasource
[The Titanic Dataset on Kaggle](https://www.kaggle.com/datasets/ashishkumarjayswal/titanic-datasets)  

### About the Dataset
The Titanic Survival dataset is a widely-used dataset for machine learning and data analysis. It provides rich information about passengers, including:
- **Passenger Information:** Names, gender, age, and passenger class (First, Second, or Third Class).
- **Ticket Information:** Ticket numbers, fares paid, and cabin details, which offer insights into ticket prices and cabin locations.
- **Travel Details:** Port of embarkation (Cherbourg, Queenstown, or Southampton) and destination.
- **Family Relationships:** Family groups on board, represented by siblings/spouses (SibSp) and parents/children (Parch) fields.
- **Survival Status:** Binary variable indicating whether a passenger survived (1) or did not survive (0).  
This dataset is often used for predictive modeling to explore factors influencing survival rates during the Titanic disaster.  

---

## Contents of Repository
- `titanic.pynb`: Jupyter Notebook containing analysis and visualizations.
- `titanic.db`: SQL database containing cleaned and transformed Titanic data.
- `Resources/`: Folder containing the cleaned CSV data pulled from the source.

---

## Project Requirements and Fulfillments

### **Database**
- **Requirement:** Use at least one database (SQL or NoSQL) containing at least 100 records.
- **Fulfillment:** Dataset includes 890 rows. We utilized a SQL database for table creation and data querying.

### **Data Engineering**
- **Requirement:**
  - Include at least two tables or collections.
  - ETL workflows for data transformation and loading.
  - Use a new library not covered in class.
- **Fulfillment:**
  - We created "Titanic_Cleaned.csv" through data cleanup and loaded it into a SQL database.
  - ETL workflow implemented for transforming and loading data.
  - **Library Used:** Dash for visualization and interactivity.

### **Visualizations**
- **Requirement:** Include multiple visualizations using Python or JavaScript libraries.
- **Fulfillment:**
  - A range of visualizations created, including bar charts, scatter plots, pair plots, line graphs, and boxen plots.
  - **New Visualization Library:** Dash for user-friendly web analytics.

### **User Interaction**
- **Requirement:** Provide user interaction through HTML menus, dropdowns, or filters.
- **Fulfillment:** Dash was used to create an interactive web browser view with dropdown usability.

### **Data Serving**
- **Requirement:** Provide a method to display or serve data.
- **Fulfillment:** Used pandas DataFrames throughout and Flask API for JSON output where necessary.

### **Final Visualization**
- **Requirement:** Include at least three views.
- **Fulfillment:** Five visualizations included in the presentation.

---

## Documentation

### **Database Selection Reasoning**
- SQL was chosen for its efficient table creation and data querying capabilities, making it ideal for creating visualizations.

### **ETL Workflow Diagram/ERD**
- Created using [QuickDBD](https://www.quickdbd.com), with the diagram included in the `Resources` folder.

---

## Other Resources
- **Chat GPT/Copilot:** Assisted mainly with the Dash section, helping to structure code for effective implementation.