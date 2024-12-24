<<<<<<< HEAD
# Customer Segmentation Using K-Means Clustering
![Customer Segmentation Using K-Means Clustering](https://github.com/BottomsNode/SCT_ML_2/blob/main/Task%202%20%20ML.png)
This Python script demonstrates how to perform customer segmentation using K-Means clustering based on annual income and spending score.

## Dataset

The dataset used (`Mall_Customers.csv`) contains the following columns:

- `CustomerID`: Unique ID assigned to each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars
- `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## Dependencies

Make sure you have the following libraries installed:

- pandas
- matplotlib
- scikit-learn

Install them using pip if necessary:

```bash
pip install pandas matplotlib scikit-learn
```

## Running the Script:
1. Clone the Repository:
    git clone [https://github.com/BottomsNode/SCT_ML_2.git](https://github.com/BottomsNode/SCT_ML_2)<br>
    cd SCT_ML_2

2. Download the Dataset:
   Place the Mall_Customers.csv dataset in the same directory as the Python script.

3. Run the Script:
   Execute the Python script customer_segmentation.py:
   python customer_segmentation.py
This will generate an animated visualization of the K-Means clustering process.

 ## Author:
[BottomsNode](https://github.com/BottomsNode)
=======
# SCT_ML_1
![House Price Prediction](https://github.com/BottomsNode/SCT_ML_1/blob/main/Task%201%20%20ML.png)

# House Price Prediction with Linear Regression

This project implements a linear regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms.

## Dataset

The dataset used for this project contains information about various features of houses and their corresponding sale prices. It includes features like:
- GrLivArea: Above grade (ground) living area square feet
- BedroomAbvGr: Number of bedrooms above grade (does NOT include basement bedrooms)
- FullBath: Number of full bathrooms above grade
- SalePrice: Sale price of the house in dollars

## Files

- `train.csv`: Training dataset containing features and target variables.
- `test.csv`: Testing dataset used for making predictions.
- `sample_submission.csv`: Sample submission file with the format required for submission.

## Dependencies

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your/repository.git
   cd repository
   
2. Install dependencies:
   pip install -r requirements.txt

3. Run the script:
   python house_price_prediction.py

4. The script will train the linear regression model, make predictions on the test set, and display various visualizations to evaluate the model's performance.
>>>>>>> 515610a28cf0eae27c2853f4771efce51c4e0e23
