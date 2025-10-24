# 📊 Telco Customer Churn – Final Rapor

## Model Performansı
|              |   precision |   recall |   f1-score |     support |
|:-------------|------------:|---------:|-----------:|------------:|
| 0            |    0.912466 | 0.836104 |   0.872617 | 5174        |
| 1            |    0.631625 | 0.777956 |   0.697195 | 1869        |
| accuracy     |    0.820673 | 0.820673 |   0.820673 |    0.820673 |
| macro avg    |    0.772045 | 0.80703  |   0.784906 | 7043        |
| weighted avg |    0.837939 | 0.820673 |   0.826065 | 7043        |

**ROC-AUC:** 0.902

## En Önemli Özellikler
|    | Feature                        |   Importance |
|---:|:-------------------------------|-------------:|
|  1 | tenure                         |    0.148995  |
| 28 | PaymentMethod_Electronic check |    0.143671  |
|  3 | TotalCharges                   |    0.12845   |
|  2 | MonthlyCharges                 |    0.0814325 |
| 10 | InternetService_Fiber optic    |    0.0776229 |
| 25 | Contract_Two year              |    0.0756232 |
| 26 | PaperlessBilling_Yes           |    0.0609269 |
| 24 | Contract_One year              |    0.0246771 |
|  9 | MultipleLines_Yes              |    0.0207777 |
|  8 | MultipleLines_No phone service |    0.0183009 |

📁 Model: `best_model_day6_tuned.pkl`

💬 *Bu model, SMOTE ve GridSearchCV ile optimize edilmiş final sürümdür.*

🧠 Hazırlayan: Pelin Bingöl
