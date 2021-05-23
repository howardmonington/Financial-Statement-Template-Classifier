# Financial Statement Template Classifier

#### -- Project Status: Completed

## Project Intro/Objective
Financial statements can be divided into two different kinds of templates: Industrial and Financial. Industrial companies produce products and their accounting practices tend to reflect the revenue and expenses involved in production/sales business activities. Financial companies produce financial services and their accounting practices tend to reflect the revenue and expenses involved in financial service/sales business activities. In this project, I use artificial intelligence to classify companies as Industrial (indu) or Financial (fin) based on their usage of XBRL concepts in SEC 10-K/10-Q filings.

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
Although both supervised and reinforcement learning use mapping between input and output, reinforcement learning uses rewards and punishments as signals for positive and negative behavior. In this project, the RL model received a reward for keeping the shower temperature within the desired range (between 87 to 93 degrees fahrenheit) and a negative reward if it is not within the desired range. The shower length is 60 seconds, and every second the temperature can fluctuate by 1 degree upwards or downwards. The model has an action space composed of 5 actions. Every second, it can change the temperature by: (-2, -1, 0, 1, 2). I ended up building a Sequential model and using a DQNAgent, which is a value-based reinforcement learning agent that trains a critic to estimate the return or future rewards.


## Featured Notebooks/Analysis/Deliverables
* [Notebook](https://github.com/lukemonington/shower_temp_reinforcement_learning/blob/main/Shower%20Temperature%20Reinforcement%20Learning.ipynb)


## Contributing Members

**[Luke Monington](https://github.com/lukemonington)**

## Contact
* I can be reached at lukemonington@aol.com.
