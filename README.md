# Energy Consumption Forecasting in a Steel Industry

## 📖 **Overview**
This project aims to predict energy consumption in a small-scale steel industry using machine learning techniques. Accurate forecasting of electricity usage helps optimize energy management and reduce operational costs, enabling better decision-making in the steel production process.

The dataset includes features like reactive power, CO2 emissions, power factors, and time-based attributes (day of the week, time of day). We used two regression methods for training and evaluating the model: **Linear Regression** and **Random Forest Regression**.

---

## 🚀 **Project Objectives**
- Forecast energy consumption (`Usage_kWh`) based on multiple features.
- Compare the performance of **Linear Regression** and **Random Forest Regression** models.
- Visualize model results and evaluate them using performance metrics like **Mean Squared Error (MSE)** and **R² score**.
- Provide actionable insights through visualizations.

---

## 📂 **Dataset**
The dataset includes:
- **Date**: Timestamp of energy readings.
- **Usage_kWh**: Target variable representing energy consumption.
- **Lagging/Leading Current Reactive Power**: Reactive power measurements.
- **CO2 (tCO2)**: CO2 emissions.
- **Power Factor**: Measures of electrical efficiency.
- **NSM (Number of Seconds in a Day)**: Time-based numerical feature.
- **Categorical Variables**: Day of the week, weekend/weekday, and load type.

---

## 🔧 **Methods Used**
We trained the model using two regression techniques:
1. **Linear Regression**: A simple and interpretable algorithm that assumes a linear relationship between features and the target variable.
2. **Random Forest Regression**: An ensemble method that builds multiple decision trees and averages their predictions to improve accuracy and handle non-linear relationships.

---

## 📊 **Results**
### Performance Metrics:
| Metric          | Linear Regression  | Random Forest Regression |
|------------------|--------------------|---------------------------|
| **MSE**         | 17.85              | 5.47                      |
| **R² Score**    | 0.9843             | 0.9961                   |

- **Linear Regression**: Provided a high R² score, indicating that it captures most of the variance, but the high MSE suggests larger errors for some predictions.
- **Random Forest Regression**: Outperformed Linear Regression with a lower MSE, handling complex patterns better and achieving a near-perfect R² score.

---

## 🛠️ **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - `pandas` & `numpy`: Data manipulation and processing.
  - `matplotlib`: Visualizations.
  - `sklearn`: Machine learning algorithms and metrics.

---

## 📈 **Visualizations**
The following visualizations were used to analyze and interpret the results:
1. **Actual vs Predicted Values**: Scatter plot comparing true energy usage with predicted values.
2. **Residual Plot**: Visualizes errors to check for model bias or patterns.
3. **Feature Importance (Random Forest)**: Highlights which features contributed the most to predictions.
4. **Energy Usage Trends**: Time-series plot of energy consumption over time.

---

## 🧠 **How to Run**
1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib scikit-learn

2. Download the dataset and place it in the project directory.
3. Run the notebook or script to train and evaluate the models.




markdown
Copy code
# Energy Consumption Forecasting in a Steel Industry

## 📖 **Overview**
This project aims to predict energy consumption in a small-scale steel industry using machine learning techniques. Accurate forecasting of electricity usage helps optimize energy management and reduce operational costs, enabling better decision-making in the steel production process.

The dataset includes features like reactive power, CO2 emissions, power factors, and time-based attributes (day of the week, time of day). We used two regression methods for training and evaluating the model: **Linear Regression** and **Random Forest Regression**.

---

## 🚀 **Project Objectives**
- Forecast energy consumption (`Usage_kWh`) based on multiple features.
- Compare the performance of **Linear Regression** and **Random Forest Regression** models.
- Visualize model results and evaluate them using performance metrics like **Mean Squared Error (MSE)** and **R² score**.
- Provide actionable insights through visualizations.

---

## 📂 **Dataset**
The dataset includes:
- **Date**: Timestamp of energy readings.
- **Usage_kWh**: Target variable representing energy consumption.
- **Lagging/Leading Current Reactive Power**: Reactive power measurements.
- **CO2 (tCO2)**: CO2 emissions.
- **Power Factor**: Measures of electrical efficiency.
- **NSM (Number of Seconds in a Day)**: Time-based numerical feature.
- **Categorical Variables**: Day of the week, weekend/weekday, and load type.

---

## 🔧 **Methods Used**
We trained the model using two regression techniques:
1. **Linear Regression**: A simple and interpretable algorithm that assumes a linear relationship between features and the target variable.
2. **Random Forest Regression**: An ensemble method that builds multiple decision trees and averages their predictions to improve accuracy and handle non-linear relationships.

---

## 📊 **Results**
### Performance Metrics:
| Metric          | Linear Regression  | Random Forest Regression |
|------------------|--------------------|---------------------------|
| **MSE**         | 17.85              | 5.47                      |
| **R² Score**    | 0.9843             | 0.9961                   |

- **Linear Regression**: Provided a high R² score, indicating that it captures most of the variance, but the high MSE suggests larger errors for some predictions.
- **Random Forest Regression**: Outperformed Linear Regression with a lower MSE, handling complex patterns better and achieving a near-perfect R² score.

---

## 🛠️ **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - `pandas` & `numpy`: Data manipulation and processing.
  - `matplotlib`: Visualizations.
  - `sklearn`: Machine learning algorithms and metrics.

---

## 📈 **Visualizations**
The following visualizations were used to analyze and interpret the results:
1. **Actual vs Predicted Values**: Scatter plot comparing true energy usage with predicted values.
2. **Residual Plot**: Visualizes errors to check for model bias or patterns.
3. **Feature Importance (Random Forest)**: Highlights which features contributed the most to predictions.
4. **Energy Usage Trends**: Time-series plot of energy consumption over time.

## 🔍 **Insights**
- **Key Features**: The `NSM`, `CO2`, and `Lagging Current Reactive Power` were highly influential in predicting energy consumption.
- **Model Choice**: While Linear Regression is simple and interpretable, Random Forest Regression provides superior performance for this dataset due to its ability to model complex relationships.


## 📜 **Conclusion**
This project demonstrates the potential of machine learning in optimizing energy management in the steel industry. The **Random Forest Regression** model showed excellent performance, making it suitable for deployment in real-world applications.

For further improvements, incorporating additional features like weather data or production specifics could enhance accuracy.

