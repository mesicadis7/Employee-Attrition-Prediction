# Employee-Attrition-Prediction
Predicting employee attrition using Logistic Regression, Decision Trees, and Random Forest classification, along with machine learning.

Contributors:
Adis Mesic
Sasha Maric
Rami Rashid

The dataset used in this project is the ‘IBM HR Analytics Employee Attrition’ dataset available on Kaggle. It contains 1470 samples of Employees with 35 variables. 30 of these variables will be used as predictors to forecast Attrition. Out of the 1,470 employees, 1,233 employees stayed and 237 employees left. The target variable here is Attrition.

To analyze this dataset we performed the following steps:

1. Removed unnecessary information from dataset.

2. Examined the data and created graphs to show the data in other forms.

3. Represented text information using numeric values.

4. To have simpler calculations, we standardized all text to numbers, and also adjusted those already numerical values.

5. 80% for Training, and 20% of the data for Testing

6. We trained and validated the different models using 5 different splits of the training data.

7. Applied class weight averaging.

8. Conducting performance analysis of the models with respect to predicted Attrition.

The baseline model accuracy was 84.01% with average precision and recall of 0.00% and 0.00% respectively.

Improved results were obtained using Random Forest and Decision Tree Classifiers with accuracy of 83.33% and 82.31% respectively. Precision, recall and F1 score of these models were 47.50%, 40.43% and 43.68% respectively and 43.24% and 34.04% respectively.

Key Findings:

1. Logistic Regression models outperformed the other models overall.

2. Recall for the Random Forest models was higher compared to other models we tested.

3. Among all the variables used to predict attrition, overtime was the most effective.

4. Random Forest models, when used with class weight, improved cross validation F1 scores.

5. In this case, increased accuracy of the model did not indicate correct classification of instances.

Installation:

Install the following modules using the command below.

   pip install -r requirements.txt

Run the project

1. Download or clone this repository.
2. Go to the notebook located in the ‘notebooks’ directory and open it with Jupyter notebook or Google Colab.
3. If prompts appear for missing modules, install the modules and repeat step 2.
4. Run every cell in the notebook.

The dataset will be automatically downloaded from KaggleHub.

Limitations:

Artificial employee records were used in the dataset. Therefore, the true potential and limitations of the models used in this project are apparent. Some of the variables used in the models may be confounding variables and do not necessarily represent true cause and effect relationships.

AI Disclosure:

Code samples and explanations on how to implement the project models were generated using AI. Also setting up the GitHub and giving us a process throughout the project was aided by AI.
