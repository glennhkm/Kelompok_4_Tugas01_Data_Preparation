# Analisis Survei Musik & Kesehatan Mental

## Anggota Tim (Kelompok 4)
- Glenn Hakim (2208107010072)
- Ahmad Syah Ramadhan (2208107010033)
- Andika Pebriansyah (2208107010058)
- Nisa Rianti (2208107010018)
- Nuri Masyithah (2208107010006)

## Gambaran Proyek
Proyek ini mengeksplorasi hubungan antara preferensi musik dan kondisi kesehatan mental menggunakan dataset Music & Mental Health (MxMH) Survey Results dari Kaggle. Dataset ini berisi respons dari 736 peserta dengan 33 fitur, meneliti bagaimana genre musik yang berbeda dapat mempengaruhi faktor kesehatan mental seperti kecemasan, depresi, insomnia, dan OCD.

## Tujuan
1. Memahami cara memilih dan memuat dataset dari platform open-source
2. Menganalisis hubungan antara durasi mendengarkan musik, preferensi genre, dan perubahan kesehatan mental
3. Mengkaji struktur dan karakteristik dataset
4. Mengimplementasikan teknik preprocessing untuk meningkatkan kualitas dataset, termasuk penanganan missing values, encoding, normalisasi, dan pemilihan fitur

## Deskripsi Dataset
Dataset ini mencakup beberapa komponen utama:
- **Informasi Umum**: Kebiasaan mendengarkan musik dan faktor yang berpotensi mempengaruhi kesehatan mental
- **Preferensi Musik**: Frekuensi mendengarkan 16 genre musik berbeda (Pop, Rock, Hip-hop, Classical, dll.)
- **Metrik Kesehatan Mental**: Tingkat kecemasan, depresi, insomnia, dan OCD yang dilaporkan sendiri pada skala 0-10
- **Fitur Tambahan**: Usia, genre favorit, durasi mendengarkan musik, dan platform streaming yang digunakan
- **Fitur Target**: "Music effects" yang menunjukkan apakah musik memperbaiki, tidak berpengaruh, atau memperburuk kesehatan mental

## Proses Persiapan Data
Pipeline persiapan data kami meliputi:
1. **Data Loading**: Menggunakan library kagglehub dan pandas untuk mengunduh dan memuat dataset
2. **Data Understanding**: Menganalisis missing values, distribusi kelas, matriks korelasi, dan mengidentifikasi outlier
3. **Data Preparation**:
   - **Missing Values Handling**: Pendekatan khusus untuk fitur yang berbeda berdasarkan konteks dan tipe datanya
   - **Categorical Feature Encoding**: Mengkonversi variabel kategorikal ke format numerik menggunakan Label Encoding
   - **eature Selection**: Menghapus fitur yang tidak relevan seperti Timestamp dan Permissions

## Teknologi yang Digunakan
- Python
- Library: pandas, kagglehub, scikit-learn, matplotlib, seaborn

