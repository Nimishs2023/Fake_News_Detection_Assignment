# Fake_News_Detection_Assignment

## ** Overview **
This repository holds the solution for the Fake News Detection assignment. The project tries to figure out if news articles are true or fake using machine learning. It uses 44,919 articles (21,417 true, 23,523 fake) with steps like cleaning text, turning words into numbers with Word2Vec, and testing three models (Logistic Regression, Decision Tree, Random Forest). The Random Forest model did the best result with an F1-score of 0.898.
## ** Repository Contents: **
1.	**Fake_News_Detection.ipynb**: Python Notebook with all the code, like preparing data, cleaning text, exploring data, making features, training models, and checking results.
2.	**Fake News Detection Assignment Report.pdf**: Report with graphs, analysis, results, insights, and what was learned.
3.	**Fake News Detection Assignment Nimish Mohan S.zip**: Zip file with the notebook and report, as neededfor submission. ## Dependencies To run the notebook, these Python libraries are needed: - pandas - numpy - nltk - spacy (needs `en_core_web_sm` model) - scikit-learn - gensim - seaborn - matplotlib
## ** Assumptions : **
* A pre-trained Word2Vec model was used to turn text into numbers. The assumption was that it would work good for news articles because it’s trained on lots of text, but there wasn’t full certainty.
* 21 articles with missing titles or text were dropped. The assumption was that removing so few out of 44,940 wouldn’t impact the results.
* Articles shorter than 10 characters were checked and assumed to be not useful. None were found, so it seemed fine.
