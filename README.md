# Fake_News_Detection_Assignment

## Overview
This repository is for the Fake News Detection assignment. The project checks if news articles are true or fake using machine learning. It uses a dataset of 44,919 articles (21,417 true and 23,523 fake). The process includes cleaning text, converting words to numbers with Word2Vec, and testing three models (Logistic Regression, Decision Tree, Random Forest). The Random Forest model gave the best result with an F1-score of 0.898.

## Repository Contents
1. **Fake_News_Detection.ipynb**: Python notebook with all the steps like preparing data, cleaning text, exploring data, making features, training models, and checking results.
2. **Fake News Detection Assignment Report.pdf**: Report with graphs, analysis, results, insights, and learnings.
3. **Fake News Detection Assignment Nimish Mohan S.zip**: Zip file containing the notebook and report for submission.

## Dependencies
To run the notebook, these Python libraries are needed - pandas, numpy, nltk, spacy (requires the `en_core_web_sm` model), scikit-learn, genism, seaborn, matplotlib

## Assumptions
- A pre-trained "Word2Vec" model was used to convert text into numbers. It was assumed to work well for news articles because it has trained on lots of text, but this wasn’t fully confirmed.
- 21 articles with missing titles or text were removed. Since this is a very small number compared to the total dataset (44,940), it was considered fine.
- Articles shorter than 10 characters were seen as not useful. None were found, so this didn’t affect anything.
