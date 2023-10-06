# Medical-Insurance-Premium-Prediction

Medical Insurance Premium Prediction

The project focuses on building machine learning models that predict medical insurance premium charges. 

1. Dataset
   
   Source: Kaggle
   Description: contains medical records of various individuals.
   Features: age, sex, BMI, children, smoker, region
   Target: charges

2. Libraries

   pandas, numpy, matplotlib, sea
   born, sklearn, xgboost

4. Data Exploration

   * defining categorical and numerical variables
   * statistical summary

5. Data Preprocessing

   * Encoding categorical variables
   * correlation matrix
   * Feature Scaling

6. Model

   * linear regression
   * random forest
   * xgboost

Key Analysis

* The dataset was cleaned and no null values were found.
* age, BMI, and smoker features were highly correlated with charges.
* northwest and southwest regions had a negative correlation with charges
* r2_score: xgboost > random forest > linear regression

***************************************************
Usage

To run the code and reproduce the results, follow these steps:

Clone the repository. Open the Jupyter Notebook file "Medical Insurance Premium Prediction.ipynb" in Jupyter Notebook or any compatible environment. Ensure the required libraries are installed. Run the code cells sequentially to execute the data preprocessing steps, model building, and evaluation. The final results and performance metrics will be displayed in the notebook. Feel free to explore and modify the code as needed to further analyze the dataset or experiment with different models and techniques.

References

Dataset source: Medical Cost Personal Datasets

Credits

I would like to give credit to the "Build 10 Real World Machine Learning Projects" by "Vijay Gadhave". The code and project structure in this repository were developed based on the lessons and instructions provided in the course. I highly recommend checking out the course for detailed explanations and in-depth learning.
