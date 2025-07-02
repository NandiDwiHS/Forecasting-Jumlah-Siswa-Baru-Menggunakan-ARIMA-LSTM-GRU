# 📊 Prediksi Jumlah Siswa Baru Menggunakan ARIMA, LSTM, dan GRU

Repository ini merupakan implementasi program dari skripsi dengan judul:

**"Penerapan Metode Forecasting Pada Jumlah Siswa Baru di Sekolah Dasar Berbasis Data Historis Menggunakan ARIMA, LSTM, dan GRU"**

## 📝 Deskripsi

Penelitian ini bertujuan untuk membandingkan kinerja tiga model peramalan deret waktu — **ARIMA (model statistik klasik)**, **LSTM**, dan **GRU** (model deep learning) — dalam memprediksi jumlah siswa baru berdasarkan data historis dari **SDN Pasawahan 09**.

Hasil penelitian menunjukkan bahwa model **ARIMA** memiliki kinerja terbaik dengan nilai kesalahan paling rendah berdasarkan metrik RMSE, MAE, dan MAPE. Repository ini mencakup seluruh kode yang digunakan untuk preprocessing data, pelatihan model, evaluasi, dan visualisasi hasil.

## 🧪 Metodologi

- Preprocessing Data (Pembersihan, Normalisasi, Pembagian data latih dan uji 80:20)
- Model ARIMA (menggunakan `statsmodels`)
- Model LSTM dan GRU (menggunakan TensorFlow/Keras)
- Metrik Evaluasi:
  - Root Mean Square Error (RMSE)
  - Mean Absolute Error (MAE)
  - Mean Absolute Percentage Error (MAPE)


## 📊 Ringkasan Hasil Evaluasi

| Model | RMSE | MAE | MAPE |
|-------|------|-----|------|
| ARIMA | 3.54 | 2.56 | 7.73% |
| LSTM  | 7.63 | 7.24 | 22.37% |
| GRU   | 6.54 | 6.05 | 18.82% |

## 📌 Kata Kunci

`Peramalan Time Series` `ARIMA` `LSTM` `GRU` `Prediksi Siswa Baru` `Machine Learning` `Evaluasi Model` `Python`

## 📚 Lisensi

Proyek ini dikembangkan untuk keperluan akademik dan penelitian. Silakan gunakan dan sitasi dengan bijak.
