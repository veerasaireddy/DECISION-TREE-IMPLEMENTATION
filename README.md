# DECISION TREE IMPLEMENTATION

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : BUSIREDDY VEERA SAI REDDY

*INTERN ID* : CT04DM982

*DOMAIN* : MACHINE LEARNING

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTHOSH KUMAR


📄 Task 1: Decision Tree Classification Using Scikit-learn

As part of the CodTech Machine Learning Internship, Task 1 focuses on building and visualizing a decision tree classification model using the Scikit-learn library in Python. The objective of this task is to apply one of the most interpretable and powerful machine learning algorithms — the Decision Tree — to a classification problem, while understanding the decision-making process and evaluating the model’s performance.

In this task, the well-known Iris dataset was used for training and testing the model. The Iris dataset is a classical dataset in the field of machine learning and statistics. It contains a total of 150 instances of iris flowers, divided into three species: Iris setosa, Iris versicolor, and Iris virginica. Each instance in the dataset includes four numerical features: sepal length, sepal width, petal length, and petal width — all measured in centimeters. The goal is to build a model that can classify an iris flower into one of these three species based on the input features.

The process began with loading the dataset using the load_iris() function provided by Scikit-learn. This dataset is already pre-cleaned, so there was no need for extensive data preprocessing. However, exploratory data analysis was performed by converting the data into a Pandas DataFrame for better readability and visualization. The dataset was then split into input features (X) and target labels (y).

To evaluate the model's ability to generalize to unseen data, the dataset was split into training and testing sets using an 80-20 ratio. This was done using Scikit-learn’s train_test_split() method. The training data was then used to fit a Decision Tree Classifier using the DecisionTreeClassifier class. For this task, the entropy criterion was used to determine the quality of the splits. The entropy criterion is based on the concept of information gain, which measures how well a particular feature separates the classes.

After training the model, the next step was to visualize the decision tree. Visualization is a major strength of decision trees, as it allows users to interpret the decision-making process of the model. The plot_tree() function from the sklearn.tree module was used to visualize the tree structure. This visualization clearly shows how the data is split at each internal node based on feature thresholds and which classes are predicted at the leaf nodes. The tree diagram also includes feature names and class names for better clarity.

Following the visualization, the model was evaluated on the test dataset. Predictions were made using the predict() method, and the model’s performance was assessed using evaluation metrics such as accuracy score and a classification report. The accuracy score represents the proportion of correctly classified instances, while the classification report provides precision, recall, and F1-score for each class. The model achieved high accuracy, indicating that the decision tree was able to learn meaningful patterns in the data.

The final deliverable for this task is a well-commented Jupyter Notebook titled task1_decision_tree.ipynb, which contains all the necessary components: data loading, visualization, model training, and evaluation. The notebook demonstrates a step-by-step machine learning pipeline and provides visual and statistical insights into the performance of the model.

In conclusion, Task 1 provided a comprehensive introduction to decision tree models, from understanding the dataset and training a model, to interpreting its decisions through visualization. It strengthened skills in using Scikit-learn, working with structured datasets, and evaluating machine learning models, while emphasizing the importance of model explainability and interpretability. This foundational task lays the groundwork for more complex machine learning projects in subsequent tasks of the internship.

