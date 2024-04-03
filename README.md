# DSC530-Topic-2-Part-1-Time-Series-Exploring-and-Understanding
 An assignment for DSC530 at GCU that focused on choosing and preparing a dataset for time-series analysis.

# Assignment Instructions
Each machine learning algorithm expects data as input that needs to be formatted in a very specific way, so time series datasets generally require some cleaning and feature engineering processes before they can generate useful insights. Since time series data has a temporal feature, only some of the statistical methodologies are appropriate for time series data.
For this activity, in 500-750 words, answer the following:

1. Search for a dataset that is suitable for a time series task. You may search repositories such as Data.gov, UCI Machine Learning, Kaggle, or Scikit-Learn. There are currently 48 time series datasets on the UCI website, which is located in the topic Resources.
2. Discuss the origin of the data and assess whether it was obtained in an ethical manner.
3. Formulate question(s) that you want to answer by applying a time-series analysis. Make sure to address the following:
 - The purpose of generating forecasts and explain the difference between forecasting and predictions.
 - The type of forecasts that are needed; Descriptive or/and predictive?
 - How the forecasts will be used by the company.
 - What costs are associated with forecast errors.
 - Define your forecasting horizon and explain the impact of large or small forecast horizon on forecasting accuracy.
4. Explain in a few words how time series forecasting analysis is used in the retail, energy, government, financial, agriculture, and education industries.
5. Import the necessary libraries, then read the dataset into a data frame and perform initial descriptive statistical explorations. Report the results.
6. Check the datatype of the date column and make sure it's identified as date. If not, use the parse_dates parameter in pandas to parse it as a date feature. Print the first five rows.
7. Use the statsmodels Python module to visualize any Trends, Seasonality, Cyclic, or Noise in your dataset. Report and interpret your results. Do you see any consistent/irregular patterns in your data? Explain?
8. Discuss the need for standardizing and/or normalizing your dataset based on Step 6 output.

APA style is not required, but solid academic writing is expected. This assignment uses a rubric. Please review the rubric prior to beginning the assignment to become familiar with the expectations for successful completion. You are not required to submit this assignment to LopesWrite.
