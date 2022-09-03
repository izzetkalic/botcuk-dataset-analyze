
[Main Page](../../README.md)

# TQuad Dataset

[TR] Yarışma kapsamında hazırlanan Türkçe soru-cevap [verisetidir](https://github.com/TQuad/turkish-nlp-qa-dataset).

[EN]

# Fine Tuning Metrics

Model         | Phase       | Exact Match |  F1
:-------------|:------------|:-----------:|:------------:
BERTurk       | Train/Eval  | 59.7178     |  79.4480
<br/>         | Test        | 59.4177     |  79.6924
DistilBERTurk | Train/Eval  | 40.2822     |  60.5264
<br/>         | Test        | 39.7634     |  59.0327
ConvBERTurk   | Train/Eval  | 60.8102     |  79.6843
<br/>         | Test        | 60.6005     |  79.3676
ELECTRA Base  | Train/Eval  | <b>61.5385  |  <b>80.3351
<br/>         | Test        | <b>61.2375  |  <b>80.7814

<br/>
<br/>

# Fine Tuning Metrics by Step
<img src="../../placeholders/255_101_58.png" width="5%" /> BERTurk
-~- 
<img src="../../placeholders/197_45_18.png" width="5%" /> DistilBERTurk
-~- 
<img src="../../placeholders/235_45_108.png" width="5%" /> ConvBERTurk
-~- 
<img src="../../placeholders/179_179_179.png" width="5%" />  ELECTRA Base

<span style="color:rgb(255, 101, 58)">BERTurk</span> -~- 
<span style="color:rgb(197, 45, 18)">DistilBERTurk</span> -~- 
<span style="color:rgb(235, 45, 108)">ConvBERTurk</span> -~- 
<span style="color:rgb(179, 179, 179)">ELECTRA Base</span>

Exact Match                |  F1
:-------------------------:|:-------------------------:
<img src="../../images/qa-tquad/tquad_eval_exact_match.svg" width="100%" />  |  <img src="../../images/qa-tquad/tquad_eval_f1.svg" width="100%" />