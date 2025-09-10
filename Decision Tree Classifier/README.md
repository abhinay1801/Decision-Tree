# Decision Tree Classifier – Iris Dataset

This project demonstrates the implementation of a **Decision Tree Classifier** on the **Iris dataset** using Python and scikit-learn.  
The focus is on **pre-pruning** and **hyperparameter tuning** to improve accuracy and avoid overfitting.


## Decision Tree Classifier

### Description
The **Decision Tree Classifier** is trained on the Iris dataset to predict flower species based on four features.  
Pruning and parameter tuning are applied to optimize the model.

### Key Steps
- Load the Iris dataset (`sklearn.datasets.load_iris`)  
- Train a **DecisionTreeClassifier**  
- Apply **pre-pruning** with parameters:  
  - `max_depth`  
  - `min_samples_split`  
  - `min_samples_leaf`  
  - `criterion` (Gini/Entropy)
- Perform **hyperparameter tuning** with GridSearchCV  
- Evaluate with:  
  - Accuracy Score  
  - Train/Test comparison  


## Results
- **Default Decision Tree**: Good accuracy but risk of overfitting  
- **Tuned Decision Tree**: Improved accuracy & better generalization  
