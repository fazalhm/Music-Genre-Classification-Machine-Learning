# Music-Genre-Classification

## Description:
The task of the project is classify the music genre, when given some metadata about a song. The provided dataset contains about 8111 songs, where the first column contains the genre of the song and the remaining 237 columns contain a mixture of song metadata information
extracted from the audio file itself. 

Dataset link: https://github.com/mdeff/fma.

## Solution: 
To tackle the task, machine learning techniques are used. Principal component analysis (PCA) is used for dimension reductionality since the dataset contains 237 features, the features are reduced to 70 number of components. The project also used different types of classifiers such as Random Forest, Decision Tree, K-Nearest-Neighbor, Multi Layer Preceptron (MLP), Support Vector Classification (SVC) and Naive Bayes (GaussianNB). The project uses cross-validation (K-Fold) for determining the accuracy and grid search for parameter tuning, with classification report and confusion matrix as metrics for analysis. 

The accuracies for Random Forest, Decision Tree, K-Nearest-Neighbor, Multi Layer Preceptron (MLP), Support Vector Classification (SVC) and Naive Bayes (GaussianNB) are 70%, 57%, 69%, 76%, 76% and 53% respectively.
