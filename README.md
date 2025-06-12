# Instagram_Data_Science

Bu proje, Kaggle'dan alınan "Top Instagram Influencers Data (Cleaned)" veri seti üzerinden Instagram influencer’larının performansını analiz etmeyi amaçlıyor.

## 🎯 Hedefler

- Takipçi sayısı, kategori ve ülke gibi faktörlerin etkileşim oranına etkisini incelemek
- Etkileşim oranına göre influencer’ları gruplandırmak
- Basit bir modelle hangi özelliklerin etkileşimi en çok etkilediğini yorumlamak

## 🧩 Veri

- **Veri kaynağı:** Kaggle – "Top Instagram Influencers Data (Cleaned)" :contentReference[oaicite:4]{index=4}
- Filtreleme veya temizleme öncesi raw CSV’in `data/` klasöründe saklanması önerilir

## 🧰 Teknolojiler

- Python: pandas, seaborn, matplotlib, scikit-learn
- Jupyter Notebook

## 📁 Proje Yapısı

Instagram_Data_Science/
├── data/ # Raw dataset: top_influencers.csv
├── notebooks/
│ ├── 01_data_cleaning.ipynb # Veri temizleme & ön analiz
│ ├── 02_eda.ipynb # EDA görselleştirmeleri
│ ├── 03_modeling.ipynb # Basit modelleme
├── src/
│ ├── data_loader.py
│ └── utils.py
├── results/
│ ├── figures/
│ └── model_summary.csv
├── requirements.txt
└── README.md
