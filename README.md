# Social Media and Mental Health Balance

## Project Overview
Exploratory data analysis (EDA) of how social media usage relates to well-being, using a survey dataset of 500 respondents. The notebook looks at screen time, sleep quality, stress, exercise, days without social media and happiness across six platforms.

## Objectives
- Inspect the data quality (missing values, duplicates, data types).
- Visualise patterns in social media usage and well-being indicators.
- Find correlations between screen time, stress, sleep and happiness.

## Dataset
Source: Kaggle (public dataset)

File: `Mental_Health_and_Social_Media_Balance_Dataset.csv` (500 rows, 10 columns)

Columns: User_ID, Age, Gender, Daily_Screen_Time(hrs), Sleep_Quality(1-10), Stress_Level(1-10), Days_Without_Social_Media, Exercise_Frequency(week), Social_Media_Platform, Happiness_Index(1-10)

## Technologies and Libraries
Python, Pandas, NumPy, Matplotlib, Seaborn

## Analysis Performed
- Data inspection: info, describe, null check, duplicate check
- Countplot of stress levels
- Violin plot of exercise frequency vs happiness
- Scatter plot and line plot of days without social media vs platform
- Pair plot
- Correlation heatmap

## Insights and Conclusions
- Daily screen time is strongly positively correlated with stress (about +0.74).
- Daily screen time is negatively correlated with happiness (about -0.71) and sleep quality (about -0.76).
- Age, exercise and days without social media showed almost no relationship with these measures.
- Note: these are correlations in a 500-respondent dataset, not proof of cause.

## How to Run
1. Clone the repository:
   git clone https://github.com/Sparsh20052025/SOCIAL-MEDIA-AND-MENTAL--HEALTH-BALANCE.git
2. Install the libraries:
   pip install pandas numpy matplotlib seaborn
3. Open the notebook in Jupyter or Google Colab and update the dataset path in the file-reading cell.

## Future Work
- Apply machine learning models to predict stress or happiness.
- Test the findings on a larger and more varied dataset.

## Author
Sparsh Shukla
B.Tech Computer Science and Engineering (Data Science and AI), Shri Ramswaroop Memorial University
