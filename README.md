# Fake-News-Detection-using-Python-and-Machine-Learning
I created a .csv file in Excel, imported it into Jupyter Notebook using pandas, numpy, and scikit-learn libraries. Then split it into training and testing sets, ensuring data separation. I initialised a PassiveAggressiveClassifier, fitted it on the training data, and predicted on the test set using TfidfVectorizer. The model achieved 100% accuracy.

The initiative of this project is to detect fake news. Since this is the era of fast spreading information, fake news has been a new technique to hoax people. I tried detecting fake news with the help of python and machine learning in this project. I have chosen this project because nowadays fake news are spreading as if they are the real ones through social media and through other platforms, it creates a lot of confusion and thus it disturbs the communal harmony among living beings. Introducing Python and machine learning in our day to day life to solve such problems will indulge more people into this field and thus it will help our country in STEM fields which is SCIENCE, TECHNOLOGY, ENGINEERING and MATHEMATICS. 
WHAT IS Tf-idfVectorizer ?						
TF-idf stands for term frequency inverse document frequency; it allows content creators to create their content so that it will rank very very well in Google or in other search browsers.
 TF-idf has two parts, the first part is the TF part which stands for term frequency and the second part is the idf portion or inverse document frequency.
						
The first portion, that is, the term frequency, what it does is, It largely counts the number of times a given word or a phrase appears in an article.
 For example when we search something in Google it takes the certain words that we are searching for and tf-idf analyses what really we are searching for and what search result will be relevant for the user.
						
Why is it important?						
It is important because tf-idf is generally used by content creators so that they can make sure that whatever they are writing or their making content of, they are surely answering the question of their users which is the top tier priority.
 Suppose when someone is writing an article they might think subjectively that a certain word is not really important for that article but other articles are writing that particular word and Google has deemed that word to be relevant and important for that article, so tf-idf provides us with those words and it makes our article more relevant and useful for the users. 


What is idf?
The second portion idf, The inverse document frequency, what it does is, it de values words that happen too many times (There are words like ‘the’, ‘like’ and other words which actually kind of divert the viewer’s mind from the subject, the idf portion flips that and that is what it actually does.). All this is really valuable when we examine certain articles which have specific value for certain words. 

What is a Passive Aggressive Classifier?


We use it when we have a big stream of data.Passive Aggressive Classifier is an online learning algorithm(a method of machine learning in which data becomes available in a sequential order) . In this algorithm, the algorithm is correct for a classification which is correct and in case of a miscalculation event it turns aggressive. It is generally a memory which learns from an example and then throws it away. We use it for detecting fake news or sensationalism because if the news is real then it responds passively and acts aggressively if the news is fake. It makes changes in the parameter only when it's necessary and removes all the updates that don’t upset the balance and therefore it is used for detecting fake news. 
