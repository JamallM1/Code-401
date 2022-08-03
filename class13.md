# Class 13

## How to run Linear regression in Python scikit-Learn
- you can do linear regression using numpy, scipy, stats model and sckit learn
- Scikit-learn is a powerful Python module for machine learning and it contains functions for regression, classification, clustering, model selection and dimensionality reduction.

## STEPS
1. Accessing sklearn 
  - from (Blank) IMPORT load_blank
  - blank = load_blank


2.The object 'Blank' is a dictionary, so you can explore the keys of this dictionary.
  - blank.keys()
  - ['data', 'feature_names', 'Descr', 'target'

3. I am going to print the feature names of blank data set.
  - print blank.feature_names

4. I am going to convert boston.data into a pandas data frame.
  - bla = pd.DataFrame(blank.data)
  - bla.head()
  - As you can see the column names are just numbers, so I am going to replace those numbers with the feature names.

5. Replacing the numbers with names 
  - bla.columns = blank.feature_names
  - bla.head()
  

