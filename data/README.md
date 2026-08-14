# Dataset Information

## Dataset Name

CarDekho Used-Car Dataset

## Source

The dataset was obtained from the following Kaggle data card:

- Kaggle dataset: https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho
- Original downloaded file: `car details v4.csv`
- Local renamed file: `raw/car_price_data.csv`

The Kaggle data card describes the records as used-car data collected from websites. Detailed information about the exact collection date and scraping method is limited.

## Dataset Size

- Observations: 2,059
- Raw columns: 20
- Regression target: `Price`
- Raw candidate input features: 19

## Target Variable

`Price` represents the reported listing price of a vehicle.

The records appear to represent the Indian used-car market. However, the currency unit is not explicitly verified in the currently available dataset description and should be interpreted with this limitation in mind.

## Input Features

- Make
- Model
- Year
- Kilometer
- Fuel Type
- Transmission
- Location
- Color
- Owner
- Seller Type
- Engine
- Max Power
- Max Torque
- Drivetrain
- Length
- Width
- Height
- Seating Capacity
- Fuel Tank Capacity

## License

Kaggle lists the dataset with the following license information:

- Database: Open Database
- Contents: Database Contents

Users should consult the original Kaggle data card before redistributing or using the dataset outside educational and research contexts.

## Intended Use

The dataset is used to implement and compare:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression

The project evaluates preprocessing, categorical encoding, feature scaling, coefficient shrinkage, feature selection, cross-validation, hyperparameter tuning, model assumptions, and prediction performance.

## Data-Quality Findings

Initial data understanding identified:

- No exact duplicate records
- Missing values in technical specification columns
- Numerical information combined with units in Engine, Max Power, and Max Torque
- High cardinality in Model and Location
- Imbalanced brand, location, seller, fuel, and color categories
- Strong right-skewness in Price
- A small number of suspiciously high Kilometer values
- Contextually valid luxury-vehicle price extremes

## Known Limitations

The dataset does not provide complete documentation about its collection date, sampling strategy, or scraping process.

Some categories are underrepresented, while major brands and cities contain more observations. Therefore, results should not automatically be generalized to the complete Indian used-car market.

The project treats the dataset as suitable for machine learning experimentation, portfolio development, and research-methodology training. It does not make causal claims or claim complete representation of the Indian automobile market.

## Data Integrity

The raw CSV file remains unchanged. Data cleaning, feature extraction, imputation, encoding, scaling, and outlier analysis are performed through documented notebooks and reproducible preprocessing pipelines.

## Acknowledgement

Thanks to the Kaggle contributor and collaborators for making the dataset available for learning and analysis.