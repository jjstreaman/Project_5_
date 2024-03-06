# Project_5_

## Overview
This project collected data from various resources on baseball statistics and built supervised machine learning models to predict the surgery status (Tommy John) of pitchers based on the available features.

## Business Understanding
Baseball is considered America's National Pastime. The game dates back to the early 1800's, and developed into a professional league after the Civil War. Today baseball is big business. With players signing contracts for hundreds of millions of dollars, owners want to not only protect their investment, but see a return on that investment. Before Tommy John, if a pitcher blew out their arm, it was considered a fatal blow to their career. After the successful surgery to Tommy John's UCL in 1974, this surgery has become much more common in pitchers today. Anywhere from professional players all the way to high school are undergoing this procedure. While this may save a players career, it requires a long recovery time and there is no guaruntee that this will be effective. Some players are unfortunate enough to undergo this procedure multiple times. This data was gathered from sites like baseball-reference.com, a running list of players who have undergone surgery, and the Python library 'pybaseball'. This project aims to look at the available advanced pitching statistics available and correctly predict if pitchers will need Tommy John surgery or not.

## Repository Navigation
The repository has several notebooks and a data folder. You will find the appropriate information within each specific file.


Data
- 1972_pitch_stats.csv
- 1973_pitch_stats.csv
- 1974_pitch_stats.csv
- 1975_pitch_stats.csv
- 1976_pitch_stats.csv
- 1977_pitch_stats.csv
- 1978_pitch_stats.csv
- 1979_pitch_stats.csv
- 1980_pitch_stats.csv
- 1981_pitch_stats.csv
- 1982_pitch_stats.csv
- 1983_pitch_stats.csv
- 1984_pitch_stats.csv
- 1985_pitch_stats.csv
- 1986_pitch_stats.csv
- 1987_pitch_stats.csv
- 1988_pitch_stats.csv
- 1989_pitch_stats.csv
- 1990_pitch_stats.csv
- 1991_pitch_stats.csv
- 1992_pitch_stats.csv
- 1993_pitch_stats.csv
- 1994_pitch_stats.csv
- 1995_pitch_stats.csv
- 1996_pitch_stats.csv
- 1997_pitch_stats.csv
- 1998_pitch_stats.csv
- 1999_pitch_stats.csv
- 2000_pitch_stats.csv
- 2001_pitch_stats.csv
- 2002_pitch_stats.csv
- 2003_pitch_stats.csv
- 2004_pitch_stats.csv
- 2005_pitch_stats.csv
- 2006_pitch_stats.csv
- 2007_pitch_stats.csv
- 2008_pitch_stats.csv
- 2009_pitch_stats.csv
- 2010_pitch_stats.csv
- 2011_pitch_stats.csv
- 2012_pitch_stats.csv
- 2013_pitch_stats.csv
- 2014_pitch_stats.csv
- 2015_pitch_stats.csv
- 2016_pitch_stats.csv
- 2017_pitch_stats.csv
- 2018_pitch_stats.csv
- 2019_pitch_stats.csv
- 2020_pitch_stats.csv
- 2021_pitch_stats.csv
- 2022_pitch_stats.csv
- 2023_pitch_stats.csv
- all_2008_stats_df.csv
- all_2009_stats_df.csv
- all_2010_stats_df.csv
- all_2011_stats_df.csv
- all_2012_stats_df.csv
- all_2013_stats_df.csv
- all_2014_stats_df.csv
- all_2015_stats_df.csv
- all_2016_stats_df.csv
- all_2017_stats_df.csv
- all_2018_stats_df.csv
- all_2019_stats_df.csv
- all_2020_stats_df.csv
- all_2021_stats_df.csv
- all_2022_stats_df.csv
- all_2023_stats_df.csv
- better_2008_df.csv
- better_2009_df.csv
- better_2010_df.csv
- better_2011_df.csv
- better_2012_df.csv
- better_2013_df.csv
- better_2014_df.csv
- better_2015_df.csv
- better_2016_df.csv
- better_2017_df.csv
- better_2018_df.csv
- better_2019_df.csv
- better_2020_df.csv
- better_2021_df.csv
- better_2022_df.csv
- better_2023_df.csv
- clean_tj_df.csv
- cleaning_filtered_df.csv
- complete_df.csv
- complete_100_df.csv
- cond_pivoted_df.csv
- better_2008_df.csv
- final_2009_df.csv
- final_2010_df.csv
- final_2011_df.csv
- final_2012_df.csv
- final_2013_df.csv
- final_2014_df.csv
- final_2015_df.csv
- final_2016_df.csv
- final_2017_df.csv
- final_2018_df.csv
- final_2019_df.csv
- final_2020_df.csv
- final_2021_df.csv
- final_2022_df.csv
- final_2023_df.csv
- hist_tj.csv
- modeling_df.csv
- pitcher_key_df.csv
- pivoted_df.csv
- savant_data.csv
- savant_data_results.csv
- tj_surgery_list.csv

