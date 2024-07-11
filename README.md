# Personal Health Cost Prediction

This project aims to predict the health costs for individuals based on age and other factors using a dataset from Kaggle. Various regression models were evaluated, and the Decision Tree Regressor provided the best results with an accuracy of 99.67%.

## Dataset

The dataset used for this project includes the following features:

- Age
- BMI (Body Mass Index)
- Children
- Smoker Status
- Region
- Charges (Target Variable)

The dataset can be found on Kaggle: [Mental Health Cost Dataset](https://www.kaggle.com/your-dataset-url)

## Models Evaluated

The following regression models were evaluated:

1. Linear Regression
2. Random Forest Regression
3. Polynomial Regression
4. SVM Regression
5. Decision Tree Regressor

## Best Model: Decision Tree Regressor

The Decision Tree Regressor outperformed all other models with an accuracy of 99.67%. The following plot shows the comparison of actual vs. predicted values for the Decision Tree Regressor.

![image](https://github.com/user-attachments/assets/adcb4acf-9720-4262-83be-c242a527595e)

## Plot Explanation

The plot illustrates the predicted values against the actual values. The black dashed line represents the line of perfect predictions, where the predicted values exactly match the actual values. The blue points represent the actual values, and the red points represent the predicted values. The closer the points are to the dashed line, the better the model performance.

## Usage

To replicate the results, follow the steps below:

1. Clone the repository:
    ```sh
    git clone https://github.com/AnushkaShendge/MedicalCostPersonal_Model.git
    ```
2. Navigate to the project directory:
    ```sh
    cd MedicalCostPersonal_Model
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```
4. Run the regression model script:
    ```sh
    python regression_models.py
    ```

## Conclusion

The Decision Tree Regressor provided the best results with an accuracy of 99.67%. This model can be used for high-accuracy predictions of health costs based on age and other factors.

