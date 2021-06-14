# nlp.ner.spacy

This Github repository aims to test the NER module of the spaCy framework on tweets about Tesla Company.

- The first notebook `1_reformat_data.ipynb` reformat the data of a dataset with ground truth entities in order to test the performances of the spaCy model.
- The second notebook `2_test_spacy_transformer_ner.ipynb` test the performance of the spaCy model on the ground truth data.
- The third notebook `3_the_guardian_api_pulling.ipynb` allows to pull data from the guardian API on a given topic. (In our case Tesla)
- The last notebook `4_apply_spacy_ner_to_articles.ipynb` applies spaCy NER model on the downloaded data and provide some analysis of the text dataset.

#### Setup:

Before runing the notebook 3 you will need to have a the guardian API key which you will store in the file `config.py` in the following variable :
```
API_KEY="YOUR_SECRECT_KEY"
```

#### requierements:

- spacy==3.0.6
- spacy-alignments==0.8.3
- spacy-legacy==3.0.5
- spacy-transformers==1.0.2
- wordcloud==1.8.1

