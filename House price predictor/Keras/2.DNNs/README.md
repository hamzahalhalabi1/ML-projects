# House Price Prediction Model Readme

This repository contains a Deep Neural Network (DNN) machine learning model built using Keras for predicting house prices based on various features such as year built, floor square feet, living area square feet, number of bathrooms, number of bedrooms, total rooms, year sold, and sale price.

## Dataset
The model utilizes a dataset containing information about houses including the following features:

1. Year built
2. Floor square feet
3. Living area square feet
4. Full bathrooms above grade
5. Half baths above grade
6. Number of bedrooms above basement level
7. Total rooms above grade (excluding bathrooms)
8. Year sold
9. Sale price (target variable)

## Dependencies
To run this project, ensure you have the following dependencies installed:

- Python (>=3.6)
- Keras
- NumPy
- Pandas
- Matplotlib (for visualization, optional)
- Jupyter Notebook (for running the provided example notebook, optional)

You can install the dependencies using pip:

```bash
pip install keras numpy pandas matplotlib jupyter
```

## Usage
1. Clone the repository:

```bash
git clone https://github.com/hamzahalhalabi1/house-price-prediction.git
cd house-price-prediction
```

2. Prepare your dataset:
   - Ensure your dataset is in a CSV format with columns for each feature and the target variable (sale price).
   - Make sure the dataset is clean and does not contain any missing values.

3. Train the model:
   - Use the provided Jupyter Notebook or Python script to train the model on your dataset.
   - Tune hyperparameters as needed.

4. Evaluate the model:
   - Assess the performance of the trained model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), etc.
   - Visualize the predictions versus actual sale prices to gain insights into the model's performance.

5. Make predictions:
   - Once the model is trained and evaluated satisfactorily, you can use it to make predictions on new or unseen data.

## Example Notebook
An example notebook (`house_price_prediction_example.ipynb`) is provided in this repository to demonstrate how to use the model for house price prediction. You can run this notebook in a Jupyter environment to see the model in action.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Issues
If you encounter any issues or have suggestions for improvements, please feel free to open an issue on GitHub.

## Credits
Dataset from 
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/overview