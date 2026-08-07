# Dataset Information

## Dataset Name

Car Price Analysis Dataset

## Source

The CSV used in this project was obtained through the following Kaggle notebook:

- Reference notebook: https://www.kaggle.com/code/dhruvkp07/car-price

The original dataset page, license, measurement units, and data-generation
method have not yet been independently verified.

## Current Data-Quality Warning

Initial exploratory data analysis found nearly uniform numerical distributions,
near-zero correlations with Price, and weak logical consistency among Year,
Mileage, and Condition.

Therefore, this dataset is currently treated as a learning and data-audit
dataset, not as verified real-world data for research conclusions.

## License

The dataset license has not yet been independently verified from the
original dataset page.

## Local File

`raw/car_price_prediction.csv`

The dataset contains 2,500 observations and 10 columns.

## Target Variable

`Price` — the target variable representing the reported car price.
The currency unit has not yet been independently verified.

## Input Features

- Car ID
- Brand
- Year
- Engine Size
- Fuel Type
- Transmission
- Mileage
- Condition
- Model

`Car ID` is a unique identifier and will not be used as a predictive feature.

## Intended Use

This dataset is retained for educational experimentation, data-quality
auditing, and machine learning pipeline development.

It may be used for preliminary implementation of Linear Regression,
Ridge Regression, Lasso Regression, and Elastic Net Regression. However,
a verified real-world dataset will be selected for the final model
comparison and research conclusions.

## Known Limitations

The available Kaggle information indicates that the dataset may contain
synthetic or mixed-source records.

Some feature combinations may not represent real vehicles, such as Tesla
cars with Petrol or Diesel fuel types. The relationships among Price, Year,
Mileage, Engine Size, and Condition also appear weak or unrealistic.

Therefore, results obtained from this dataset should be treated as
educational findings. They should not be interpreted as actual car-market
estimates or causal relationships.