# Parkinsons-Disease-Classification
## About
The Machine learning classification model which classifies if the person with given attributes is suffering from parkinson's disease or not which was build using decision tree classifier and random forest classifier.
## About Data set
The data set was obtained from [UCI machine learning repository](https://archive.ics.uci.edu/ml/datasets/Parkinson%27s+Disease+Classification,"UCI repository"). It contains 754 attributes and 756 instances for each attribute. Various speech signal processing algorithms including Time Frequency Features, Mel Frequency Cepstral Coefficients (MFCCs), Wavelet Transform based Features, Vocal Fold Features and TWQT features have been applied to the speech recordings of Parkinson's Disease (PD) patients to extract clinically useful information for PD assessment.

## About ML algorithms used
Two algorithms has been used for building the model, decision tree classifier and Random Forest classifier. Both of the model were compared using various classification evaluation parameters and the model which outperformed other was selected as a final model. Decision tree and Random forest both requires hyperparameters so to choose the best hyperparameters GridSearchCV was used for hyperparameter tuning.

## Steps 
1. loading dataset and creating Dataframe using pandas.
2. Data cleaning and preparation dropping unwanted columns, dealing with duplicates and missing values, scalling of the data, checking if the dataset is imbalanced.
3. spliting the dataset into training and testing set using train_test_split.
4. Building two classifiers using decision tree and Random forest algorithms.
5. hyperparameter tuning using GridSearchCV and choosing best hyperparameters.
6. evaluation of models using classification report and choosing the model with better performance.
