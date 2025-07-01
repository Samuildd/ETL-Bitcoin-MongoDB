# ETL-Bitcoin-MongoDB
## Bitcoin Data ETL Pipeline

This project extracts Bitcoin 1-minute data from CSV, performs data cleaning and transformation, and loads it into a MongoDB Atlas database.

### Steps:

- **Extract** Bitcoin data from CSV
- **Transform** data: clean, fill missing, develop new columns (moving average, % change, day_of_week), identify outliers, convert currency and unit testing
- **Load** load data into MongoDB Atlas

### Technologies Used

- Python/Pandas
- MongoDB Atlas
- Google Collab

### How to use personally:

1. Open the notebook in Google Colab
2. Set your API for currency conversion
3. Set your MongoDB Atlas connection string
4. Run the ETL pipeline

The original bitcoin dataset can be found on kaggle. [Click Me!](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data/data)
