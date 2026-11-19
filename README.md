# TUGAS PRAKTIKUM MODUL 6
Deskripsi
Repository ini berisi pengerjaan Tugas Praktikum Modul 6 pada materi **Association Rule Mining** (Analisis Aturan Asosiasi).
Praktikum ini bertujuan untuk memahami proses pencarian hubungan antaritem dalam sekumpulan transaksi menggunakan teknik Data Mining. Algoritma yang digunakan adalah Apriori dan FP-Growth dengan beberapa pengujian parameter serta analisis hasil aturan asosiasi.
Pengerjaan dilakukan menggunakan Python melalui Jupyter Notebook.

Tujuan Praktikum
1. Memahami konsep dasar Association Rule Mining.
2. Mengimplementasikan algoritma Apriori.
3. Menganalisis pengaruh nilai Minimum Support dan Minimum Confidence.
4. Menghitung nilai Support, Confidence, Lift, Leverage, dan Conviction.
5. Membandingkan performa algoritma Apriori dan FP-Growth.
6. Menerapkan Association Rule Mining pada studi kasus Petshop dan Klinik Hewan.

Materi dan Pembahasan
1. Analisis Minimum Support dan Minimum Confidence
Melakukan pengujian terhadap perubahan parameter:
- Minimum Support: 0.10 dan 0.15.
- Minimum Confidence: 0.50 dan 0.70.
- Pengujian variasi Minimum Confidence dari 0.50 hingga 1.00.
Analisis dilakukan untuk mengetahui pengaruh perubahan parameter terhadap jumlah Frequent Itemset dan aturan asosiasi yang dihasilkan.
2. Perhitungan Leverage dan Conviction
Melakukan analisis terhadap dua aturan asosiasi:
- Mie Instan → Telur
- Roti → Susu
Parameter yang dianalisis meliputi Support, Confidence, Lift, Leverage, dan Conviction.
3. Perbandingan Apriori dan FP-Growth
Membandingkan dua algoritma Association Rule Mining berdasarkan:
- Jumlah Frequent Itemset.
- Rata-rata waktu eksekusi.
- Konsistensi hasil itemset.
- Pengujian pada beberapa nilai Minimum Support.
4. Studi Kasus Mandiri: Petshop dan Klinik Hewan "Sehat Pets"
Menerapkan Association Rule Mining pada dataset simulasi yang terdiri dari:
- 50 transaksi.
- 12 jenis produk.
Produk yang digunakan meliputi makanan kucing, pasir kucing, snack kucing, vitamin kucing, makanan anjing, snack anjing, vitamin anjing, sampo hewan, obat cacing, kalung anti kutu, mainan, dan susu hewan.
Analisis mencakup:
- One-Hot Encoding.
- Frekuensi kemunculan item.
- Frequent Itemset menggunakan Apriori.
- Pembentukan Association Rules.
- Visualisasi Support, Confidence, dan Lift.
- Identifikasi 8 aturan asosiasi dengan Lift tertinggi.
- Pengujian variasi Minimum Support dan Minimum Confidence.


## Praktikum Data Mining – Evaluasi Model Klasifikasi

## Deskripsi
Praktikum ini membahas evaluasi model klasifikasi menggunakan Python dengan studi kasus deteksi transaksi pembayaran digital (fraud).

## Tujuan
- Memahami Confusion Matrix (TP, TN, FP, FN).
- Menghitung Accuracy, Precision, Recall, dan F1-Score.
- Melatih model klasifikasi Decision Tree.
- Memvisualisasikan hasil evaluasi model.
- Menganalisis pengaruh threshold terhadap hasil prediksi.

## Tools dan Library
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- JupyterLab

## Dataset
Menggunakan 500 data transaksi sintetis dengan fitur:
- `amount`
- `hour`
- `new_device`
- `foreign_ip`
- `isFraud`

## Cara Menjalankan
1. Buka JupyterLab.
2. Buka file notebook `.ipynb`.
3. Pastikan library sudah terinstal.
4. Jalankan seluruh cell secara berurutan.

## Model dan Evaluasi
Model yang digunakan adalah **Decision Tree Classifier** dengan evaluasi:
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-Score
- Baseline Classification
- Threshold Experiment  
