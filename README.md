# NCAA_March_Madness_2020
Data Analysis and Model Building for 2020 Kaggle/Google Cloud NCAA March Madness Tournament.

Repository Contents:

## 00DataSetCreation-FeatureEngineering
Data wrangling and manipulation. Extracting data from .csv tables provided via Google Cloud and and engineering team statistics (both game level regular season and postseason) to prepare a feature set for modeling.

## 01.1UpsetPrediction
Data analysis for trends and patterns in predicting upsets. Designed model to predict upsets (potentially used in final voting ensemble model)

## 01 EDA-TournamentModeling2003-2019
EDA and model building using only end of regular season data available from 2003 - 2019. Primarily used as a benchmark for final model.

## 02.1RegularSeason-StatisticsOnly
Model building using only team statistics from regular season games to predict outcomes. Level 0 model. 

## 02.2RegularSeason-RankingsOnly
Model building using only rankings and ratings from regular season to predict outcomes. Level 0 model.

## 02RegularSeasonModel
Model using both regular season statistics and rankings. Benchmark for ensemble method.

## 03ModelEvaluation
NOT COMPLETE- evaluating effectiveness of models and experimenting with model combinations.
