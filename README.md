# Credit Score Classification

The following project contains a python script that trains a machine learning model to predict the credit score of a person. The valid responses for prediction are 'Good', 'Standard' and 'Poor'.

# Technologies Used

* R (for data cleaning and preprocessing)
* Python (for building the machine learning model)

# Brief Description about the Repository files

* archive/ - This directory actually contains the data after preprocessing and cleaning
* Original_data/ - This directory contains the original data before preprocessing and cleaning
* classificationscript.R - This is the R script that contains all the commands that were executed during the data preprocessing and cleaning
* Classifier.ipynb - This is the actual file that contains the code for building the machine learning model

# Description of Data Cleaning and Preprocessing Step

In this step, a variety of tasks were done on the data to make it ready for building the model. Given below is a brief description of the same:

1. Removed the unnecessary characters like '-' and '_' from the end of some of the columns
2. Removed some unnecessary columns that would not play a huge role in the final prediction of the model
3. Fixed some seemingly incorrect values through processes like forward fill and replaced some of the empty values with the mean of their respective columns
4. Encoded some character values into numbers that the Machine Learning model would understand
5. Performed One-hot encoding of the occupation column

# Description of the Machine Learning Model

For the purposes of this project, we will use three types of machine learning models and evaluate the performance of all three to come to a conclusion as to which model performs best. The three different models are Decision Tree, Random Forest and XGBoost. More details can be found in the Classifier.ipynb cells.

# Links

Below you can find my Twitter and LinkedIn Pages. Feel free to connect. :blush:. Thank you for reading through this Project.

* LinkedIn - https://www.linkedin.com/in/imankalyanchakraborty/
* Twitter - https://twitter.com/ikc1975