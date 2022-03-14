# Naive-Bayes
Excelr Project

Problem Statement: 1) Prepare a classification model using Naive Bayes for salary data 

Data Description:

age -- age of a person
workclass	-- A work class is a grouping of work 
education	-- Education of an individuals	
maritalstatus -- Marital status of an individulas	
occupation	 -- occupation of an individuals
relationship -- 	
race --  Race of an Individual
sex --  Gender of an Individual
capitalgain --  profit received from the sale of an investment	
capitalloss	-- A decrease in the value of a capital asset
hoursperweek -- number of hours work per week	
native -- Native of an individual
Salary -- salary of an individual



Naïve Bayes algorithm is a supervised learning algorithm, which is based on Bayes theorem and used for solving classification problems.

It is mainly used in text classification that includes a high-dimensional training dataset.

**Naïve Bayes Classifier is one of the simple and most effective Classification algorithms which helps in building the 
fast machine learning models that can make quick predictions.

There are three types of Naive Bayes model under the scikit-learn library:
**Gaussian:** It is used in classification and it assumes that features follow a normal distribution.

**Multinomial:** It is used for discrete counts. For example, let’s say,  we have a text classification problem. 
Here we can consider Bernoulli trials which is one step further and instead of “word occurring in the document”, 
we have “count how often word occurs in the document”, you can think of it as “number of times outcome number x_i is observed over the n trials”.

**Bernoulli:** The binomial model is useful if your feature vectors are binary (i.e. zeros and ones). One application 
would be text classification with ‘bag of words’ model where the 1s & 0s are “word occurs in the document” and “word does not occur in the document” respectively.
