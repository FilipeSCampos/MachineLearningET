# MachineLearningET
# Classification Using Decision Trees

This code demonstrates the use of decision trees for classification tasks. It uses the `sklearn` library in Python to build a decision tree model and evaluate its performance.

## Dataset

The dataset used for this project is stored in the `CCARDBALANCE.xlsx` file. It contains information about credit card holders, including their demographic characteristics and monthly spending.

## Usage

1. Install the required dependencies by running the following command:

```
import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeRegressor
from sklearn.metrics import mean_squared_error
from sklearn.tree import DecisionTreeClassifier, plot_tree,export_graphviz
from sklearn import tree
from sklearn.tree import export_text
from sklearn.ensemble import RandomForestRegressor
import matplotlib.pyplot as plt
```


2. Run the `TrabalhoML.ipynb` script. This will perform the following steps:

- Load the dataset from the `CCARDBALANCE.xlsx` file.
- Preprocess the data by converting string values to numeric values.
- Split the dataset into training and testing sets.
- Train a decision tree classifier using the training data.
- Evaluate the model's performance on the testing data.
- Display the decision tree visualizations.

3. The script will output the following information:

- Number of leaves in the decision tree.
- Depth of the decision tree.
- Decision tree visualization.
- Feature importance statistics.
- Accuracy score on the training set.
- Accuracy score on the testing set.

4. To make predictions on new data, create a dictionary with the input values for each feature and pass it to the `predict` method of the trained model. The output will be the predicted class label.

## Results

The decision tree model achieves an accuracy of 96% on the testing classification set and 83% on the regression test, indicating its effectiveness in classifying credit card holders' spending behavior.

The data
![Capturar](https://github.com/FilipeSCampos/MachineLearningET/assets/113521439/77295436-111e-4e63-bbd3-5d3ef1d31b3d)

The Classifier tree model 
![image](https://github.com/FilipeSCampos/MachineLearningET/assets/113521439/911ba371-7a2a-4510-869e-b4da1e9b8992)


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

