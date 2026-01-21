# Health Issues Classification – Random Forest

Proyek ini melakukan **klasifikasi health issues** berdasarkan **gaya hidup dan konsumsi kopi** menggunakan algoritma **Random Forest**. Dataset yang digunakan adalah *Global Coffee Health Dataset*. Notebook ini membahas satu pendekatan klasifikasi dengan beberapa tahapan utama.

## Pendekatan Klasifikasi
Menggunakan seluruh fitur relevan yang berkaitan dengan:
- Gaya hidup
- Konsumsi kopi dan kafein
- Faktor kesehatan

Tahapan yang dilakukan meliputi:
- Pembersihan data (handling missing values)
- Seleksi fitur  
  (menghapus salah satu dari `Coffee_Intake` atau `Caffeine_mg`, dipilih `Caffeine_mg` karena lebih presisi)
- Encoding data kategorikal menggunakan **LabelEncoder**
- Pembagian data training dan testing

## Algoritma
Proyek ini menggunakan:
- **Random Forest Classifier**

dengan optimasi hyperparameter menggunakan:
- **GridSearchCV**

## Evaluasi Model
Model dievaluasi menggunakan beberapa metrik, yaitu:
- Accuracy
- F1-Score
- Confusion Matrix
- Classification Report (Precision, Recall, dan F1-score)

Pendekatan ini digunakan untuk memperoleh model klasifikasi dengan performa terbaik dalam memprediksi *health issues* berdasarkan gaya hidup dan konsumsi kopi.
