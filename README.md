# NYC_Subway_Analysis
This project focuses on optimizing NYC Subway services by analyzing ridership patterns and identifying delays. Using MTA turnstile data, GTFS feeds, and real-time service status, it aims to build predictive models to enhance operational efficiency and improve commuter experiences.

Overview
This project employs advanced machine learning techniques, including Random Forest and Gradient Boosting, to predict daily subway ridership. The goal is to provide actionable insights for transit agencies to optimize service planning and improve resource allocation.

Key features of this project include:

Data Cleaning and Preprocessing: Handling outliers, standardization, and feature engineering.
Exploratory Data Analysis (EDA): Investigating relationships between weather patterns and subway ridership.
Model Training and Optimization: Building and fine-tuning predictive models using hyperparameter tuning.
Results Visualization: Demonstrating the impact of key features on ridership through plots and metrics.

Dataset
The project utilizes two primary datasets:

MTA Turnstile Dataset: Contains subway entry and exit data.
Please use the following link to access the dataset:
https://drive.google.com/file/d/1Hrmzuj5solu-28lWME92bo74qh5KTodH/view?usp=drive_link
Weather Dataset: Includes hourly weather variables such as temperature, precipitation, and wind speed.

Languages: Python
Libraries:
Data manipulation: pandas, numpy
Visualization: matplotlib, seaborn
Machine learning: scikit-learn
Statistical analysis: scipy

Key Steps
Data Preprocessing:

Cleaning and merging datasets.
Removing outliers using the IQR method.
Standardizing numerical variables and encoding categorical variables.
Exploratory Data Analysis (EDA):

Visualizing correlations between weather conditions and ridership.
Analyzing patterns during rush vs. non-rush hours.
Modeling:

Training Random Forest and Gradient Boosting models.
Hyperparameter tuning using GridSearchCV and RandomizedSearchCV.
Evaluating models based on R² scores and RMSE metrics.
Visualization:

Generating scatter plots, box plots, and heatmaps to understand feature importance.

Results
Gradient Boosting Model: Achieved the best performance with an R² score of 0.671 and an RMSE of 531.44.
Key predictors of ridership include:
Temperature (positive correlation).
Precipitation (moderate positive correlation).
Rush Hour Indicator (significant impact on usage patterns).

Future Work
Incorporating real-time data for dynamic predictions.
Extending the analysis to include multi-city datasets.
Adding socioeconomic and behavioral data for richer insights.
Exploring advanced machine learning techniques, such as deep learning models.

Contributors
Ved Aralkar
Feel free to reach out for questions or suggestions: vedaralkar@gmail.com
