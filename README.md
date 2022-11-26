# NLP-NER
A simple NER implementation:
The Repo contains a simple NER implimentation of a labelled dataset. Included the notebook which was ran in google colab envirnoment.

The data is annotated for named entities:

1. Person
2. Location
3. Group
4. Creative work
5. Corporation
6. Product
Possible approaches include, rule based model, training Sequence to sequence model from scratch or use transformers.

Rule based approcahes are not used here as it is exhaustive and maynot always converge to a generalization. The approach used in this experiment is to train a sequence to sequence model using LSTM.As per the size of the data and distributation of classes across the data, this approach promises to be fruitful. Due to lack of computational resources in the local machine, this notebook donot useses any Transformer based approaches.
