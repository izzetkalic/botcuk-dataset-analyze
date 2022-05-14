
[Main Page](../../README.md)

# YTU Dataset

[TR] [Prof.Dr. Banu DİRİ](https://avesis.yildiz.edu.tr/diri) tarafından hazırlanan soru-cevap verisetidir. İlgili verisetine ulaşmak için kendisi ile iletişime geçiniz.

[EN] 

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

<span style="color:rgb(0, 108, 179)">BERTurk</span> -~- 
<span style="color:rgb(45, 179, 235)">DistilBERTurk</span> -~- 
<span style="color:rgb(255, 101, 58)">ConvBERTurk</span> -~- 
<span style="color:rgb(5, 142, 125)">ELECTRA Base</span>

Exact Match                |  F1
:-------------------------:|:-------------------------:
<img src="../../images/qa-itu/itu_eval_exact_match.svg" width="100%" />  |  <img src="../../images/qa-itu/itu_eval_f1.svg" width="100%" />