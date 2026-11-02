
AMAZON PRODUCT REVIEW SENTIMENT ANALYSIS
========================================

DATASET
-------
Amazon Reviews 2023 - All Beauty
Original Reviews: 701,528
Experiment Samples: 30,000

DATA SPLIT
----------
Training: 24,000
Validation: 3,000
Testing: 3,000

SENTIMENT LABELS
----------------
0 = Negative
1 = Neutral
2 = Positive

MODELS
------
1. Bidirectional LSTM
2. BERT Base Uncased (HuggingFace)

EXPERIMENTAL RESULTS
--------------------
LSTM Accuracy: 85.57%
BERT Accuracy: 90.70%

LSTM Macro F1: 0.7211
BERT Macro F1: 0.7867

TRAINING TIME
-------------
LSTM: 0.36 minutes
BERT: 19.16 minutes

MODEL SIZE
----------
LSTM: 15.51 MB
BERT: 418.35 MB

PROJECT OBJECTIVE
-----------------
Three-class sentiment classification of Amazon
product reviews using LSTM and fine-tuned BERT.

IMPORTANT
---------
Sentiment labels are generated from star ratings.
These labels may not perfectly represent the actual
emotional meaning of every review.
