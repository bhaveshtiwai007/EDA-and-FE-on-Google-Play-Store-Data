# EDA-and-FE-on-Google-Play-Store-Data
EDA and Feature Engineering on Google Play Store Dataset
This project involves Exploratory Data Analysis (EDA) and Feature Engineering (FE) on a dataset containing over 10,000 Android applications published on the Google Play Store. The aim is to derive insights from the data, clean and preprocess it, and transform it for further machine learning or analytical use.

📊 Dataset Overview
The dataset contains information about various Android applications including:

App Name

Category

Rating

Reviews

Size

Installs

Price

Content Rating

Genres

Last Updated

Current Version

Android Version

You can find the dataset here.

 Key Objectives
Perform data cleaning to handle inconsistencies and missing values.

Understand relationships and patterns through EDA.

Engineer meaningful features to prepare the dataset for modeling.

 Data Cleaning
Removed duplicates and null values.

Converted categorical values such as "Size", "Installs", and "Price" into numerical formats.

Normalized data and handled inconsistent formatting (e.g., 'Varies with device').

🛠 Feature Engineering
Converted "Installs" and "Price" to numeric types for analysis.

Extracted new features such as:

App Size in MB

Popularity buckets based on install counts

App pricing categories (Free/Paid)

Encoded categorical variables for modeling.

📈 Exploratory Data Analysis
Identified top app categories based on install counts.

Analyzed distribution of ratings, price, and app sizes.

Explored the relationship between app type (free/paid) and its rating/installs.

Created bar plots, histograms, and scatter plots using matplotlib and seaborn.
 Technologies Used
Python

Pandas

NumPy

Seaborn

Matplotlib

Jupyter Notebook
