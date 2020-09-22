# EECS-731-Project-2
EECS 731 Homework 2

#### Project 2 - To be, or not to be
Classy Shakespeare plays and players

1. Set up a data science project structure in a new git repository in your GitHub account
2. Download the Shakespeare plays dataset from https://www.kaggle.com/kingburrito666/shakespeare-plays
3. Load the data set into panda data frames
4. Formulate one or two ideas on how feature engineering would help the data set to establish additional value using exploratory data analysis
5. Build one or more classification models to determine the player using the other columns as features
6. Document your process and results
7. Commit your notebook, source code, visualizations and other supporting files to the git repository in GitHub

#### Steps followed
1. Download the data and load the csv file.
2. Clean the data by removing rows with missing values
3. Compute extra features that can add value to the domain.
4. Implement the classifiers and observe the accuracy (fbeta score)

#### References
1. https://www.kaggle.com/mallaham/network-analysis-of-shakespeare-plays
2. https://ailephant.com/basics-nlp-with-nltk/#:~:text=In%20Python%2C%20this%20is%20most%20commonly%20done%20with,transcribed%20into%20text%2C%20or%20to%20generate%20new%20text
3. https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html
4. https://scikit-learn.org/stable/auto_examples/classification/plot_digits_classification.html#sphx-glr-auto-examples-classification-plot-digits-classification-py
5. https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.MultinomialNB.html#sklearn.naive_bayes.MultinomialNB
