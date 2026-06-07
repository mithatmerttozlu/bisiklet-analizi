# Washington DC Bisiklet Kiralama Verisi Analizi

**Yazar:** Mithat Mert Tozlu  
**Öğrenci No:** 24 LITT 040  
**Ders:** Veri Analizinde Bilgisayar Programlama 2

🔗 **Canlı Rapor:** https://mithatmerttozlu.github.io/bisiklet-analizi/

> Yukarıdaki URL'yi GitHub kullanıcı adınla ve depo adınla değiştir (örnek: `https://mithatmert.github.io/bisiklet-analizi/`).

## Hakkında

Bu rapor, UCI Bike Sharing veri setini (Washington DC Capital Bikeshare, 2011-2012) kullanarak günlük bisiklet kiralama hareketlerini inceler. Tanımsal istatistikler, mevsimsel desenler, kullanıcı tipleri ve hava durumu etkisi analiz edilmiştir.

## İçerik

- Tanımsal istatistikler (`describe`, `value_counts`, `groupby`, korelasyon)
- 8 farklı görselleştirme:
  - Histogram, boxplot, scatter, bar (matplotlib/seaborn)
  - Korelasyon ısı haritası
  - 2 etkileşimli Plotly grafiği (zaman serisi + saatlik desen)
- Bulgular ve sınırlılıklar bölümü

## Veri Kaynağı

UCI Machine Learning Repository — Bike Sharing Dataset  
https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset

## Yerel Çalıştırma

```bash
pip install -r requirements.txt
jupyter notebook notebook/rapor.ipynb
```

## Klasör Yapısı

```
bisiklet-analizi/
├── data/
│   ├── day.csv
│   └── hour.csv
├── notebook/
│   └── rapor.ipynb
├── docs/
│   └── index.html       
├── requirements.txt
├── .gitignore
└── README.md
```
