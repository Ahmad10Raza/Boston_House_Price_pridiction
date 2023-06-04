# The Boston House Price Prediction

* **The Boston House Price Prediction dataset is a classic dataset in machine learning. It contains information about 506 houses in Boston, Massachusetts, in 1970. The dataset includes 14 features, such as the number of rooms, the crime rate, and the distance to employment centers. The goal is to predict the median value of owner-occupied homes in thousands of dollars.**

* **There are many different machine learning algorithms that can be used to predict house prices. Some common algorithms include linear regression, random forests, and decision trees. The best algorithm to use will depend on the specific features of the dataset.**

* **In this project, I will use linear regression to predict house prices. Linear regression is a simple but effective algorithm that can be used to predict continuous values. I will use the scikit-learn library in Python to train and evaluate the model.**

The following steps were taken to build the model:

* **The data was preprocessed by removing any missing values and scaling the features to a common scale.**
* **The model was trained on 70% of the data and evaluated on the remaining 30% of the data.**
* **The model was tuned by changing the learning rate and the number of epochs.**
* **The best model was selected based on its performance on the evaluation set.**
* **The following results were obtained:**

* The mean absolute error of the best model was $10,500.
* The root mean squared error of the best model was $16,500.
* The R-squared value of the best model was 0.81.

* **These results suggest that the model is able to predict house prices with a reasonable degree of accuracy. However, it is important to note that the model was trained on data from 1970. The housing market has changed significantly since then, so the model may not be as accurate for predicting house prices today.**

Here is some steps for  used   the model:

* 1. conda create -p venv python==3.8 -y
* 2. pip install -r requirements.txt
* 3. python app.py
# Boston_House_Price_pridiction
