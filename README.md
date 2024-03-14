# Prediksi Jumlah Hotspot di Kalimantan Menggunakan Model Long Short-Term Memory Berdasarkan Indikator Iklim

Repository ini berisi lampiran program yang dibuat oleh Muhammad Daryl Fauzan, yaitu program untuk memprediksi jumlah hotspot di Kalimantan menggunakan model LSTM.

## Abstrak

Kebakaran hutan dan lahan (Karhutla) sudah menjadi fenomena yang memprihatinkan di Indonesia. Titik api (hotpsot) digunakan sebagai tahap awal untuk mengidentifikasi terjadinya kebakaran hutan. Model deep learning dapat digunakan untuk memprediksi jumlah hotspot. Salah satu model yang dapat digunakan untuk memodelkan hal tersebut adalah Long Short-Term Memory (LSTM). Oleh karena itu, tujuan dari penelitian ini adalah memprediksi jumlah hotspot di Kalimantan menggunakan model LSTM. Berdasarkan hasil evaluasi model, model-model LSTM yang dibangun menggunakan window berukuran 12 memiliki performa yang lebih baik dibandingkan model yang dibangun dengan window berukuran dua. Model terbaik yang dapat memprediksi jumlah titik hotspot adalah model LSTM dengan 2 layer LSTM dan 4 dense layer dengan masing-masing hidden layer menggunakan 64 node. Model ini menggunakan RMSE sebagai loss function, Nadam sebagai metode optimasi dengan learning rate sebesar 0,001, bobot yang diinisiasi menggunakan glorot uniform, serta metode early stopping dengan δ=0  serta patience selama 25 epoch.

