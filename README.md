# 📊 Umsatzprognose mit Machine Learning

Dieses Projekt wurde entwickelt, um die monatlichen Verkaufsmengen (Quantity) in einem E-Commerce-Kontext mithilfe von Regression-Algorithmen vorherzusagen. Es demonstriert den gesamten Data-Science-Workflow: von der Datenvorverarbeitung bis zur Modellvalidierung.

##  Projektziel
Das Hauptziel ist es, basierend auf Faktoren wie Preisgestaltung, Wettbewerbsdaten und Produktbewertungen präzise Vorhersagen über zukünftige Verkaufszahlen zu treffen.

##  Datenstruktur & Strategie
In diesem Repository wird eine strikte Trennung zwischen Training und Test durchgeführt:

* **Erhöhte Genauigkeit durch Training (`Testdatensatz.csv`):** Dies ist der primäre Datensatz, mit dem das Modell trainiert wurde, um Muster und Trends zu lernen.
* **Reale Validierung (`Test.csv`):** Dieser Datensatz dient als "Blind-Test" für das Modell. Er wurde ausschließlich für die finale Anwendung und Prüfung der Vorhersagekraft verwendet.

##  Tech Stack
* **Sprache:** Python
* **Bibliotheken:** Pandas, NumPy, Scikit-learn, Matplotlib, Joblib.
* **Modell:** Random Forest Regressor.

##  Modellleistung (Validierung)
Die Auswertung des Modells auf dem Test-Set ergab folgende Kennzahlen:
* **R2 Score (Bestimmtheitsmaß):** ~70,20%
* **RMSE (Root Mean Square Error):** 8,98

##  Dateibeschreibung
* `yzvas.ipynb`: Das Jupyter Notebook mit dem gesamten Python-Code.
* `model.pkl`: Das trainierte und exportierte Machine-Learning-Modell.
* `le.pkl`: Der gespeicherte LabelEncoder für die Kategorisierung.
* `vorhersage_vs_tatsaechlich.png`: Visualisierung der vorhergesagten vs. tatsächlichen Werte.

---
**Autor:** Furkan Can Çelik

