First thing we upload the data, we add the tokens we want and then run it and then it will divide the tokens depend on the corpes that has been learned on it, it will be LOC, PER, and ORG tags, XTREME has 183 configurations that been show.
langs = ["ar", "fr", "it", "en"]
fracs = [0.629, 0.229, 0.084, 0.059]
Line 2 and 3, are the languges that was been selected to be, and then it will show how many are the traing of all of them, and then train the features.
The code have 7 classes, it will appear the test sit and the train sit.
The code uses BERT and XLM-R models to transform.
XLM-R: is a multilingual version of RoBERTa. It is pre-trained on 2.5TB of filtered CommonCrawl data containing 100 languages.
BERT: stands for Bidirectional Encoder Representations from Transformers and is a language representation model by Google. It uses two steps, pre-training and fine-tuning, to create state-of-the-art models for a wide range of tasks.
