*[English](README.md), [Türkçe](README.tr.md)*

> Paylaşılan sonuçlar ve verisetleri tezimin bir parçasıdır. Yakında paylaşıma açılacaktır.

# Cümle Sınıflandırma ve Soru Cevaplama Görevleri için BERTTurk Modeli ile Türkçe Verisetleri Üzerinde Performans Analizi

Bu verisetleri [BERTurk](https://github.com/stefan-it/turkish-bert) modeli kullanılarak [Colab](https://colab.research.google.com/) yardımıyla cümle sınıflandırma ve soru cevapları görevinde kullanılmak üzere eğitilmiştir. Elde edilen sonuçlar ve verisetleri bu projede paylaşılmıştır.

Verisetleri temizlenip standartlaştırılarak eğitim (%70), doğrulama (%20) ve test (%10) olarak ayrılmıştır. Ek olarak görsel analizde kullanılmak üzere her bir girdinin karakter ve kelime sayıları hesaplanmış ve [Zemberek](https://github.com/ahmetaa/zemberek-nlp) aracı ile cümlenin öğeleri çıkarılarak verisetlerine dahil edilmiştir.

## Soru Tanıma Verisetleri

Veriseti                                         | En İyi Model  | Accuracy    |  Precision   | Recall      | F1      
:------------------------------------------------|:--------------|:-----------:|:------------:|:-----------:|:--------:
[Dialog Veriseti](datasets/qd-dialog/README.md)  | ConvBERTurk   | 0.958773    |  0.951311    | 0.892570    | 0.921005
[Quora Veriseti](datasets/qd-quora/README.md)    | ELECTRA Base  | 0.959178    |  0.952355    | 0.893072    | 0.921762
[Tweet Veriseti](datasets/qd-tweet/README.md)    | ELECTRA Base  | 0.788375    |  0.790655    | 0.788375    | 0.787725

## Soru Cevaplama Verisetleri

Veriseti                                       | En İyi Model  | Exact Match |  F1        
:----------------------------------------------|:--------------|:-----------:|:----------:
[TQuad Veriseti](datasets/qa-tquad/README.md)  | ELECTRA Base  | 61.5385     | 80.3351
[YTU Veriseti](datasets/qa-ytu/README.md)      | ELECTRA Base  | 65.0746     | 82.9919