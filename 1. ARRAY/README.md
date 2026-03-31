# Sistem Sederhana Pengelolaan Nilai Mahasiswa Menggunakan Array

## 1. Penjelasan Konsep Array

Array adalah salah satu konsep dasar dalam pemrograman dan struktur data. Secara sederhana, Array adalah sebuah variabel yang dapat menyimpan lebih dari satu nilai dengan tipe data yang sama dalam satu nama variabel.

Bayangkan Array seperti sebuah lemari loker yang panjang. Setiap kotak loker memiliki ukuran yang sama (tipe data sama) dan disusun secara berurutan. Untuk menemukan barang di dalamnya, Anda hanya perlu mengetahui nomor lokernya (indeks).

## 2. Screenshot Hasil Eksekusi

### - Input nilai
<img width="185" height="174" alt="image" src="https://github.com/user-attachments/assets/30417aca-028c-4bc5-a875-4fc0379eb84d" />

### - Output Hasil di Terminal
<img width="170" height="104" alt="image" src="https://github.com/user-attachments/assets/791c7ef1-6528-45e5-b345-e6e173f5a9fd" />

### - Grafik bar (Terendah – Rata-Rata – Tertinggi)
<img width="812" height="576" alt="image" src="https://github.com/user-attachments/assets/d0c40d9a-e030-4c09-a467-b6dc71863f95" />

### - Grafik bar (Lulus – Tidak Lulus)
<img width="507" height="470" alt="image" src="https://github.com/user-attachments/assets/52f9d700-68d1-499a-a39a-b8eb71963960" />

## 3. Analisis Kompleksitas
| Bagian Kode                      | Kompleksitas Waktu    | Kompleksitas Ruang    | Keterangan                       |
|----------------------------------|-----------------------|-----------------------|----------------------------------|
| Input Loop (for i in range(10))  | O(n)                  | O(n)                  | Bergantung pada jumlah data      |
| Fungsi Statistik (max, min, sum) | O(n)                  | O(1)                  | Scan list satu kali per fungsi   |
| Loop Analisis (Filter Lulus)     | O(n)                  | O(1)                  | Scan list satu kali              |
| Visualisasi (matplotlib)         | O(1)                  | O(1)                  | Data yang diplot bersifat tetap  |
| Total Keseluruhan                | O(n)                  | O(n)                  | Efisiensi Linear                 |

### 4. Refleksi Pembelajaran
Melalui pengerjaan proyek sistem sederhana ini, saya memperoleh beberapa poin pembelajaran utama dalam manajemen data dan pengembangan perangkat lunak:

- Pemahaman Struktur Data Dasar:  Saya kembali memperkuat konsep bahwa Array (yang dalam Python diimplementasikan sebagai List) adalah fondasi penting untuk menyimpan data secara terorganisir. Penggunaan indeks memungkinkan akses data yang cepat dan sistematis, terutama dalam kasus pengelolaan nilai dalam jumlah banyak.

- Pentingnya Analisis Efisiensi : Proses penyusunan tabel kompleksitas mengajarkan saya bahwa menulis kode tidak hanya sekadar "yang penting jalan". Dengan memahami Big O Notation (O(n)), saya belajar untuk mempertimbangkan bagaimana performa program akan terpengaruh jika jumlah input data (mahasiswa) meningkat dari puluhan menjadi ribuan.

- Integrasi Logika dan Visualisasi : Proyek ini menunjukkan betapa pentingnya mengubah data mentah menjadi informasi visual. Penggunaan library matplotlib mempermudah interpretasi hasil analisis (seperti distribusi nilai dan rasio kelulusan) yang jauh lebih sulit dipahami jika hanya melihat deretan angka di terminal.

- Dokumentasi Teknis yang Baik : Menyusun tugas ini ke dalam format Markdown di GitHub membantu saya melatih keterampilan komunikasi teknis. Menjelaskan alur kerja program secara naratif dan visual merupakan aspek krusial bagi seorang pengembang dalam berkolaborasi di ekosistem profesional.
