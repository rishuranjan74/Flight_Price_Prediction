### Flight Price Prediction Project ✈️

This project focuses on building a machine learning model to predict flight prices. By analyzing key factors such as airline, departure time, and travel duration, the model provides valuable insights into the dynamic nature of airfare, helping users make informed booking decisions.

### Key Features ✨

  * **Data Sourcing**: Utilizes a cleaned dataset from Kaggle, ensuring high-quality data for analysis.
  * **Exploratory Data Analysis (EDA)**: Comprehensive visualization and analysis to understand the relationships between different features and the flight price.
  * **Feature Engineering**: Preprocessing of raw data to create new, informative features that enhance model performance.
  * **Model Building & Comparison**: Implementation and evaluation of multiple regression algorithms, including **Linear Regression** and **Random Forest Regressor**.
  * **Performance Metrics**: Evaluation of models using standard regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared ($R^2$) score.

### Methodology 🛠️

1.  **Data Loading and Cleaning**: The project begins by loading the `Clean_Dataset.csv` file. Redundant columns, such as `Unnamed: 0`, are removed to streamline the dataset.
2.  **Exploratory Data Analysis (EDA)**: Visualizations are generated to explore data distributions and relationships. This phase helps identify key trends, such as how prices are affected by the airline, class, and departure time.
3.  **Data Preprocessing**:
      * **Categorical Encoding**: Categorical features like `airline`, `source_city`, and `class` are transformed into a numerical format suitable for machine learning models using `LabelEncoder`.
      * **Outlier Treatment**: Outliers in continuous variables like `duration` are identified and removed to improve model robustness.
4.  **Model Training**: The preprocessed data is split into training and testing sets. Both Linear Regression and Random Forest models are trained on the training data.
5.  **Evaluation**: The trained models are evaluated on the test data using regression-specific metrics and visualizations to compare their predictive accuracy.

### Results and Evaluation 📊

The performance of each model is measured using key regression metrics. The results demonstrate which model provides a more accurate prediction of flight prices.

| Model | Mean Absolute Error (MAE) | R-squared ($R^2$) Score |
| :--- | :---: | :---: |
| **Linear Regression** | 4637.010 | 0.9046 |
| **Random Forest Regressor** | 1076.6306 | 0.9854 |

  * **Observation**: The **Random Forest Regressor** typically outperforms the Linear Regression model, demonstrating its ability to capture complex, non-linear relationships in the data. The project provides clear evidence of which factors most significantly influence flight prices, such as the flight class and the number of days left before departure.


3.  **Run the Notebook**: Open the `Flight_Price_Prediction.ipynb` notebook in your preferred environment (e.g., Google Colab, Jupyter Notebook) and run the cells in order. The notebook contains all the code and explanations to reproduce the entire project.
