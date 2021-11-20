# Hotel Reviews Final Report

## Abstract
Having reviews is very valuable for both the guest and the hotel owner. For the potential guest, it’s a valuable resource during the search for a stay. For the hotelier, it’s a way to increase visibility and improve customer contact, which benefits the guests as well. Moreover, it can be useful in building recommendation systems.
So, in this project we used the **Hotel Reviews Data**. Our observation is a customer's review which is represented by a textual feedback of the customer's experience a hotel.

## Data Description
- In this project we choose the [Hotel Reviews Dataset](https://github.com/RaihanAk/Hotel-Review-Sentiment-Analysis_MachineLearning)
- This dataset contains **38933** documents and **5** terms.<br/>

## Preprocessing
We clean the text from puncutation, numbers, stop-words, empty-tokens, and words with one letter. Moreover, we found some reviews in languages other
than English, so we deleted these languages. Also, there were some reviews in which letters are too repeated in some words, which makes these words meaningless, so we deleted them as well.

## Algorithms
### Topic Modeling
Four models have been applied to try to create topics in reviews, which are: **LSA**, **NMF**, **LDA**, and **CorEx**. **NMF** was model with best topics results.
So, our generated topics are: **Procedures**, **Parking**, **General Atmosphere**, **Room Facilities**, and **Resort Hotel**.
### Models Evaluation and Selection
After making the topics our new target, we have been evaluate the data over 5 models, which are: __Logistic Regression__ , __Random Forest Classifier__, __Bernoulli NB__, __Multinomial NB__,
and __Gaussian NB__.
Accordingly, we choose __Random Forest Classifier__ because it has the greatest accuracy score.
#### Training
__Score__: 1.00<br/>
#### Testing
__Score__:  0.9823<br/>

## Tools
Here the basic tools we used in our project: <br/>
Technologies: python, and Jupyter Notebook with python libraries:
- pandas
- matplotlib
- numpy
- seaborn
- scikit-learn
- nltk
- spacy
- itertools
- scattertext

## Communication
The provided slides.

## Conclusion
We aim to improve hotel reviews, by helping hotels in finding the most common services and facilities that satisfied people to keep working on. In other side, finding also what make
customers unsatisfied to improve it. By using NLP as a part of machine learning.
