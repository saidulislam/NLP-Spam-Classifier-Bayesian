## Mission<br/>
Spam detection is one of the major applications of Machine Learning in the interwebs today. Pretty much all of the major email service providers have spam detection systems built in and automatically classify such mail as 'Junk Mail'.<br/>
<br/>
In this mission we will be using the Naive Bayes algorithm to create a model that can classify SMS messages as spam or not spam, based on the training we give to the model. It is important to have some level of intuition as to what a spammy text message might look like. Often they have words like 'free', 'win', 'winner', 'cash', 'prize' and the like in them as these texts are designed to catch your eye and in some sense tempt you to open them. Also, spam messages tend to have words written in all capitals and also tend to use a lot of exclamation marks. To the human recipient, it is usually pretty straightforward to identify a spam text and our objective here is to train a model to do that for us!<br/>
<br/>
Being able to identify spam messages is a binary classification problem as messages are classified as either 'Spam' or 'Not Spam' and nothing else. Also, this is a supervised learning problem, as we will be feeding a labelled dataset into the model, that it can learn from, to make future predictions.<br/>


## Overview<br/>
This project has been broken down in to the following steps:

<br/>
- Step 0: Introduction to the Naive Bayes Theorem<br/>
- Step 1.1: Understanding our dataset<br/>
- Step 1.2: Data Preprocessing<br/>
- Step 2.1: Bag of Words (BoW)<br/>
- Step 2.2: Implementing BoW from scratch<br/>
- Step 2.3: Implementing Bag of Words in scikit-learn<br/>
- Step 3.1: Training and testing sets<br/>
- Step 3.2: Applying Bag of Words processing to our dataset.<br/>
- Step 4.1: Bayes Theorem implementation from scratch<br/>
- Step 4.2: Naive Bayes implementation from scratch<br/>
- Step 5: Naive Bayes implementation using scikit-learn<br/>
- Step 6: Evaluating our model<br/>
- Step 7: Conclusion<br/>
