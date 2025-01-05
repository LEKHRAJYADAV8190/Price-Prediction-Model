# Price Prediction Model

## Overview
This project demonstrates a machine learning workflow to predict prices based on given features. The workflow includes data preprocessing, model training, evaluation, and visualization. The model is built using Python and popular data science libraries.

## Features
- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Feature selection
- Model training using Linear Regression
- Model evaluation with metrics such as MSE and R²
- Visualization of actual vs. predicted prices

## Installation

### Prerequisites
- Python 3.6+
- Pip package manager

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/price_prediction.git
   cd price_prediction
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook `preprocess_and_trainmodel.ipynb`.
2. Run the cells in sequence to:
   - Load and preprocess the dataset
   - Train the Linear Regression model
   - Evaluate the model
   - Visualize the results

## File Structure
- `preprocess_and_trainmodel.ipynb`: Contains the code for the entire workflow.
- `requirements.txt`: Lists all the dependencies required for the project.
- `README.md`: Documentation for the project.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Results
The trained Linear Regression model is evaluated using the following metrics:
- **Mean Squared Error (MSE)**: 33,219,995,673.59
- **R-squared (R²)**: 0.4867

### Visualization
The project includes a scatter plot to compare actual and predicted prices, highlighting the model's performance visually:

![Actual vs Predicted Prices](preprocess_and_trainmodel.ipynb)

## Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for any bugs or improvements.



