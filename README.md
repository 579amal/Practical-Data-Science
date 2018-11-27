# Practical-Data-Science
My Data Science Experiments
A project done by Amal Joy. 

Instruction to operate the source code file:
1. Data file is taken from the internet so no need of the data file. 
2. Line number 75 is plotting the decision tree in the python screen itself. It requires some additional packages to be installed. In case if you are having trouble installing the packages, just delete that entire chunk. It won’t effect the running of the program.


The project was aimed to build a model to predict if a person is diabetic or not based on his
medical diagnostics. The experiment was conducted using the pima Indians diabetics data.
Numerous issues were present in the data including impossible values and missing values.
These issues were handles appropriately by imputing class average in most of the cases.
Normalization of the variables were applied on the data. A thorough analysis of the features
was conducted and the most important features were selected for building the models.
Different models like KNN, decision trees and Random forest were built on the data. Due to
the issue of data imbalance, oversampling using SMOTE was also tried on KNN model. But it
was later found that the oversampling is actually overfitting the data and the model will not
be useful. Important features were identified from the random forest model and the new data
set was made using only the important features. Comparison of the models were also done and
found that random forest model gave the best results. Parametric tuning was also performed
on all the models. Random search grid was applied on the decision tree and the random forest
model to tune the parameters. Even though the parametric tuning didn’t have much effect on
the random forest model it had a 3.75% improvement on the decision tree model. Cross
validation was applied on all the models and Random Forest model was found to be more stable
than any other model in the experiment with a 10-fold cross validation accuracy of 87.11%.

Thanks for reading
