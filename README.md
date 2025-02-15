# DataAnalytics
1. Project Overview
 • Objective:
 -Clean and analyze Yelp business data to derive actionable insights.
 -Visualize trends in ratings, categories, and geospatial data.
 • Key Steps:
 - Data Exploration → Cleaning → Sentiment Analysis → Storage & Visualization

2. Dataset Description
The yelp_academic_dataset_business.json file contains information about businesses listed on Yelp.
 Each row represents a business and includes various attributes such as:
•	Basic Info: business_id, name, address, city, state, postal_code, latitude, longitude
•	Operational Details: is_open, hours
•	Customer Engagement: review_count, stars
•	Categories: categories (e.g., restaurants, shops, services)
•	Attributes: Detailed business properties like WiFi, OutdoorSeating, RestaurantsPriceRange2, AcceptsInsurance, etc.

3. Installation & Setup
 Tools Used:
 • Jupyter Notebook, PySpark, Pandas, ElasticSearch, Kibana.
Steps to clone the repository:
  •Open an empty folder on desktop.
  •Open git desktop
  •File -> Colne repository
  •Select the online repository and put your local repository path
  •Press the button "Clone"
List dependencies 
  •Open Command Prompt 
  •Install python (last version) and Java (11.0.26)
  •Install jupyter notebook (pip install notebook)
  •Install necessary libraries
    -(pip install pandas numpy matplotlib seaborn )
    -pip install PySpark
    -pip install scipy fuzzywuzzy python_Levenshtein

4. Team Roles
 •DijanaShahinaj: Dataset Analysis & Problem Definition
    Dataset preview, schema validation, missing values, and outlier detection.
 • Adela Cibuku: Data Cleaning & Transformation
   Standardizing addresses, categories, and business hours; outlier removal.
 • AngjelinaBahushi: Sentiment Analysis & Correlations
    Sentiment classification, category/city analysis, and feature engineering.
 • Elva Panariti: Data Storage & Visualization
    ElasticSearch setup, Kibana dashboards, and interactive visualizations.

5. Usage
 • Open command Prompt
 •Take the local repository path
 • run the command "cd pathoflocalrepository"
 • run jupyter noteook

6.  Initialization and Data Loading:
 • Spark Session was initialized for handling large datasets efficiently.
 • The Yelp dataset was loaded into a Spark DataFrame, with initial exploration done using df.show(5) and 
conversion to Pandas for easier visualization.

7. Exploratory Data Analysis (EDA)
 • Schema and data types were examined to identify necessary transformations, such as flattening nested 
JSON fields.
 • Attributes like hours and business details were extracted and converted into separate columns.
 • Missing values and duplicates were checked, but no duplicate entries were found.

8. Achieved Results
 ✔
 ️Comprehensive issue report guiding cleaning priorities.
 ✔
 ️Cleaned dataset with 90% fewer missing values.
 ✔
 ️Sentiment scores revealing "WiFi availability" as a key driver of positivity.
 ✔
 ️Interactive dashboards for real-time business trend analysis.


