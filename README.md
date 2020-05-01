![Diabetes-Onset-Detection-with-Deep-Learning](https://miro.medium.com/max/2560/1*TJapPdGxjpOh5FxDwG18rQ.jpeg)
# Diabetes Onset Detection Using Supervised Machine Learning Techniques
We obtained the Diabetes Onset Dataset from Kaggle's website and used Jupyter Notebook as the platform for the purpose of coding. Our methodology involves use of GridSearchCv with neural networks.
## A. Feature Selection
Feature selection is finding the subset of original features by different approaches based on the information they provide, accuracy, prediction errors.
The features used in the project are:
- n_pregnant
- glucose_concentration
- blood_pressuer (mm Hg)
- skin_thickness
- BMI
- pedigree_function
- age
- class
## B. Model Selection
Neural Network with:
* epochs = 50, 
* batch_size = 10, 
* learn_rate = 0.01, 
* init = uniform and 
* activation = linear
## C. Training the models with Data
The data taken is from **https://www.kaggle.com/uciml/pima-indians-diabetes-database**
## D. Taining Data and Testing Data
Data is divided using KFold in sklearn library.
### Then the Class is predicted:
- 1 if Diabetic
- 0 if Non-Diabetic
# Result =>
Algorithm has a bit low accuracy of nearly 78.57%. <br />
(Do check https://github.com/balshersingh10/Diabetes-Onset-Detection-with-SVM-KNN)
## Files included in repository are:
- **source.ipynb(Jupyter Notebook-https://jupyter.org/)**
- **source.pdf(Just a pdf print of jupyter notebook)**
- **diabetes.csv(File that stores Train and Test Data)**  <br />
