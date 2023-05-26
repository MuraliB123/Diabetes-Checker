# Machine Learning - Diabetes Checker

This repository holds my works on machine learning for the Diabetes Checker project. The project aims to provide an easy monitoring system to detect the chances of diabetes among women.

## Approach

1. Imported the dataset from Kaggle and removed unnecessary columns.
2. Performed Exploratory Data Analysis (EDA).
3. Treated outliers using the quantile method, manually fixing the min and max percentiles for each feature column.
4. Observed collinearity and removed redundant features.
5. Created box plots and scatter plots for data visualization.
6. Implemented classification algorithms and noted performance metrics.
7. Performed cross-validation to find the optimum kernel for the Support Vector Classifier.
8. Applied SMOTE sampling for handling imbalanced data.
9. Analyzed the performance metrics report and identified the optimum algorithm.
10. Saved the final model into a pickle file.

## Usage

To use the Diabetes Checker model, follow these steps:

1. Install the required dependencies (e.g., NumPy, Pandas, scikit-learn).
2. Download the dataset from [Kaggle](link-to-dataset).
3. Run the preprocessing script to prepare the data.
4. Train the model using the provided scripts.
5. Use the trained model to make predictions on new data.

## Results

The project achieved an accuracy of X% on the test set. Further details and performance metrics can be found in the [Results](link-to-results) section.

## Future Work

In the future, I plan to improve the project by:
- Adding more features to improve the accuracy of predictions.
- Exploring different machine learning algorithms to compare performance.
- Enhancing the data preprocessing steps for better handling of outliers and missing values.

## License

This project is licensed under the [MIT License](link-to-license).

