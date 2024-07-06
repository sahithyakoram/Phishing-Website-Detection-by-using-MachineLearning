# Phishing Website Detection using Machine Learning Techniques
**Objective**:
A phishing website is a common social engineering method that mimics trustful uniform resource locators (URLs) and webpages. The objective of this project is to train machine learning models and deep neural nets on the dataset created to predict phishing websites. The performance level of each model is measured and compared.

# Feature Extraction
The below mentioned category of features are extracted from the URL data:

1. Address Bar based Features
          In this category 9 features are extracted.
2. Domain based Features
          In this category 4 features are extracted.
3. HTML & Javascript based Features
          In this category 4 features are extracted.

 # Models & Training
 Before stating the ML model training, the data is split into 80-20 i.e., 8000 training samples & 2000 testing samples. From the dataset, it is clear that this is a supervised machine learning task. There are two major types of supervised machine learning problems, called classification and regression.
 This data set comes under classification problem, as the input URL is classified as phishing (1) or legitimate (0). The supervised machine learning models (classification) considered to train the dataset in this project are:
1. Decision Tree
2. Random Forest
3. Multilayer Perceptrons
4. XGBoost
5. Support Vector Machines
