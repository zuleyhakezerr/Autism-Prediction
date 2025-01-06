# Autism Prediction Project

## Proje Açıklaması
Bu proje, **Otizm Spektrum Bozukluğu (ASD)** tanısını daha doğru ve erken bir şekilde tahmin etmeyi amaçlayan bir makine öğrenimi uygulamasıdır. ASD, sosyal etkileşim ve davranışlarda farklılıklarla tanımlanan bir nörogelişimsel bozukluktur. Proje kapsamında kullanılan veri setleri ve algoritmalar, doğru sınıflandırma ile bireylerin yaşam kalitesini artırmayı hedeflemektedir.

## Projenin Özellikleri
- **Notebook Adı:** `autism-prediction-pycomp-2.ipynb`
- **Veri Analizi ve Görselleştirme:** Veri setinin keşfi ve görselleştirilmesi için **Seaborn**, **Matplotlib** ve **Plotly** gibi kütüphaneler kullanılmıştır.
- **Makine Öğrenimi:** 
  - **Karar Ağaçları (Decision Trees)**
  - **Rastgele Ormanlar (Random Forest)**
  - **XGBoost** gibi algoritmalar kullanılarak ASD tanısını tahmin etme modeli geliştirilmiştir.

## Kullanılan Teknolojiler
- **Python 3**
- **Jupyter Notebook**
- **Scikit-Learn**
- **Pandas ve NumPy**
- **Seaborn ve Matplotlib**
- **Plotly**

## Veri Seti
Proje, ASD tahmini için özel olarak hazırlanmış bir veri seti kullanır. Veri setindeki temel sütunlar şunlardır:
- **Age (Yaş):** Bireyin yaşı.
- **Gender (Cinsiyet):** Bireyin cinsiyeti.
- **Class/ASD:** ASD tanısı (0: Hayır, 1: Evet).
- **Jaundice (Sarılık):** Sarılık geçmişi.

## Kurulum ve Çalıştırma
Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

1. **Gerekli Kütüphaneleri Kurun:**
   ```bash
   pip install -r requirements.txt
