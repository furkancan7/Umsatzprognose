# Makine Öğrenmesi ile Gelir Tahmini / Umsatzprognose mit Machine Learning

Bu proje, bir e-ticaret bağlamında aylık satış miktarlarını (Quantity) regresyon algoritmaları kullanarak tahmin etmek için geliştirilmiştir. Veri bilimi sürecinin tamamını kapsar: veri ön işleme, modelleme ve doğrulama.

Dieses Projekt wurde entwickelt, um die monatlichen Verkaufsmengen (Quantity) in einem E-Commerce-Kontext mithilfe von Regressionsalgorithmen vorherzusagen. Es deckt den gesamten Data-Science-Workflow ab: Datenvorverarbeitung, Modellierung und Validierung.

---

## Proje Amacı / Projektziel

Bu projenin amacı, fiyatlandırma, rekabet verileri ve ürün değerlendirmeleri gibi faktörlere dayanarak gelecekteki satış miktarlarını tahmin etmektir.

Ziel des Projekts ist es, basierend auf Faktoren wie Preisgestaltung, Wettbewerbsdaten und Produktbewertungen präzise Vorhersagen über zukünftige Verkaufszahlen zu treffen.

---

## Veri Yapısı & Strateji / Datenstruktur & Strategie

Bu projede eğitim ve test verileri arasında net bir ayrım yapılmıştır.

In diesem Projekt wird eine klare Trennung zwischen Trainings- und Testdaten vorgenommen.

- **Eğitim Verisi (`Testdatensatz.csv`)**  
  Modelin veri içindeki desenleri öğrenmesi için kullanılan ana veri setidir.  
  Primärer Datensatz zum Trainieren des Modells, um Muster und Zusammenhänge zu lernen.

- **Test Verisi (`Test.csv`)**  
  Model performansını ölçmek için kullanılan görülmemiş test verisidir.  
  Blind-Test-Datensatz zur finalen Bewertung der Modellleistung.

---

## Teknoloji Yığını / Tech Stack

- Dil / Sprache: Python  
- Kütüphaneler / Bibliotheken: Pandas, NumPy, Scikit-learn, Matplotlib, Joblib  
- Model / Modell: Random Forest Regressor  

---

## Model Performansı / Modellleistung

Test seti sonuçları / Ergebnisse auf dem Test-Set:

- R2 Score (Bestimmtheitsmaß): ~70,20%  
- RMSE (Root Mean Square Error): 8,98  

---

## Dosya Açıklaması / Dateibeschreibung

- `yzvas.ipynb`  
  Tüm Python kodlarının bulunduğu Jupyter Notebook dosyası.  
  Jupyter Notebook mit dem gesamten Python-Code.

- `model.pkl`  
  Eğitilmiş makine öğrenmesi modeli.  
  Trainiertes und exportiertes Machine-Learning-Modell.

- `le.pkl`  
  Kategorik verileri encode etmek için kullanılan LabelEncoder.  
  LabelEncoder für die Kategorisierung.

- `vorhersage_vs_tatsaechlich.png`  
  Gerçek ve tahmin edilen değerlerin karşılaştırma grafiği.  
  Visualisierung von vorhergesagten vs. tatsächlichen Werten.

---

## Yazar / Autor

Furkan Can Çelik
