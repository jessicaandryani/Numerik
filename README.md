UAS Metode Numerik - Bab 11: Matriks Khusus & Metode Gauss-Seidel

Repositori ini dibuat untuk memenuhi tugas mata kuliah Metode Numerik. Seluruh penyelesaian soal mengacu pada Bab 11 buku teks Numerical Methods for Engineers.

👤 Identitas Mahasiswa

Nama: Jessica Andryani

NIM: F55123051

Program Studi: Teknik Informatika

Kelas: A

📂 Struktur Repositori

Repositori ini disusun secara rapi dan terbagi menjadi dua bagian utama penyelesaian:

11_1_sampai_11_15.pdf:
Berisi penyelesaian matematis analitis (hitungan manual) untuk Soal 11.1 sampai 11.15.

11_16_sampai_11_28.ipynb:
Berkas Jupyter Notebook interaktif yang memuat kode program Python, grafik analisis kompleksitas, dan profil simulasi kanal untuk Soal 11.16 sampai 11.28.

⚙️ Fitur Program & Algoritma Mandiri

Di dalam Jupyter Notebook, terdapat beberapa modul algoritma numerik yang dibangun dari dasar (scratch) tanpa bergantung pada library instan:

Algoritma Thomas ($O(n)$): Penyelesaian efisien untuk matriks tridiagonal (Soal 11.24).

Dekomposisi Cholesky: Faktorisasi matriks simetris positif-definit $[A] = [L][L]^T$ (Soal 11.25).

Metode Iterasi Gauss-Seidel dengan Relaksasi: Iterasi linear dipercepat dengan parameter $\lambda$ (Soal 11.26).

Metode Beda Hingga (Finite Difference): Pemodelan distribusi zat kimia pada kanal 1 dimensi (Soal 11.27).

Pentadiagonal Solver ($O(n)$): Algoritma khusus untuk penyelesaian matriks bandwidth-5 (Soal 11.28).

