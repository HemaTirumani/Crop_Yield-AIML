**Project: Crop Yield Prediction Using Machine Learning**
**Problem Understanding:**
Crop yield prediction is an important task in agriculture as it helps in planning, resource management, and decision-making. Crop yield depends on multiple factors such as crop type, season, cultivated area, rainfall, fertilizer usage, pesticide usage, and geographic location.
The goal of this project is to develop a machine learning model that predicts crop yield using historical agricultural data. The dataset contains records of different crops grown across various states over multiple years along with environmental and input-related factors. By learning patterns from past data, the model aims to predict future crop yield accurately.
This project focuses not only on achieving good prediction accuracy but also on understanding how different features influence the predicted yield. Visualization and feature importance analysis are used to interpret the model’s behavior, ensuring transparency and better reasoning behind predictions.

**Data Preprocessing:**
*   Loaded the crop yield dataset and verified data quality
*   Encoded categorical variables such as Crop, Season, and State
*   Selected Yield as the target variable
*   Split the dataset into training and testing sets (80% training, 20% testing)

**Model Selection & Training:**
Implemented two ensemble regression models:
*   Random Forest Regressor
*   Gradient Boosting Regressor
These models were chosen because they:
*   Handle non-linear relationships effectively
*   Perform well on structured agricultural data
*   Reduce overfitting compared to simple regression models
*   Both models were trained and evaluated for performance comparison

**Results & Evaluation Metrics:**
*   Model performance was evaluated using standard regression metrics:
*   R² Score – Measures how well the model explains variance in crop yield
*   Mean Absolute Error (MAE) – Average magnitude of prediction error
*   Root Mean Squared Error (RMSE) – Penalizes larger prediction errors

**Model Comparison:**
*   Gradient Boosting achieved slightly better
*   performance than Random Forest
*   Both models demonstrated strong predictive capability
*   Performance comparison was visualized using bar charts

**Model Reasoning & Visualization:**
To ensure interpretability and reasoning beyond accuracy, the following visualizations were used:
*   **Feature Importance Plots:**
      Show how much each feature contributes to yield prediction for both models
*   **Actual vs Predicted Scatter Plots:**
      Compare predicted values with actual yield values to assess prediction quality
*   **Model Performance Comparison Plot:**
      Visually compares R² scores of Random Forest and Gradient Boosting
These visualizations help explain why the model makes certain predictions and identify the most influential factors affecting crop yield.
