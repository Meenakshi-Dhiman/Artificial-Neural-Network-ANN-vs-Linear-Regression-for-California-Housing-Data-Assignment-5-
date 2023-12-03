# Artificial-Neural-Network-ANN-vs-Linear-Regression-for-California-Housing-Data-Assignment-5-

**California Housing Price Prediction: Linear Regression vs. Artificial Neural Network
Executive Summary:**
This report presents an analysis of predicting house prices in California using two different approaches: Linear Regression and Artificial Neural Network (ANN). The California Housing dataset was utilized, and the models were implemented and compared based on performance metrics.

1. Data Preprocessing:
1.1 Dataset Exploration:
The California Housing dataset was loaded using scikit-learn. Features related to housing in California were examined, and basic statistics were generated.

1.2 Handling Missing Values and Outliers:
Missing values were checked and handled appropriately. Outliers were addressed using the Z-score method to maintain data integrity.

1.3 Splitting the Dataset:
The dataset was split into training and testing sets, with 80% used for training and 20% for testing.

2. Linear Regression:
2.1 Model Implementation:
A Linear Regression model was implemented using scikit-learn. The model was trained on the training set.

2.2 Model Evaluation:
The performance of the Linear Regression model was evaluated using Mean Squared Error (MSE) and R2 Score on the testing set.

3. Artificial Neural Network (ANN):
3.1 Model Design:
A simple ANN for regression was designed using TensorFlow/Keras. The architecture included a dense layer with ReLU activation and an output layer.

3.2 Model Training:
The ANN was trained on the training set using the Adam optimizer and mean squared error loss.

3.3 Model Evaluation:
The performance of the ANN was evaluated using the same regression metrics as Linear Regression on the testing set.

4. Comparison and Analysis:
4.1 Performance Metrics:
Metrics for both models were compared, including Mean Squared Error and R2 Score.

4.2 Strengths and Weaknesses:
The strengths and weaknesses of each model were discussed, considering factors like interpretability, computational complexity, and model flexibility.

4.3 Complexity Analysis:
An analysis was conducted to determine whether the complexity of the ANN provided better predictive performance compared to Linear Regression.

5. Visualization:
Scatter plots were created to visually compare the predicted values of both models with the actual values. Additionally, efforts were made to visualize the model architectures.

6. Conclusion:
The key findings were summarized, providing insights into the performance of both models. The report discussed which model performed better for predicting house prices in the California Housing dataset.

7. Challenges Encountered:
Challenges during the implementation process included addressing data quality issues, determining the optimal model complexity, interpreting the results, and tuning hyperparameters.

8. Recommendations:
Based on the analysis, recommendations were made regarding the choice of model for predicting house prices in the California Housing dataset.

9. Future Work:
Suggestions for future work include exploring more advanced neural network architectures, conducting hyperparameter tuning, and experimenting with feature engineering.
