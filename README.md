# Simple Regression for Advertising Cost Prediction

# Case
Sebuah perusahaan periklanan mendapatkan klien yang ingin memprediksi cost Advertising yang perlu mereka keluarkan berdasarkan target penjualan.

# Deskripsi
Proyek ini  bertujuan untuk melakukan prediksi biaya iklan / advertising berdasarkan target penjualan menggunakan simple regression. Data yang digunakan diambil dari sumber (https://www.econometrics.com/intro/sales.htm).

# Langkah-langkah
1. **Persiapan Data**: Mengunduh dan membaca data menggunakan pandas. Data ini terdiri dari dua kolom:
- Sales: Variabel dependen yang merupakan target penjualan.
- Advertising: Variabel independen yang merupakan biaya advertising dalam jutaan dolar.
2. **Analisis dan Visualisasi Data**: Eksplorasi data awal dan visualisasi hubungan antara penjualan (sales) dan biaya iklan (advertising).
3. **Preprocessing Data**: Membersihkan data jika diperlukan.
4. **Model Simple Regression**: Membangun dan melatih model regresi linear sederhana.
5. **Prediksi**: Melakukan prediksi biaya iklan berdasarkan target penjualan dilakukan untuk target sales 50, 100, dan 150.
6. **Evaluasi Model**: Mengevaluasi model menggunakan Root Mean Squared Error (RMSE) dan R-squared (R2 score).

# Hasil Prediksi
- Prediksi biaya advertising untuk 50 sales: 77.82756831 : sekitar 77.83 juta dolar.
- Prediksi biaya advertising untuk 100 sales: 173.5759746 : sekitar 173.58 juta dolar.
- Prediksi biaya advertising untuk 150 sales: 269.3243809 : sekitar 269.32 juta dolar.

# Evaluasi Model
- RMSE: 14.367119905549034
- R2 Score: 0.3978668208721431

# Interpretasi
- RMSE: Hasil RMSE menunjukkan seberapa baik model memprediksi biaya advertising berdasarkan sales. Semakin rendah nilai RMSE, semakin baik modelnya. Nilai RMSE yang rendah menunjukkan bahwa model memiliki tingkat kesalahan prediksi yang kecil.
- R-squared (R2 Score): Nilai R2 score menunjukkan seberapa baik variabilitas dalam biaya advertising dapat dijelaskan oleh variabilitas dalam sales. R2 score yang mendekati 1 (nilai maksimum) menunjukkan bahwa model cukup baik dalam menjelaskan variasi biaya advertising berdasarkan sales.
- Hasil evaluasi menunjukkan seberapa baik model memprediksi data. Interpretasi ini membantu memahami seberapa akurat model dalam memprediksi biaya advertising berdasarkan target penjualan (sales) yang diberikan. Jika nilai RMSE rendah dan R2 score mendekati 1, ini menunjukkan bahwa model memiliki kinerja yang baik dalam konteks ini.
- Hubungan antara sales dan biaya advertising terlihat positif, yang berarti semakin tinggi sales, semakin tinggi pula biaya advertising yang diperlukan.
- Model regresi sederhana ini memberikan perkiraan yang cukup akurat untuk biaya advertising berdasarkan data penjualan yang diberikan. Dengan demikian, menggunakan analisis ini, perusahaan periklanan dapat membuat perkiraan biaya advertising yang diperlukan berdasarkan target penjualan mereka dengan tingkat kepercayaan yang baik.

# Kode
Seluruh kode dapat dilihat di file `Machine_Learning.ipynb`. Berikut adalah hasilnya :
<img width="409" alt="image" src="https://github.com/AfrohFauziah/Machine-Learning/assets/161470622/4d55904b-cc1d-433f-a0ae-fee0b4401b88">

<img width="137" alt="image" src="https://github.com/AfrohFauziah/Machine-Learning/assets/161470622/b858e736-282d-4395-bbba-03b300cf68b0">

# Visualisasi
Menampilkan scatter plot data asli dan garis regresi linear untuk memvisualisasikan hubungan antara sales dan advertising.

<img width="340" alt="image" src="https://github.com/AfrohFauziah/Machine-Learning/assets/161470622/01c177e4-4a3f-4cbb-b547-9a3311a0d0f6">
