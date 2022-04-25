# uni_project_nlp
basic nlp for job ads and classification

there are 3 tasks for this project.

1. basic text preprocessing
- tokenize the texts of job advertisements
- covert all words to lower case
- remove words with length less than 2
- remove stopwords
- remove words only appeared once
- remove 50 most frequent words

2. generating feature representations for job ads
- generate count vector representation
- use pre-trained word2vector (Fast_text, google_news, glove) to generate tf-idf weighted and unweighted document vector for each ad

3. job advertisement classification
- use the above count vector and doc vetors to train a classification model to predict the category of a given job ad.
