# Myers-Briggs Type Indicator (MBTI) Machine Learning Classification from Social Media 
The Random Forest, Support Vector Machine, and a CNN and LSTM hyrbrid model's performances in predicting an indivduals MBTI personality type from their  textual social media posts are investigated. Metrics such as F1-score and Balanced accuracy are are evaluated.
## Running Instructions
1. Download the Kaggle (MBTI) Myers-Briggs Personality Type Dataset from: https://www.kaggle.com/datasets/datasnaek/mbti-type.
2. Upload the dataset to Google Drive.
3. For each IPYNB file click the 'Open in Colab' option appearing at the start of each notebook.
4. Once redirected to Google Colab, click the 'Runtime' option and change the runtime to a GPU. This improves the running the times of each notebook.
## The following files are contained within this project:
1. Data_visualization.ipynb which contains graphical information of the dataset. 
2. Random_Forest.ipynb which contains the implementation of the Random Forest Classifier algorithm.
3. SVM_FINAL.ipynb which contains the implementation of the Support Vector Machine algorithm.
4. CNN_LSTM.ipynb which contains the implementation of the CNN and LSTM hybrid algorithm.
## Instruction to run the code for different testing conditions:
### MBTI type mentions removed or present within all files:
Within the ‘preprocessing’ section of each IPYNB file there is a comment indicating whether or not MBTI type mentions should be removed from posts. Below the comment is the code for this specification. Commenting this line will keep MBTI type mentions present and uncommenting it will remove them.
### Sampling the imbalanced data: 
Within the ‘sampling to deal with imbalanced data’ section in each IPYNB file, there are comments indicating the type of sampling technique and whether to perform sampling on the train set only or on the test set as well. The succeeding lines of code can be uncommented depending on the desired method.

## Hyperparameter tuning within the Random_Forest.ipynb and SVM_FINAL.ipynb
- GridSearchCV can be performed by uncommenting the code within the 'Hyperparamter Tuning using Grid Search and Cross Validation' section of each IPYNB file. This is time-consuming and thus commented out once the optimal parameters are found. 
- The optimal parameters for each MBTI dichotomy are specified for each algorithm in the IPYNB files. 

## Collaboration 
This investigation was completed by Jamie Benater (https://github.com/jamiebenater) and Michael Goldman (https://github.com/Mikeygoldman1).

