SPAM EMAIL DETECTION
The goal of this project is to build a model that is able to classify an email as spam or not spam by analyzing various words, characters, and their related frequencies 


The following steps will be taken:

Loading the data from where it has been stored
Understanding the data, it's features and observation
Checking the information contained in the data
Exploring and Visualizing the data - checking for inconsistencies, distribution of features and patterns in the data
Cleaning the data
Analyzing the data
Preprocessing the data
Building a model

If after replacing spurious values from the obsevations with nan the features do not automatically change to float type run the following code to manually change the affected features to float type![Screenshot (2)](https://github.com/user-attachments/assets/4da65e98-2cff-4915-9cc2-77d6d286e663)
:

feat= data[['word_freq_our', 'word_freq_000', 'word_freq_hpl', 'word_freq_labs']]

for col in feat:
    data[col]= data[col].astype(float)
