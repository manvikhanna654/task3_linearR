# task3_linearR
# Housing Price Prediction using Linear Regression

This project uses a simple linear regression model to predict house prices based on features like area, number of bedrooms, bathrooms, stories, and parking spaces. The dataset is assumed to be a CSV file containing various attributes of houses.

## 📁 Dataset

The dataset should include at least the following columns:

- `price`: Selling price of the house
- `area`: Size of the house (in square feet)
- `bedrooms`: Number of bedrooms
- `bathrooms`: Number of bathrooms
- `stories`: Number of stories (floors)
- `parking`: Number of parking spaces

Make sure the file is uploaded in your Google Colab environment before running the code.

## 🧠 Model

We use a simple Linear Regression model from `scikit-learn` to:

- Train on 80% of the data
- Test on the remaining 20%
- Evaluate the performance using MAE, MSE, RMSE, and R² score

## 📊 Visualization

A scatter plot is generated to compare actual vs predicted prices based on the `area` feature.

## 💡 How to Run

1. Upload your dataset when prompted.
2. The script will:
   - Clean the column names
   - Select the relevant features
   - Train and evaluate the model
   - Show the actual vs predicted prices visually

## 🛠️ Requirements

Make sure the following libraries are installed (pre-installed in Google Colab):

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## ✅ Output

The script prints:
- Model accuracy metrics (MAE, MSE, RMSE, R²)
- Coefficients and intercept of the model
- A scatter plot comparing actual and predicted prices

---

Feel free to extend this project by:
- Including more features
- Encoding categorical variables
- Trying out other regression models
