# TugasMachineLearningBab11

## 11. Praktikum Bab 11: Reduksi Dimensi (PCA, t-SNE, & LDA)

### 1. Kompresi Dimensi dengan PCA (Praktikum 1):
- *Cumulative Variance:* Penggunaan parameter pecahan desimal (misal 0.90) secara otomatis memilih jumlah komponen minimum yang dapat merepresentasikan sebagian besar varians data tanpa kehilangan informasi penting.
- *Dampak pada Performa:* Pengurangan dimensi terbukti mampu mempercepat waktu pelatihan model klasifikasi sekaligus mempertahankan tingkat akurasi yang tetap tinggi.

### 2. Perbandingan Visualisasi PCA, t-SNE, dan LDA (Praktikum 2):
- *PCA (Unsupervised):* Berfokus memaksimalkan varians global data secara linier.
- *t-SNE (Non-linear):* Sangat andal dalam memetakan struktur data kompleks ke ruang 2D sehingga pemisahan cluster terlihat jauh lebih tegas dan jelas.
- *LDA (Supervised):* Memanfaatkan label kelas untuk memaksimalkan pemisahan antar kelompok, menjadikannya pilihan ideal untuk tahap preprocessing sebelum proses klasifikasi.
