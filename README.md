# ML-Web-App-Mushroom-Classification-
This is just an introductory project for deploying Machine Learning Model on web application. 

### About the project:
 Machine Learning model was deployed using the streamlit framework. Streamlit is an open source app framework for machine learning and data science. For machine learning part, mushroom dataset has been classified into edible or poisonous categories. 
Support Vector Machine, Logistic Regression, Random Forest have been used for classification.
A user can choose different hyper-parameters for training the model and effect of different hyper-parameters can then be observed. 


### Dataset:
Mushroom dataset has been used for building Machine Learning classification model.
https://archive.ics.uci.edu/ml/datasets/Mushroom

#### Requirements for running this project:
1. Streamlit must be installed. This can be done by typing pip install streamlit in terminal.
2. Certain functions like plot_confusion_matrix are available only in scikit-learn version 0.22 and above. So make sure that the appropriate scikit-learn version is installed. This can be done using conda install scikit-learn=0.22
3. All other basic requirements for ML hold, like installation of numpy and pandas etc.

To run this simply clone the project and type streamlit run app.py in terminal. 
