# Hearthstone Mana Tahmin Modeli

Bu proje, **Hearthstone** kartlarının istatistiksel özellikleri ve kart metinlerinden elde edilen gömlemeleri (embeddings) kullanarak **mana değerini** amaçlayan bir makine öğrenimi çalışmasıdır.

## Proje Özeti

Model, kartların saldırı (Attack), can (Health), tür (Type), nadirlik (Rarity), mekanik özellikler (Mechanics) ve metin açıklamaları gibi değişkenlerden yararlanarak tahmin yapar.  
Amaç, oyun tasarımındaki denge unsurlarını sayısal olarak incelemek ve kart maliyetlerinin tutarlılığını değerlendirmektir.

## Kullanılan Yöntemler ve Teknolojiler

- Python 3
- scikit-learn 
- optuna (hyperparameter tunning)
- matplotlib, seaborn 

- SentenceTransformers (kart metinlerinden embedding çıkarımı)

## Sonuçlar

- Model doğruluk metriği (R²): **0.75**

