
---

# Prodigy Internship Task 1

## Task Overview
This task involves analyzing a housing dataset to predict house prices using a linear regression model. The process includes data preprocessing, exploratory data analysis (EDA), model building, evaluation, and visualization.

---

## Steps and Code Details

### 1. **Importing Necessary Libraries**
The script uses the following libraries:
- `pandas` and `numpy`: For data manipulation and analysis.
- `matplotlib.pyplot` and `seaborn`: For visualizing data and insights.
- `scikit-learn`: For machine learning tasks such as data splitting, model training, and evaluation.

### 2. **Loading the Dataset**
The dataset file, `Housing.csv`, is loaded using `pandas`. Update the `dataset_path` variable with the correct path to your dataset.

### 3. **Dataset Overview**
The first few rows of the dataset are displayed to understand its structure.

### 4. **Data Cleaning and Preprocessing**
- Missing values are checked and handled by dropping rows with missing entries.
- Relevant features (`area`, `bedrooms`, `bathrooms`) are selected, along with the target variable (`price`).

### 5. **Exploratory Data Analysis (EDA)**
- **Correlation Matrix**: Visualized using a heatmap to show relationships between features.
- **Scatter Plots**: Display relationships between individual features and the target variable (`price`).
- **Histogram**: Shows the distribution of house prices.

### 6. **Data Splitting**
The data is split into training and testing sets:
- 80% for training
- 20% for testing

### 7. **Model Building and Training**
A **Linear Regression** model is trained using the selected features and target variable.

### 8. **Model Evaluation**
Key metrics are computed:
- **Mean Squared Error (MSE)**: Measures the average squared difference between predicted and actual values.
- **R-Squared (R²)**: Indicates how well the model explains the variability of the target variable.

### 9. **Visualization of Results**
- Scatter plot showing actual vs. predicted prices.
- Coefficients of the linear regression model are displayed.

---

## Requirements

### Dependencies
Install the required Python libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Dataset
Ensure the dataset (`Housing.csv`) is available in the correct path specified by `dataset_path`.

---

## Running the Code
1. Clone the repository or download the script.
2. Place the `Housing.csv` dataset in the specified path.
3. Run the script using Python:
   ```bash
   python script_name.py
   ```
4. View the outputs, including visualizations and metrics, in the terminal and generated plots.

---

## Results
- **Model Coefficients**: The contribution of each feature to the predicted price.
- **Evaluation Metrics**:
  - Mean Squared Error (MSE)
  - R-Squared (R²)
- Visual comparisons of actual vs. predicted prices.

---

## Notes
- Update the `dataset_path` variable to point to your dataset location.
- Modify the script to handle any specific preprocessing requirements for your dataset.

--- 

