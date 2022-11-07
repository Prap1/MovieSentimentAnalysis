# MovieSentimentAnalysis
Movie Sentiment Analysis
 
Project description
Movie reviews sentiment analysis is a project which is based on natural language processing, where we use NLP techniques to extract useful words of each review and based on these words we can use binary classification to predict the movie sentiment if it's positive or negative.
Prerequisites
This is list of required packages and modules for the project to be installed :
•	Python
•	Pandas
•	Numpy
•	re
•	Scikit-learn
•	Keras
•	NLTK
The Dataset
This dataset contain about 50000 record which is a sample of movie's review
and a target column "sentiment" which describe the sentiment of the viewer about the movie either it is positive or negative,
 

Coding Sections
In this part we divide project code to sections as follows:
•	Section 1 | Data Preprocessing  and Vizualization:
In this section we aim to do some operations on the dataset before training the model on it,
processes like :
	Loading the dataset
	Encoding ouput to binary (Positive : 1 , Negative : 0)
	Visualize the data
	Data cleaning : Remove HTML tags
	Data cleaning : Remove special characters

•	Section 2 | Model Creation :
The dataset is ready for training, so we create a five model(GaussianNB, MultinomialNB, BernouliNB, Simple Neural Network, CNN)  then fit it to the data.
•	Section 3 | Model Evaluation :
Finally we evaluate the model by getting accuracy

Output
•	Visualization sample
 
•	Review sample after applying the preprocessing 
 
•	Model Accuracy
 
References
These links may help you to better understanding of the project idea and techniques used :
1.	Natural Language Processing (NLP) : https://ibm.co/38bN03T
2.	Sentiment analysis : https://bit.ly/3yi9BGq
3.	Naive Bayes classifier : https://bit.ly/3zhoWIO
4.	Model evaluation : https://bit.ly/3B12VOO




