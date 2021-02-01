## Unlabelled Tweet analysis 


### 1. Objectives
To use content analysis of tweets to identify the community sentiment towards RA’s (or any other diseases) drug therapies. Secondly, to study and unravel thematic clusters and topics related to these sentiments, and identify the factors that may affect patients to persist with some therapies and not others. Lastly, due to the nature of the unlabeled state and large volume of tweets, the set-up process with a use of manual annotation is impractical and expensive. The proposed framework is to find for the balance of this trade-off and efficient and effective analysis. 
 
### 2. Methods

Combined sentiment and thematic analysis in a sequential way is proposed and used to provide effective community perception analysis as follows. 

![alt text](https://github.com/wee3434/unlabelled-twitter-analysis/blob/master/Image/proposedFramework.png)
 
 
Below framework is proposed to perform sentiment analysis with the least manual annotation on un-labelled dataset while combining the benefits of lexicon and machine-learning based approaches. To overcome biasness and attain better quality performance, I added 10% of manual annotated data. The best performing machine learning model can be different by dataset and chosen by comparison. Here, I fitted and compared CNN, SVM, NB and logistic regression. 

![alt text](https://github.com/wee3434/unlabelled-twitter-analysis/blob/master/Image/sentimentAnalysis.png)