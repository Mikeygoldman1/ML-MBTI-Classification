# Myers-Briggs Type Indicator (MBTI) Machine Learning Classification from Social Media 
The Random Forest, Support Vector Machine, and a CNN and LSTM hyrbrid model's performances in predicting an indivduals MBTI personality type from their  textual social media posts are investigated. Metrics such as F1-score and Balanced accuracy are are evaluated.
## Installations and Running Instructions
- Use pip install tensorflow to install the latest version of TensorFlow. This is required to building the CNN and LSTM hyrbid model. 
- All the IPYNB files can be run 
# The following files are contained within this project:
Data_visualization.ipynb which contains information about and graphical representations of the dataset. 
Random_Forest.ipynb which contains the implementation of the Random Forest Classifier algorithm.
SVM.ipynb which contains the implementation of the Support Vector Machine algorithm.
CNN_LSTM.ipynb which contains the implementation of the CNN and LSTM hybrid algorithm.

# Instruction on how to run the code:
##MBTI type mentions removed or present within all files
Within the ‘preprocessing’ section there is a comment indicating whether or not MBTI type mentions should be removed. Below the comment is the code for this specification. Commenting this line will keep MBTI type mentions present and uncommenting it will remove them.
## Sampling the data within all files
Within the ‘sampling to deal with imbalanced data’ section, there are comments indicating the type of sampling technique and whether to perform sampling on the train set only or on the test set as well. The succeeding lines of code can be uncommented depending on the desired method.

## Hyperparameter tuning within the Random_Forest.ipynb and SVM.ipynb
GridSearchCV can be performed by uncommenting the code within the respective section. This is time-consuming and thus commented out once the optimal parameters are found. 

