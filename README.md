# Startup Campus x MSIB Assignment
## Machine-Learning Classification 
## Using Random Forest Classifier and XGBoost Classifier

Dataset yang digunakan adalah dataset dari kaggle yang dapat diakses dengan link github berikut: https://raw.githubusercontent.com/romanouke/Data-Preprocessing-Dataset-DSAI/main/heart.csv

Melakukan klasifikasi dengan target feature adalah "No Disease" atau "Disease"
Diawali dengan Data Preprocessing dimana melihat missing value dan balancing data untuk data train dan data test
Kemudian proses klasifikasi dibagi menjadi 2 bagian untuk masing-masing metode, yaitu:
1. Tahap umum: Melakukan klasifikasi dengan semua feature/kolom dan kemudian melakukan hyperparameter tuning untuk menemukan parameter yang paling sesuai dengan data yang tentunya sesuai juga dengan metode
2. Tahap Feature Important: Menggunakan Feature Important yang didapatkan pada tahap umum yang mana nilai dari feature yang digunakan adalah > 0.05 dan tentunya menggunakan best parameter yang ditemukan di tahap umum
