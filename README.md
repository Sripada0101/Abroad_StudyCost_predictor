# **Abroad Study Cost Predictor**

This project focuses on analyzing and predicting the cost of studying abroad using exploratory data analysis (EDA) and machine learning. The dataset includes study costs across various countries, course types, and specializations. The project employs comprehensive data preparation, model training, and evaluation techniques to achieve accurate predictions.

## **Project Workflow**

The project follows a structured workflow to preprocess, analyze, and model the data effectively:

### **1. Data Cleaning**
- Handle missing values by replacing them with the mode of the respective column.
- Remove duplicate rows to ensure data integrity.
- Detect and eliminate outliers using the Interquartile Range (IQR) method to retain only meaningful data.

### **2. Data Smoothing**
- Apply exponential smoothing to the `FEES` column to reduce noise and enhance the clarity of trends.

### **3. Data Normalization**
- Scale numerical data to ensure uniformity and prepare it for model training.

### **4. Correlation Analysis**
- Analyze relationships between features using correlation heatmaps.
- Identify key predictors for study costs.

### **5. Data Reduction**
- Use feature selection techniques to reduce dimensionality while retaining the most impactful variables.

### **6. Model Selection**
- Compare multiple regression models, including Random Forest and Gradient Boosting, to find the most suitable for prediction.

### **7. Model Training**
- Train the selected models on the preprocessed dataset.
- Optimize hyperparameters for better performance.

### **8. Model Evaluation**
- Evaluate the models using metrics such as Root Mean Squared Error (RMSE) and R-squared (R²).
- Compare the performance of different models and finalize the best one.

### **9. Data Visualization**
- Visualize trends in study costs using bar plots, line plots, and scatter plots.
- Generate visual representations of the model's predictions versus actual values.


## **Files**

- `dsprojj2.csv`: Original dataset file containing study cost data.
- `dsproj.ipynb`: Jupyter Notebook with the complete code for the project.
- `aggregated_data.csv`: Aggregated dataset generated during the process.
- `generalized_data.csv`: Generalized dataset after transformations.
- `requirements.txt`: List of Python libraries required to run the project.


## **Results**

This project successfully analyzes and predicts the cost of studying abroad based on various factors, including course types, countries, and specializations. The models used in this analysis provided valuable insights into the relationships between features and study costs, demonstrating strong performance in the evaluation process. The key highlights include:

- **Preprocessing**: Data cleaning, smoothing, and normalization steps were applied to ensure the dataset was properly prepared for model training, enhancing the quality and consistency of the data.
  
- **Model Evaluation**: After comparing multiple regression models, the **Gradient Boosting Regressor** outperformed the **Random Forest Regressor**. The Gradient Boosting model demonstrated a **lower RMSE** and a **higher R²**, making it the most accurate model for predicting study costs. These results were verified and visualized through comparison graphs to highlight the performance differences.

- **Visualization**: Several visualizations, including prediction vs. actual graphs, were used to better understand trends in the data and assess the accuracy of the model predictions.

## License
This project is licensed under the MIT License.