Notebooks
- all_2008_stats_cleaning
- all_2009_stats_cleaning
- all_2010_stats_cleaning
- all_2011_stats_cleaning
- all_2012_stats_cleaning
- all_2013_stats_cleaning
- all_2014_stats_cleaning
- all_2015_stats_cleaning
- all_2016_stats_cleaning
- all_2017_stats_cleaning
- all_2018_stats_cleaning
- all_2019_stats_cleaning
- all_2020_stats_cleaning
- all_2021_stats_cleaning
- all_2022_stats_cleaning
- all_2023_stats_cleaning
- Data_Cleaning_Notebook_1
- Data_Cleaning_Notebook_2
- Data_Cleaning_Notebook_3
- Data_Cleaning_Notebook_4
- Model_Notebook_1
- Model_Notebook_2
- Final_Notebook

## Presentation and Data Source
- Historic Seasonal Starting Pitching Data from Baseball-reference.com - [Link](https://www.baseball-reference.com/leagues/majors/2023-starter-pitching.shtml)
- TJ Surgery List from Google Docs - [Link](https://docs.google.com/spreadsheets/d/1gQujXQQGOVNaiuwSN680Hq-FDVsCwvN-3AazykOBON0/edit#gid=0)
- Python baseball library Pybaseball - [Link](https://pypi.org/project/pybaseball/)
- Presentation - [Link](https://docs.google.com/presentation/d/1nC4skWPs04aq8HSFh7sb7AwX3NmBQNQF0HUHMBmjggk/edit#slide=id.g2bf4da13b11_0_22)

## Data and Model Analysis
The data for this project has been collected, cleaned, and sorted for the final analysis.
Many tools were used in this process of analysis, including but not limited to pybaseball, pandas, numpy, sklearn, imblearn,  etc.
The first step was to gather and clean data in order to get a historic view of the number of starting pitchers in the MLB as well as the number of TJ surgeries since 1974 (to applicable pitchers, standards were starting pitchers only who have thrown a minimum of 320 career innings).
The next step was to collect data on Advanced Pitching Metrics, which was limited between the years of 2008 - 2023.
After cleaning and organizing this set of data, the target variable was set to "Surgery" as its values are binary (0 or 1) where 0 means no surgery, and 1 means surgery.
Due to the nature of the collected data, pivot tables were made in order to be read accurately. This resulted in 129 features.
Because of this, I made two separate dataframes in order to test what would make the more effective models.
The first was the standard dataframe, the second one condensed pitch types & their associated metrics to generalized categories (fastball, breaking ball, off-speed, etc.).
Several models were attempted, including: Logistic Regression, Decision Tree, Random Forest, XG Boost, and KNN.
These models were adjusted via Grid Search to determine the best parameters specific to that model.
The best performing model was a Logistic Regression model, with a recall score of 85%.
This model employed a Standard Scaler to scale the various features, adjusted class weights to {0: 1, 1: 5}, score set to recall, C set to 0.01, penalty set to l1, tolerance set to 0.01, and max iterations set to 5000.

## Conclusion
By the end of the process, the Logistic Regression was the most effective model, with a recall score of 85%.
This model employed a Standard Scaler to scale the various features, adjusted class weights to {0: 1, 1: 5}, score set to recall, C set to 0.01, penalty set to l1, tolerance set to 0.01, and max iterations set to 5000.
To further improve this model, I would like to gather more data and add more features including biological data, video analysis of pitching mechanics, advanced pitching data for years prior to 2008, data for international leagues, minor leagues, college, and various other factors like days rest, humidity, altitude, etc.
