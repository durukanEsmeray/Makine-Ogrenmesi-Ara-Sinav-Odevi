# Makine Öğrenmesi Ara Sınav Ödevi

## Proje Hakkında
Bu proje, Topkapı Üniversitesi Makine Öğrenmesi dersi ara sınav ödevi kapsamında hazırlanmıştır.

## Veri Seti
- **Veri Seti:** Breast Cancer Wisconsin
- **Özellik Sayısı:** 30
- **Örnek Sayısı:** 569
- **Sınıflar:** Malignant (Kötü huylu), Benign (İyi huylu)

## Kullanılan Yöntemler
- Veri ön işleme ve EDA
- Boyut indirgeme: PCA ve LDA
- 5 farklı ML algoritması (Logistic Regression, Decision Tree, Random Forest, XGBoost, Naive Bayes)
- 15 model eğitimi (5 algoritma × 3 veri temsili)
- XAI: SHAP analizi

## Sonuçlar
- **En İyi Model:** Logistic Regression (Ham Veri)
- **Test Accuracy:** 97.37%
- **ROC-AUC:** 99.44%

## Dosyalar
- `Makine_Ogrenmesi_Ara_Sinav_Odevi.ipynb` - Jupyter Notebook (Tüm kod ve analizler)
- `Makine_Ogrenmesi_Ara_Sinav_Raporu.docx` - Detaylı rapor

## Öğrenci Bilgileri
- **Öğrenci:** Durukan Esmeray
- **Tarih:** 27 Kasım 2025
- **Üniversite:** Topkapı Üniversitesi


## Final Ödevi
- **Dosyalar:** 
  - `Makine_Ogrenmesi_Final_Odevi.ipynb` - Jupyter Notebook
  - `Makine_Ogrenmesi_Final_Raporu.docx` - Detaylı rapor
- **Modeller:** KNN, SVM (Linear/RBF), MLP, KMeans
- **En İyi Model:** SVM-Linear (Test Accuracy: 97.37%)
- **Hiperparametre Optimizasyonu:** GridSearchCV, RandomizedSearchCV
- **Kümeleme:** KMeans (k=2, ARI=0.65)
- **XAI:** SHAP Analizi
