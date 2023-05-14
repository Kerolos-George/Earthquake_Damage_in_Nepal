# Earthquake_Damage_in_Nepal
This project involves building a classification model using Decision Tree algorithm. Decision tree is a supervised machine learning algorithm used for classification and regression tasks. It works by splitting the data based on a set of conditions (features) that best separates the data into their respective classes or categories.
## Data Wrangling
The data was imported and wrangled with the wrangle function created in the wrangling notebook. The cleaning process involved creating a binary target, identifying leaky columns (columns that reveal information about the target), identifying high cardinality columns (columns with a large number of unique values), and handling missing values.
## Data Splitting
The data was split into training, testing, and validation datasets. The validation dataset was used to evaluate the performance of the model during hyperparameter tuning.
## Model Building
OrdinalEncoder was used to encode categorical variables. OrdinalEncoder is a scikit-learn encoder that converts categorical variables to integers.

The model initially overfit the training data, so some hyperparameter tuning was done to find the best depth to train the data with and also to ensure it generalizes well to new data.
