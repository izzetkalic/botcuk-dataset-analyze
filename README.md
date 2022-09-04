*[English](README.md), [Türkçe](README.tr.md)*


> The results and datasets are a part of my dissertation. It will be published soon.
# BERTurk Performance Analysis on Text Classification and Question Answering Tasks in Turkish Datasets

The datasets that are used in this project were trained in order to be used in text classification and question answering tasks by using the [BERTurk](https://github.com/stefan-it/turkish-bert) model and [Colab](https://colab.research.google.com/) platform. The obtained results are published in this repository.

The datasets were cleaned and standardized and divided into training (70%), validation (20%), and testing (10%). In addition, the character and word counts of each input were calculated to be used in visual analysis, and the elements of the sentence were extracted with the [Zemberek](https://github.com/ahmetaa/zemberek-nlp) tool and included in the datasets.

You can find all fine-tuned models on [Huggingface](https://huggingface.co/Izzet).

## Question Detection Datasets

Dataset                                          | Best Model    | Accuracy    |  Precision   | Recall      | F1       
:------------------------------------------------|:--------------|:-----------:|:------------:|:-----------:|:--------:
[Dialog Dataset](datasets/qd-dialog/README.md)   | ConvBERTurk   | 0.958773    |  0.951311    | 0.892570    | 0.921005
[Quora Dataset](datasets/qd-quora/README.md)     | ELECTRA Base  | 0.959178    |  0.952355    | 0.893072    | 0.921762
[Tweet Dataset](datasets/qd-tweet/README.md)     | ELECTRA Base  | 0.788375    |  0.790655    | 0.788375    | 0.787725


## Question Answering Datasets

Dataset                                        | Best Model    | Accuracy    |  Precision   
:----------------------------------------------|:--------------|:-----------:|:------------:
[TQuad Dataset](datasets/qa-tquad/README.md)   | ELECTRA Base  | 61.5385     | 80.3351
[YTU Dataset](datasets/qa-ytu/README.md)       | ELECTRA Base  | 65.0746     | 82.9919 
