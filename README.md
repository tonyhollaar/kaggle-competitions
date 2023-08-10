# Kaggle Competitions
Kaggle Projects / Competitions
- [Predict CO2 Emissions in Rwanda](https://www.kaggle.com/competitions/playground-series-s3e20)
- [Titanic: Machine Learning from Disaster Competition](https://www.kaggle.com/c/titanic)

## 🌍 Predict CO2 Emissions in Rwanda
[Predict CO2 Emissions in Rwanda](https://www.kaggle.com/competitions/playground-series-s3e20)
on Kaggle aims to create machine learning models using open-source CO2 emissions data from Sentinel-5P satellite observations to predict future carbon emissions.
These solutions may help enable governments and other actors to estimate carbon emission levels, even in places where on-the-ground monitoring is not possible.


Check out my [Link to my Notebook](https://github.com/tonyhollaar/kaggle-competitions/blob/main/kaggle_co2_emmissions.ipynb) for a detailed walkthrough of my approach.

### Key Methodologies
As a data scientist, here's a comprehensive breakdown of the key steps and methodologies that can be employed to tackle the "Predict CO2 Emissions in Rwanda" competition:

🔍 **Exploratory Data Analysis (EDA) with Geospatial Visualizations:** Begin by thoroughly understanding the provided CO2 emissions dataset. Utilize geospatial information such as latitude and longitude along with the `folium` package to create interactive maps. This helps visualize emission levels across different geographic regions and identify potential spatial patterns.

📊 **Feature Engineering and Preprocessing:** Effective feature engineering enhances model performance. Derive additional features from the timestamp, aggregate data at different temporal resolutions, and encode categorical variables. Deal with missing values and normalize numerical features during preprocessing.

**Prophet Time Series Model:** Given the time-dependent nature of the data, employ a time series forecasting approach. Facebook's Prophet is ideal for modeling time series data with seasonality and holidays. It captures patterns like trends and periodic variations for accurate predictions.

## 🚢 Titanic: Machine Learning from Disaster Competition
[Titanic: Machine Learning from Disaster Competition](https://www.kaggle.com/c/titanic) on Kaggle tests skills in machine learning and data analysis! The goal of the competition is to predict which passengers survived the Titanic shipwreck based on various features provided in the dataset.

Check out my [Link to my Notebook](https://github.com/tonyhollaar/kaggle-competitions/blob/main/titanic-machine-learning-from-disaster.ipynb) for a detailed walkthrough of my approach. I've documented the steps I took, the preprocessing techniques applied, the machine learning models used, and the evaluation of results. Feel free to explore, learn, and provide feedback!
### Key Methodologies

🔍 **Exploratory Data Analysis (EDA):**
- Analyzed ticket class, gender, age, and more.
- Visualized data with histograms, box plots, and more.
- Handled missing data.

🔧 **Precision-Crafted Feature Engineering:**
- Segmented 'Age' into meaningful groups with binning.
- Extracted insights from 'Title' using regular expressions (RegEx).
- Categorized 'Fare' through quantiles.

📊 **Insightful Data Visualization:**
- Visualized survival correlations.
- Used stacked bar charts for category insights.

🛠️ **Strategic Feature Augmentation:**
- Introduced 'Age_missing' and 'Fare_0' attributes.
- Enhanced predictive power with engineered features.

🌌 **Venturing into Deep Learning:**
- Utilized deep learning technique.
- Sequential model with Dense and Dropout layers.
- Reviewed accuracy and loss trends through epochs.
