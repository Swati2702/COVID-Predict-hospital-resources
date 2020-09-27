# COVID-Predict-hospital-resources

This project was created for Datathon 2020 Challenge Organized by Data Science Hub at Northeastern University. This project was declared to be the winner. 

The datathon was held by the Data Science Hub at Northeastern University. The aim was to use COVID19 data to uncover insights that can be most impactful in the areas of at-risk population evaluation and capacity management. 

Dataset: https://www.kaggle.com/roche-data-science-coalition/uncover/

- The major problem that the world is facing in dealing with Corona is the availability of limited resources we have at our hand for treating patients - resources like hospital beds, ICUs, ventilators, medicines and even health care workers. This has led to pushing our health care workers to work incessantly for even more than 2 days at a stretch impacting their health as well.

- The task that we have tried achieving through this datathon is to predict the hospital resources that would be required for the upcoming day. This would allow the hospital management to plan and arrange for resources efficiently beforehand. It would also enable the healthcare workers to plan their schedules and allow them to maintain some balance between their personal and professional lives.

Approach:

- Extensive Data Analysis
- Preprocess Data
- Create lags to remove time component from timeseries data  
- Used XGBoost on the data and got rmse score of 0.7 on validation data and 0.39 on test data
