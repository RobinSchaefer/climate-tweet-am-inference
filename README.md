# Argument Mining Inference on German Climate Change Tweets

This repo contains AM inference results (ACTC) for the two climate change tweet corpora, I use in my dissertation.

1. the GerCCT corpus
2. the MP tweet corpus

Models for AM inference were trained on an annotated subset of the GerCCT corpus and used to label the remainder of the dataset. Subsequently, the models were applied to the MP corpus to allow for comparison of argument structures in both corpora.

The GerCCT inference results contain further results obtained from two AM pipelines:

1. a 2 step pipeline: ADU classification -> semantic type classification
2. a 3 step pipeline: general argument classification -> ADU classification -> semantic type classification