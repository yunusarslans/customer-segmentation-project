# 🛍️ Müşteri Segmentasyonu (Customer Segmentation) - KMeans Projesi

Bu projede, bir alışveriş merkezinin müşteri verileri kullanılarak KMeans algoritmasıyla müşteri segmentasyonu yapılmıştır.

## 📊 Kullanılan Özellikler
- Yaş (Age)
- Yıllık Gelir (Annual Income)
- Harcama Skoru (Spending Score)

## 🧪 Kullanılan Yöntemler
- Veri Görselleştirme (Histogram, Scatter Plot)
- KMeans Kümeleme
- PCA ve t-SNE ile Görselleştirme
- Elbow Yöntemi ile optimum küme sayısının belirlenmesi

## 📁 Proje Yapısı
```
.
├── data/                   # Orijinal CSV veri dosyası
├── images/                 # Grafik çıktıları (PNG)
├── notebooks/
│   ├── 01-eda.ipynb        # Keşifsel Veri Analizi (EDA)
│   └── 02-clustering-kmeans.ipynb  # KMeans ve Kümeleme Görselleştirme
├── README.md
└── requirements.txt
```

## 🛠️ Kurulum
Bu projeyi çalıştırmak için aşağıdaki kütüphanelerin kurulu olması gerekmektedir:

```bash
pip install -r requirements.txt
```

## 🧠 Amaç
Müşteri davranışlarını analiz ederek pazarlama stratejileri ve segment bazlı kampanyalar için veri odaklı bir temel oluşturmak.

## 👤 Yazar
- **Yunus Emre Arslan**
