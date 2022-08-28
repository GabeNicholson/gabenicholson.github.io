### 1. Predicting Covid-19 News Sentiment with Fine-Tuned RoBERTa

Is the news always negative? Anyone who watched the news in the last two years probably noticed that loom and gloom were always making top headlines, especially given the pandemics heavy toll. However, was the news always negative or did it become more positive when good things occured such as increases in vaccine uptake or decreases in Covid-19 cases? In this project (my UChicago thesis) I used a neural network to predict Covid-19 article sentiment on over 500,000 Covid-19 articles from April 2020 - April 2022. With this data, I then created a time series that compared the Covid-19 positive rate to the average sentiment score across all articles. 

The results are that the news is overly negative and that the news publishes much more often when bad things Occur compared to when good events happen. For example, when the Omicron wave was over and Covid cases were plummeting, the news was publishing 6x less articles compared to the week before when it was at its peak. Further, the average news sentiment during the decrease in Omicron cases was still more negative than positive. These findings have important implications for accurate news reporting, namely, that an overly negative news media will mislead readers and may cause an incerase in distrust toward news institutions. 

- Hand picked 1000 Covid-19 article annotations to train on leading to 94% accuracy on the test set (Over 20% more accurate than BERT).
- The model was than used to predict over 500,000 Covid-19 related articles on AWS Sagemaker.
- Currently being used at the University of Chicago and Dartmouth College (Professor Bruce Sacerdote and his lab).

### 2. Predicting Bike Path Changes While Controlling for Multiple Testing





### 3. Classification in the face of Uneven Test/Training Set Distributions

A major problem in machine learning is when the test set comes from a different distribution than the training set. Even when carefully applying cross-validation to avoid overfitting, a test set that has a different distribution than the training set will lead to an overestimation in model accuracy. We propose a possible solution to this problem by using Conformal prediction and reweighting predictions with weights derived from PCA and KNN. Using unsupervised ML techniques, we can adjust the weights without actually looking at the test set data, thereby avoiding any data dependent decisions. Our approach is highly valueable in real world applications since many machine learning models in industry are completely under the assumption that the predictions they will make in production will resemble that of what they were origianlly trained on. Our method can be used to supplement this assumption by continuing to make the distributions equal. 
