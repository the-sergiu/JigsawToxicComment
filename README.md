# Jigsaw Multilingual Toxic Comment Classification Kaggle Competition

## Link to Competition/Dataset
https://www.kaggle.com/c/jigsaw-multilingual-toxic-comment-classification/overview

## Description
The focus is on machine learning models that can identify toxicity in online conversations, where toxicity is defined as anything rude, disrespectful or otherwise likely to make someone leave a discussion. If these toxic contributions can be identified, we could have a safer, more collaborative internet.

## Notebook
This notebook represents my approach to the competition dataset.

## Results
The measure of success in this competition was the AUROC score.
I obtained a AUROC score of 72%, which I am happy with, having worked only on 10% of the total data, on Google Collab Free.

## Room for improvement

* Fast.ai helps with a pretrained English Language Model when using the language_model_learner. If I had more resources (and perhaps skill), I would construct a language model that can 'understand' all 6 languages from the dataset. Training a language model on current tech can take up to 3 days. 6 languages * 3 days = 18 days of non stop running.
* Obviously, train and test on all of the data, not just 10% (again, more resources would have been necessary).
* Be more wary of possibility of overfitting.