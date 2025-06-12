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

## 📁 Project Structure

```
Instagram_Data_Science/
├── data/
│   ├── top_instagram_influencers.csv
│   └── cleaned_influencers.csv
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_modeling.ipynb
├── src/
│   ├── __init__.py
│   ├── data_loader.py
│   └── utils.py
├── results/
│   ├── figures/
│   ├── model_summary.csv
├── requirements.txt
└── README.md
```

