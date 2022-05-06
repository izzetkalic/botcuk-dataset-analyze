
[Main Page](../../README.md)

# Dialog Dataset

[TR] [Qi Jia ve diğerleri](https://github.com/JiaQiSJTU/QAmatching) tarafından yayınlanan bir makale için hazırlanan verisetidir. Çince doktor-hasta diyalog kayıtlarını içeren veriseti [Google Translate API](https://cloud.google.com/translate) yardımıyla Türkçeye çevrilerek kullanılmıştır.

[EN]

# Fine Tuning Metrics

Model         | Phase       | Accuracy    |  Precision   | Recall        | F1
:-------------|:------------|:-----------:|:------------:|:-------------:|:-------:|
BERTurk       | Train/Eval  | 0.957015    |  0.951456    | 0.885542      | <b>0.956515
<br/>         | Test        | 0.961081    |  0.950317    | 0.902610      | 0.925849
DistilBERTurk | Train/Eval  | 0.957556    |  0.947705    | 0.891566      | 0.918779
<br/>         | Test        | 0.962432    |  0.952481    | 0.905622      | 0.928461
ConvBERTurk   | Train/Eval  | <b>0.958773 |  0.951311    | 0.892570      | 0.921005
<br/>         | Test        | <b>0.963243 |  0.956475    | 0.904618      | <b>0.929824
ELECTRA Base  | Train/Eval  | 0.955123    |  0.953057    | 0.876506      | 0.913180
<br/>         | Test        | 0.958378    |  0.942226    | 0.900602      | 0.920944

<br/>
<br/>

# Fine Tuning Metrics by Step

<span style="color:rgb(255, 101, 58)">BERTurk</span> -~- 
<span style="color:rgb(44, 174, 228)">DistilBERTurk</span> -~- 
<span style="color:rgb(0, 108, 179)">ConvBERTurk</span> -~- 
<span style="color:rgb(179, 179, 179)">ELECTRA Base</span>

Accuracy                   |  F1
:-------------------------:|:-------------------------:
<img src="../../images/qd-dialog/dialog_eval_accuracy.svg" width="100%" />  |  <img src="../../images/qd-dialog/dialog_eval_f1.svg" width="100%" />

Precision                  |  Recall
:-------------------------:|:-------------------------:
<img src="../../images/qd-dialog/dialog_eval_precision.svg" width="100%" />  |  <img src="../../images/qd-dialog/dialog_eval_recall.svg" width="100%" />