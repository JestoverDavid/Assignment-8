# Assignment-8
# House Price Prediction

This project aims to predict house prices using various features from a given dataset. The dataset includes attributes such as the number of bedrooms, bathrooms, square footage, and more. The goal is to build a model that can accurately estimate the price of a house based on these features.

## Dataset

The dataset used in this project is provided in the file `data.csv`. It contains the following columns:

- `date`: Date of the transaction
- `price`: Price of the house
- `bedrooms`: Number of bedrooms
- `bathrooms`: Number of bathrooms
- `sqft_living`: Square footage of the living area
- `sqft_lot`: Square footage of the lot
- `floors`: Number of floors
- `waterfront`: Whether the house has a waterfront view
- `view`: Quality of the view
- `condition`: Condition of the house
- `sqft_above`: Square footage of the house above ground
- `sqft_basement`: Square footage of the basement
- `yr_built`: Year the house was built
- `yr_renovated`: Year the house was renovated
- `street`: Street address
- `city`: City
- `statezip`: State and ZIP code
- `country`: Country

## Files

- `data.csv`: The original dataset.
- `House price prediction.ipynb`: Jupyter notebook containing the code for data preprocessing, feature engineering, model training, and evaluation.
- `train_sample.csv`: A smaller sample of the training data.
- `test_sample.csv`: A smaller sample of the test data.

## Data Preprocessing

1. **Handling Missing Values**: Missing values in numeric columns were filled with the median of the respective columns. Missing values in categorical columns were filled with the mode.
2. **Encoding Categorical Features**: Categorical features were converted to numerical values using one-hot encoding.
3. **Feature Scaling**: Features were scaled using `StandardScaler` to standardize the data.

## Model Training

The data was split into training and testing sets. Various models can be trained using the preprocessed data. The notebook `House price prediction.ipynb` provides code to train and evaluate models.

## Usage

To run the project, follow these steps:

1. Clone the repository.
2. Ensure you have the necessary Python packages installed. You can install the required packages using:
   ```bash
   pip install -r requirements.txt
