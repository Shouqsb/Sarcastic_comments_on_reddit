# Sarcastic_comments_on_reddit
## Abstract
The goal of this project is to detect sarcastic comments by analyzing comments that use the sarcasm tag using machine learning models, in order to detect and prevent sarcastic comments. The data used in this project was created by Kaggle, and the data trained Logistic Regression and Naive Bayes from the sklearn package, with the Logistic Regression outperforming the Naive Bayes by 69%.

## Design 
The project is a requirement in T5 Data Scince Bootcamp provided by SDAIA. the main idea of the project is classifying comments if it is sarcastic/non-sarcastic using machine learning algorithms. the data is a comments in Reddit provided by kaggle 

## Data
The dataset will use is **Sarcastic Comments - REDDIT**. 
The dataset found at [Kaggle](https://www.kaggle.com/sherinclaudia/sarcastic-comments-on-reddit).
The dataset contains 1.3 million Sarcastic comments from the Internet commentary website Reddit. The dataset was generated by scraping comments from Reddit containing the (sarcasm) tag. This tag is often used by Redditors to indicate that their comment is in jest and not meant to be taken seriously, and is generally a reliable indicator of sarcastic comment content.


## Algorthim
* Dataset cleaning and removing null values and convert the data types of the featurs using ```pandas```
* Explore the data
* Visualization the data using ```matplotlib.pyplot``` and ```seaborn```
* Apply vectorzition on the dataset using ```TfidfVectorizer```

*Models*
Using Logistic Regression and Naive Bayes to classify the comments if is it sarcastic/non sarcastic
Logistic Regression result:
* Accuracy 0.69
* F1 0.69
* precision 0.69
* recall 0.70

Naive Bayes result:
* Accuracy 0.67
* F1 0.67
* precision 0.67
* recall 0.67


Based on the accuracy the Logistic Regression gives better performance than Naive Bayes

## Tools
* `pandas` for data manipulation
* `sklearn` for modeling
* ```matplotlib, seaborn```  for plotting
* `TfidfVectorizer` to vectorzition

