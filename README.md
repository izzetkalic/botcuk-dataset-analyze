*[English](README.md), [Türkçe](README.tr.md)*

# BERTurk Performance Analysis on Text Classification and Question Answering Tasks in Turkish Datasets



## Question Detection Datasets

Dataset                                          | Best Model    | Accuracy    |  Precision   | Recall      | F1       
:------------------------------------------------|:--------------|:-----------:|:------------:|:-----------:|:--------:
[Dialog Veriseti](datasets/qd-dialog/README.md)  | ConvBERTurk   | 0.958773    |  0.951311    | 0.892570    | 0.921005
[Quora Veriseti](datasets/qd-quora/README.md)    | ELECTRA Base  | 0.959178    |  0.952355    | 0.893072    | 0.921762
[Tweet Veriseti](datasets/qd-tweet/README.md)    | ELECTRA Base  | 0.788375    |  0.790655    | 0.788375    | 0.787725


## Question Answering Datasets

Dataset                                        | Best Model    | Accuracy    |  Precision   
:----------------------------------------------|:--------------|:-----------:|:------------:
[TQuad Veriseti](datasets/qa-tquad/README.md)  | ELECTRA Base  | 61.5385     | 80.3351
[ITU Veriseti](datasets/qa-itu/README.md)      | ELECTRA Base  | 65.0746     | 82.9919 
