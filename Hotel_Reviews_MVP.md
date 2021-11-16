# Hotel Reviews MVP
## Objective
In this project we used a Hotel Reviews Data. Our observation is a customer's review which is represented by a textual feedback of the customer's experience a hotel.
## Preprocessing
- - In this project we choose the [Hotel Reviews Dataset](https://github.com/RaihanAk/Hotel-Review-Sentiment-Analysis_MachineLearning)
- This dataset contains **38933** documents and **5** terms.
- Perform Preprocessing: <br/>
  - Cleaning text using nlp features.
  - Visualization.
## Findings
After tokenizing the text, we found that there is more than one language, and we kept English language only. Then, also we found a lot of repeated letters in words, and we tried to remove most of them.
Also, after removing stop words we try to visualize the most frequent words in the reviews, and we found a lot of unmeaningful word. As a result, we dropped them.
<img src = 'https://github.com/emanalshehrii/Hotel_Reviews_NLP/blob/main/images/Count_freq.png' />
As shown above, there are unmeaningful frequent words, such as **room**, **hotel**, **get**, **stay**, **would**, **one**, **bed**, **night**, **us**, **go**, and we dropped them. Which may help us to improve our results.
<br/><br>
As a next step, we will build our topics using different model, such as **NMF**, **LSA**, and **LDA**.
