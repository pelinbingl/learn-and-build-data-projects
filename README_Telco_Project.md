# 📊 Telco Customer Churn Analysis – 7 Günlük Veri Bilimi Serüveni

Bu proje, **gerçek bir veri bilimi akışını baştan sona** uygulamak amacıyla hazırlanmıştır.  
7 gün boyunca veri temizleme, görselleştirme, modelleme, optimizasyon ve raporlama adımları uygulanmıştır.

👩‍💻 **Hazırlayan:** Pelin Bingöl  
🎯 **Amaç:** Gerçek bir veri bilimi sürecini adım adım öğrenmek ve uygulamak.  
🧠 **Veri seti:** [Telco Customer Churn (Kaggle)](https://www.kaggle.com/blastchar/telco-customer-churn)

---

## 📅 7 Günlük Çalışma Planı

| Gün | Konu | Hedef |
|-----|------|-------|
| **1. Gün** | Veri Bilimi Akışı & Ortam Kurulumu | Colab + Kaggle API kurulumu, veri setini tanıma |
| **2. Gün** | Veri Temizleme | Eksik değerler, veri türü dönüşümü, aykırı değer analizi |
| **3. Gün** | Görselleştirme & Korelasyon | Churn dağılımı, heatmap, boxplot, kategorik analizler |
| **4. Gün** | İlk ML Modelim (Logistic Regression) | Eğitim/test ayrımı, ölçekleme, model değerlendirme |
| **5. Gün** | Model Karşılaştırma | RandomForest, DecisionTree, Logistic Regression karşılaştırması |
| **6. Gün** | Model İyileştirme (SMOTE + GridSearchCV) | Veri dengeleme ve hiperparametre optimizasyonu |
| **7. Gün** | Raporlama & Yayın | Markdown + HTML raporu, Medium & GitHub sunumu |

---

## 🧰 Kullanılan Teknolojiler
- Python 3.10+  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn, Imbalanced-learn (SMOTE)  
- Google Colab  
- Kaggle API  
- Joblib  
- Markdown / HTML Raporlama  

---

## ⚙️ Model Performans Özeti

| Metrik | Değer |
|--------|-------|
| Accuracy | 0.84 |
| Precision | 0.79 |
| Recall | 0.83 |
| F1-Score | 0.81 |
| ROC-AUC | **0.89** |

📈 Son model: **Tuned Random Forest**  
⚖️ Veri dengesi: **SMOTE**  
🔧 Parametreler: **GridSearchCV (5-fold)**

---

## 🔍 En Önemli Özellikler (Feature Importance)

| Özellik | Etki |
|----------|------|
| Contract_Two year | 🔻 churn düşürüyor |
| tenure | 🔻 uzun müşteri ömrü sadakati artırıyor |
| MonthlyCharges | 🔺 yüksek fatura churn artırıyor |
| InternetService_Fiber optic | 🔺 fiber kullanıcıları riskli |
| OnlineSecurity_Yes | 🔻 güvenlik hizmeti churn azaltıyor |

---

## 📁 Dosya Yapısı
```
telco-churn-analysis/
│
├── 01_telco_day1_setup.ipynb
├── 02_telco_day2_cleaning.ipynb
├── 03_telco_day3_visuals.ipynb
├── 04_telco_day4_model.ipynb
├── 05_telco_day5_eval.ipynb
├── 06_telco_day6_tuning.ipynb
├── 07_telco_day7_final.ipynb
│
├── cleaned_telco_churn.csv
├── best_model_day6_tuned.pkl
├── scaler_day6.pkl
├── final_report_telco.md
└── images/
```

---

## 📊 Raporlar
- `final_report_telco.md` → Markdown formatında nihai rapor  
- `final_report_telco.html` → HTML versiyonu  
- `feature_importance.png`, `roc_curve.png`, `confusion_matrix.png`  

---

## 📬 Sonuç

Bu proje, sıfırdan bir veri bilimi sürecinin tamamını uygulamayı amaçlar:  
**veri temizleme → modelleme → optimizasyon → raporlama**

**Sonuç olarak:**
- Modelim %84 doğrulukla müşteri kaybını tahmin ediyor.  
- Churn’e en çok etki eden faktörleri görselleştirdim.  
- Proje artık yeniden eğitilebilir ve ölçeklenebilir bir yapıya sahip.  

---

## 🧠 Gelecek Planı
- Streamlit ile web arayüzü  
- MLOps pipeline (model güncellemeleri)  
- Yeni veri akışlarını API ile bağlama  

---

## ⭐ İletişim
**Pelin Bingöl**  
📩 [GitHub](https://github.com/pelinbingl) | [Medium](https://medium.com/@pelinbingl)

---

> 🌟 *“Bir veri bilimci, veriyi sadece analiz etmez; onun hikayesini anlatır.”*
