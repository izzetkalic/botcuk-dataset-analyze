
[Main Page](../../README.md)

# YTU Dataset

[TR] [Prof.Dr. Banu DİRİ](https://avesis.yildiz.edu.tr/diri) tarafından hazırlanan soru-cevap verisetidir. İlgili verisetine ulaşmak için kendisi ile iletişime geçiniz.

[EN] It is a question-answer dataset prepared by [Prof.Dr. Banu DİRİ](https://avesis.yildiz.edu.tr/diri). Please contact her to access the dataset.

# Fine Tuning Metrics

Model         | Phase       | Exact Match |  F1
:-------------|:------------|:-----------:|:------------:
BERTurk       | Train/Eval  | 62.5871     |  81.8977
<br/>         | Test        | 56.2624     |  76.7202
DistilBERTurk | Train/Eval  | 30.1493     |  51.1165
<br/>         | Test        | 29.8211     |  48.2728
ConvBERTurk   | Train/Eval  | 65.6716     |  82.427
<br/>         | Test        | <b>62.0278  |  <b>79.8566
ELECTRA Base  | Train/Eval  | <b>65.0746  |  <b>82.9919
<br/>         | Test        | 60.0398     |  77.9323

<br/>
<br/>

# Fine Tuning Metrics by Step

<img src="../../placeholders/0_108_179.png" width="5%" /> BERTurk
-~- 
<img src="../../placeholders/45_179_235.png" width="5%" /> DistilBERTurk
-~- 
<img src="../../placeholders/255_101_58.png" width="5%" /> ConvBERTurk
-~- 
<img src="../../placeholders/5_142_125.png" width="5%" />  ELECTRA Base

Exact Match                |  F1
:-------------------------:|:-------------------------:
<img src="../../images/qa-itu/itu_eval_exact_match.svg" width="100%" />  |  <img src="../../images/qa-itu/itu_eval_f1.svg" width="100%" />