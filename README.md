# Audio Classification (Indoors/Outdoors) using SVM Model
This project aims to classify audio files recorded at different locations in London as indoors or outdoors using a Support Vector Machine (SVM) model. The SVM model is a popular supervised learning algorithm used for classification and regression analysis. Hyperparameter tuning is applied to optimize the SVM model, achieving an accuracy of 76%.

## Dataset:
The dataset used in this project consists of audio files recorded at various locations in London. The audio files are labeled as indoors or outdoors based on the location where they were recorded.

## Methodology:
The methodology used in this project consists of the following steps:
1. Data preprocessing: The audio files are preprocessed to extract relevant features such as MFCC, Spectral Centroid, and Zero Crossing Rate.
2. Feature engineering: The extracted features are used to create a feature vector for each audio file.
3. Model Fitting and Hyperparameter Tunning: The SVM model is trained using the feature vectors of the audio files to classify them as indoors or outdoors.
Hyperparameter tuning: The hyperparameters of the SVM model are optimized using grid search cross-validation to improve the model's accuracy.
