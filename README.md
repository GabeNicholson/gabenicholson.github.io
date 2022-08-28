### 1. Predicting Covid-19 News Sentiment with Fine-Tuned RoBERTa

- Hand picked 1000 Covid-19 article annotations to train on leading to 94% accuracy on the test set (Over 20% more accurate than BERT).
- The model was than used to predict over 500,000 Covid-19 related articles on AWS Sagemaker.
- Currently being used at the University of Chicago and Dartmouth College (Professor Bruce Sacerdote and his lab).
- The results are that the news is overly negative and that the news publishes much more often when bad things Occur compared to when good events happen. For example, when the Omicron wave was over and Covid cases were plummeting, the news was publishing 6x less articles compared to the week before when it was at its peak. Further, the average news sentiment during the decrease in Omicron cases was still more negative than positive. These findings have important implications for accurate news reporting, namely, that an overly negative news media will mislead readers and may cause an incerase in distrust toward news institutions. 


