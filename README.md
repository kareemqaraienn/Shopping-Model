# Shopping Classification Model
This project implements a machine learning model to predict whether a customer will make a purchase on an e-commerce website, based on various features such as the number of pages they visit, the time they spend on the website, and the month of the year.

## Usage
To run the model, you need to have Python 3 and the scikit-learn library installed on your computer. Once you have these dependencies installed, navigate to the project directory and run the following command:

`python shopping.py data.csv`

Here, data.csv is the path to the CSV file containing the shopping data. You can substitute this with your own data file, as long as it follows the same format as the sample data provided.

## Data
The shopping data used in this project is a publicly available dataset from the UCI Machine Learning Repository. It contains 12,330 instances and 18 features, including numerical, categorical, and binary variables.

## Model
The model used in this project is a k-nearest neighbors (KNN) classifier with k=1. The model is trained on a subset of the data and evaluated on another subset, using a 60:40 train-test split.

## Evaluation
The performance of the model is evaluated using two metrics: sensitivity and specificity. Sensitivity is the proportion of actual positive labels that were accurately identified, while specificity is the proportion of actual negative labels that were accurately identified. The model achieves a sensitivity of 70.17% and a specificity of 90.69% on the test set.

## Conclusion
This project demonstrates the use of a simple KNN classifier to predict customer purchasing behavior on an e-commerce website. The model achieves reasonable accuracy on the test set, and could potentially be improved with additional feature engineering or model tuning.

## Credits
This program's relevant functions were written by me, and is based on a problem set for the course CS50AI from Harvard University. The course material and problem set were created by the staff at Harvard University, and are available at https://cs50.harvard.edu/ai/.
