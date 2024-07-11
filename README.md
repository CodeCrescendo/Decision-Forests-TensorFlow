# Decision-Forests-TensorFlow
Implementing and analyzing Random Forest and Gradient Boosted Trees using TensorFlow's Decision Forest library

1.Project Overview: This project involves experimenting with TensorFlow's Decision Forest (TF-DF) library to train, test, and interpret Random Forests and Gradient Boosted Trees for classification tasks using student grading data.

2.Data Preprocessing: The dataset includes scores of students across various components, with grades as the target variable. The data is loaded into a Pandas dataframe, and label encoding is performed on ordinal data such as grades and attendance. TensorFlow decision forests handle numerical and categorical data natively, so preprocessing steps are tested with and without encoding.

3.Random Forest Model: A random forest model is constructed using TensorFlow's Decision Forest library. The dataset is split into training and testing sets using a 70-30 rule. The model is trained on the training dataset and evaluated on the test set. The first tree in the trained model is visualized to understand the decision-making process.

4.Gradient Boosted Trees Model: Gradient boosted decision trees are implemented and their performance is compared with the random forest model. The accuracy and log loss of both models are analyzed to determine their robustness and effectiveness.

5.Hyperparameter Tuning: The training and testing accuracies of the models are compared to find optimal hyperparameters such as the number of trees (n_trees) and maximum depth (max_depth). The impact of different values of these hyperparameters on model performance is studied to achieve a reasonable accuracy of 85% and above.

6.Visualization and Analysis: The hypothesis space is visualized by producing scatter plots of the dataset. The performance of the models is documented, and the effects of varying hyperparameters on accuracy and robustness are analyzed.

7.Submission and Results: The implementation includes code for data preprocessing, model training, evaluation, and visualization. The final submission consists of a cleaned Jupyter notebook and a readme file with group members' names and IDs. The results, including accuracy, log loss, and plots, are documented.
