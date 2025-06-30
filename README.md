# Decision-Trees-and-Random-Forest

**NAME**: MURARI YAMINI

**OBJECTIVE** : learn tree based models for classification and regression
we explore how Decision Trees and Random Forests can be used to predict whether a tumor is malignant(cancerous tumor) or benign(non cancerous) based on its physical characteristics.

This task also covers:

Tree pruning to reduce overfitting

Random forest ensemble learning

Feature importance analysis

Model evaluation using accuracy and cross-validation

### libraries used
| tool | used for |
|---------|--------|
| python	| Programming language|
| pandas  | dataset loading(csv) |
| matplotlib| visualization of tree and features|
| scikit-learn | machine learning models and other packages|

### Dataset
Features Used:

- radius_mean

- texture_mean

- perimeter_mean

- area_mean

Target:

- Diagnosis: M(Malignant),B(Benign)

### steps involved
1.data loading and preprocessing

  - loaded csv file using pandas

  - mapped diagnosis(M,B) to numeric values(0,1)

2.model training

- trained a decision tree classifier

- trained a pruned  tree with max_depth=3 to prevent overfitting

 - trained a Random Forest Classifier with 100 trees

3.visualization

  - visualized the pruned decision tree using plot_tree

  - displayed a bar chart of feature importance from the random forest

4.model evaluation

  - evaluated models using accuracy score

  - performed cross-validation(cv=3) to assess generalization
### Results
printed the accuracy of:

- Decision Tree

- pruned Decision Tree

- Random Forest

Visualized:

- pruned tree structure for interpretability

- feature importance chart for understanding the most influential features

 - performed cross-validation to reduce bias from a single train-test split

   ### OUTPUT :
   ![Image](https://github.com/user-attachments/assets/db0bb7a6-f11e-4779-841d-e31344a59a1b)
   
