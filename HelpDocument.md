# Help Document

## I. How to Execute

The project has been implemented on Google Colaboratory, which is a free online cloud-based Jupyter notebook environment that allows us to train machine learning models on CPUs, GPUs, and TPUs. To execute the code on Google Colab, select it with a click and then either press the play button to the left of the code, or use the keyboard shortcut - ‘Command/Ctrl+Enter’ .

## II. Packages Used

1. **numpy** : numpy is the core library for scientific computing in Python. It provides a high-performance multidimensional array object, and tools for working with arrays.
2. **pandas** : pandas is a library in Python for data manipulation and analysis
3. **sklearn** : Scikit-learn (sklearn) is a machine learning library for Python. It features various classification, regression and clustering algorithms.
     
     i.  From ‘sklearn.model_selection’,  we import ‘train_test_split’ to split the dataset into train and test  data.
     
     ii.  From ‘sklearn.linear_model’ , ‘sklearn.neighbors’, ‘sklearn.tree’ , ‘sklearn.naive_bayes’, we import classification algorithms  ‘LogisticRegression’,          ‘KNeighborsClassifier’, ‘DecisionTreeClassifier’ and ‘GaussianNB’ respectively.
  
     iii.  From ‘sklearn.metrics’, we import ‘f1_score’, ‘accuracy_score’ and ‘confusion_matrix’’ for the    evaluation of the models.
  
     iv. From ‘sklearn.metrics’, we import ‘roc_curve’ and ‘roc_auc_score’ for plotting the ROC curve and calculating area under the curve.
4. **seaborn** : seaborn is a Python data visualization library. For our project, we used the seaborn’s ‘heatmap’ module to plot the confusion matrix for our models.
5. **matplotlib** : matplotlib helps us create visualizations in python. We have used matplotlib for creating graphs for exploratory data analysis.
