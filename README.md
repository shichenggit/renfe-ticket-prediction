
# Spanish High-Speed Train Ticket Prediction


### Software and Libraries Used in this project

pandas
numpy
sklearn.model_selection (for train, validation, test split)
sklearn.metrics (for RMSE, model evaluation)
datetime (for extracting month, day, weekday, hour info)
os 

matplotlib
seaborn

scipy.stats (for ANOVA test)

Xgboost (for building sklearn Xgboost model)
sagemaker (for building AWS XGBoost model)

lightgbm (for building the LGBMRegressor model)


### Dataset

 The dataset is in CSV format available from Kaggle.
 
 * [Data CSV File](https://www.kaggle.com/thegurus/spanish-high-speed-rail-system-ticket-pricing): The data is scraped from Spanish High Speed Train Service (Renfe AVE) tickets pricing monitoring system. Ticket pricing changes based on demand and time, and there can be significant difference in price. 
 * The data includes 2.58 million records ranging from 4/22/2019 through 7/8/2019. File size is 2.71 MB.


 

---

## Setup Instructions

The notebook attached was created and tested using Amazon's SageMaker platform. The SageMaker model was trained using CPU on a regular ml.m4.xlarge instance.

The LGBMRegressor model can be run without AWS SageMaker. 

### Additional materials

Additional links and information are included in the project report.
