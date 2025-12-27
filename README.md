# Social-Media-VS-productivity
**Social Media vs Productivity Analysis**

This project examines the relationship between social media usage and productivity through exploratory data analysis (EDA) on a dataset of digital habits, work performance, and well-being factors.

**Project Overview**
The analysis explores how daily social media time, screen habits, stress, and sleep impact perceived and actual productivity scores across demographics like age, gender, and job type. It uses a subset of 3,000 records from a 30,000-record dataset with 17 features, focusing on patterns via visualizations and correlations.

**Dataset**

Source: Kaggle dataset "Social Media vs Productivity" (https://www.kaggle.com/datasets/mahdimashayekhi/social-media-vs-productivity).[1]

**Features:**
| Category     | Columns                                                                                      |
| ------------ | -------------------------------------------------------------------------------------------- |
| Demographics | age, gender, jobtype                                                                         |
| Social Media | dailysocialmediatime, socialplatformpreference, numberofnotifications, screentimebeforesleep |
| Productivity | workhoursperday, perceivedproductivityscore, actualproductivityscore, weeklyofflinehours     |
| Well-being   | stresslevel, sleephours, jobsatisfactionscore, daysfeelingburnoutpermonth                    |
| Habits       | usesfocusapps, hasdigitalwellbeingenabled                                                    |
After cleaning (handling ~10-12% missing values, no duplicates), 1,354 complete rows remain for analysis.

**Key Findings**

* Strong alignment between perceived and actual productivity (r=0.96), but weak ties to social media time or work hours.

​* Social media usage consistent across genders; minor variations by job type (e.g., higher variability in students/unemployed).

​* Lifestyle clusters (sleep, screen time) show limited direct productivity impact; focus apps/digital wellness underutilized.

**Usage**

* Run Social_Media_Vs_Productivity_FINAL-6.ipynb in Jupyter/Colab (Python 3, pandas, seaborn, matplotlib required).
​

* Dataset auto-loads via Colab upload or local CSV ("SOCIAL MEDIA VS PRODUCTIVITY ORG.csv").
​

* Outputs: Cleaned data, plots, correlation insights.

**Technologies**

* Python, Pandas, NumPy, Seaborn, Matplotlib.

* Jupyter Notebook (Colab-compatible)
