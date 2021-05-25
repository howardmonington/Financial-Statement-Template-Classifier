# Financial Statement Template Classifier

#### -- Project Status: Completed

## Project Intro/Objective
Financial statements can be divided into two different kinds of templates: Industrial and Financial. In this project, I use artificial intelligence to classify companies as Industrial (indu) or Financial (fin) based on their usage of XBRL concepts in SEC 10-K/10-Q filings. 

### Methods Used
* Natural Language Processing
* Machine Learning
* Deep Learning


### Technologies
* Python
* Pandas, jupyter
* TensorFlow, Keras
* RandomizedSearchCV
* scikit-learn
* Tokenizer

## Project Description
The accounting treatment of Industrial companies is different from Financial companies. Industrial companies produce products and their accounting practices tend to reflect the revenue and expenses involved in production/sales business activities. Financial companies produce financial services and their accounting practices tend to reflect the revenue and expenses involved in financial service/sales business activities. My goal in this project is to use artificial intelligence to classify the financial statements based on their XBRL tags with 100% accuracy. First, I attempt a tokenizer with a machine learning algorithm and I tune the hyperparameters. However, I am only able to get up to 98% accuracy. Then, I build a neural network and am able to achieve 100% accuracy. After this, I investigate another method of feature engineering where I use a count vectorization instead of a tokenizer and am able to achieve 100% accuracy with just a Naive Bayes model.


## Featured Notebooks/Analysis/Deliverables
* [Notebook](https://github.com/lukemonington/financial-statement-classifier/blob/main/main_ai.ipynb)
* [Project Writeup](https://github.com/lukemonington/financial-statement-classifier/blob/main/Write%20Up%20on%20My%20Approach.docx)


## Contributing Members

**[Luke Monington](https://github.com/lukemonington)**

## Contact
* I can be reached at lukemonington@aol.com.
