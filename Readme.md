# Sentiment Analysis of Tweets using supervised ML models
Using the [Hate Speech and Offensive Language Dataset](https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset) which is a dataset of detected twitter data, supervised machine learning models are trained. The following workflow was executed during the process.
1. Data Preparation (Data Categorisation and Data Vectorisation).
    Three Categories of Data: 1 - hate speech, 2 - offensive language, 3 - none.
2. Data Processing (With grid search and without grid search).
    The following models were used: Gaussian Naive Bayes, Support Vector Machine (SVM), Artificial Neural Network (ANN), Decision Tree (Entropy based), Decision Tree (Gini Index Based), K-nearest neighbour. Their parameters will be mentioned ahead.
3. Comparison of the ML models.
    The graphs show parameter tuning results and comparison table.

    ![Naive Bayes Accuracy Graph](<NB accuracy graph.png>)
    ![SVM Accuracy Graph](<SVM accuracy.png>)
    ![ANN Accuracy Graph](<ANN Accuracy.png>)
    ![DTentropy Accuracy Graph](<DT Entropy Accuracy.png>) 
    ![DTgini Accuracy Graph](<DT Gini Index Accuracy.png>)
    ![KNN Accuracy Graph](<KNN accuracy.png>)
    Accuracy Comparison Table - 
    ![Accuracy Comparison Table](<AcC_table.jpg>)

This repository acts a submission for major innovative assignment for the course - Machine learning (DSA - 2CS501) while pursuing B.Tech CSE at Nirma University.