# deep-learning-neural-network

## Prediksi Penyakit Diabetes dari Dataset Pima Diabetes

### Deskripsi
Memprediksi penyakit diabetes dari dataset pima diabetes. Beberapa fitur yang terdapat pada dataset seperti preg_times, glucose, blood_press, skin_thickness, insulin, BMI, pedigree, age. Base model yang digunakan berasal dari keras yaitu sequential. 

### Tujuan
Model yang dibangun dapat memprediksi apakah diabetes atau tidak diabetes. 

### Eksperimen
Eksperimen yang dilakukan untuk meningkatkan akurasi yaitu
- Mengubah value dari beberapa parameter pada proses train model (`batch_size` dan `epochs`)
```py
# change epochs size and batch size for input each dataset in model
model.fit(X_train, y_train, epochs=500, batch_size=8)
```

### Hasil
Hasil yang didapat dari eksperimennya adalah adanya peningkatan akurasi menjadi 75.97
