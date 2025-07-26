# 🏁 Tugas Akhir (TA) - Final Project

**Nama Mahasiswa**: Layyinatul Fuadah  
**NRP**: 5025211207  
**Judul TA**: Pengembangan Fitur Klasifikasi Ikan pada Aplikasi Mobile Kebun Binatang Menggunakan Transfer Learning  
**Dosen Pembimbing**: Ir. Adhatus Solichah Ahmadiyah, S.Kom., M.Sc.  
**Dosen Ko-pembimbing**: Ilham Gurat Adillion, S. Kom., M. Eng

---
## ZooSite 🐾

ZooSite adalah aplikasi edukasi kebun binatang dengan fitur klasifikasi gambar hewan dan interaksi melalui chatbot. Aplikasi ini dikembangkan sebagai bagian dari Tugas Akhir yang telah dikembangkan oleh penulis-penulis sebelumnya.

## 📺 Demo Aplikasi  

[![Demo Aplikasi](https://i.ytimg.com/vi/qc_k0OdLX1I/maxresdefault.jpg)](https://www.youtube.com/watch?v=qc_k0OdLX1I)  
*Klik gambar di atas untuk menonton demo*

---

*Konten selanjutnya hanya merupakan contoh awalan yang baik. Anda dapat berimprovisasi bila diperlukan.*
## 🚀 Fitur Utama
- Peta Kebun Binatang
- Chatbot Edukatif
- Klasifikasi Hewan dengan Gambar
- Pengenalan Suara Hewan
---
## 🛠 Panduan Instalasi & Menjalankan Software  

### Prasyarat  
- Daftar dependensi (contoh):
  - Flutter SDK minimal versi 3.32.0
  - NAndroid Studio atau VS Code
  - Git
  - Emulator Android atau perangkat fisik

### Langkah-langkah  
1. **Clone Repository**  
   ```bash
   git clone https://github.com/Informatics-ITS/TA.git
   ```
2. Download Resources model:
  - [✅ Download Model Kusumo, 2023](https://drive.google.com/file/d/xxxxxxxx/view?usp=sharing)
  - [✅ Download Model Auliya, 2024](https://drive.google.com/file/d/yyyyyyyy/view?usp=sharing)
  - [✅ Download Model Fuadah, 2025](https://drive.google.com/file/d/zzzzzzzz/view?usp=sharing)

3. Buat folder [models] baru didalam folder [asset]:
   ```bash
    mkdir -p assets/models
   
4. Salin semua file model yang sudah di download ke dalam folder [models] dan pastikan nama nya sama.
  - kusumo_model.tflite
  - auliya_model.tflite
  - fuadah_model.tflite
  
5. Pastikan sudah mendownload flutter dengan version minimal [3.32.0]. untuk cara ceknya:
   ```bash
    flutter --version
   ```
    jika masih dibawah versi tersebut, maka langsung upgrade ke versi paling baru
    ```bash
      flutter --upgrade
     ```
6. Setelah semua step diatas berhasil, maka langsung run:
   ```bash
    flutter pub get

7. Instalasi selesai. untuk menjalankan maka tinggal run saja melalui IDE masing-masing, atau dengan:
   ```bash
    flutter run
---
## ⚠️ Kendala

- ✅ Saat ini aplikasi **hanya bisa dibuild dalam format `.apk`** untuk Android dan diuji langsung di emulator atau perangkat fisik.
- ❌ Untuk platform **iOS (`.ipa`) belum dapat dilakukan build langsung**, karena:
  - Membutuhkan akses ke **TestFlight** untuk distribusi dan pengujian.
  - Perlu **akun Apple Developer** berbayar (USD 99/tahun) untuk dapat membangun dan menjalankan aplikasi di perangkat iOS fisik maupun distribusi via App Store.
  
> **Solusi sementara**: Fokus pengujian pada platform Android. Untuk distribusi iOS, akan dilakukan jika akses Apple Developer tersedia.
---
## 📚 Referensi & Kredit

Pengembangan fitur klasifikasi hewan dalam aplikasi ini mengacu pada hasil penelitian dan kontribusi dari penulis sebelumnya:

1. **Cikanindi, Vania (2022)**  
   Penerapan Universal Sentence Encoder (Use) Untuk Location-Aware Chatbot Pada Aplikasi Layanan Wisata Kebun Binatang.  
   [Undergraduate Tesis](https://repository.its.ac.id/94474/)

2. **Kusumo, Naufaliando Yudo (2023)**  
   Pengembangan Fitur Klasifikasi Hewan pada Aplikasi Wisata Kebun Binatang dengan Algoritma CNN.  
   [Undergraduate Tesis](https://repository.its.ac.id/104229/)

3. **Auliya, Maisan (2024)**  
   Perbaikan Klasifikasi Hewan pada Aplikasi Mobile Kebun Binatang dengan Transfer Learning.  
   [Undergraduate Tesis](https://repository.its.ac.id/111053/)  

> Jika kamu menggunakan proyek ini dalam penelitian atau pengembangan lain, mohon cantumkan referensi kepada penulis-penulis di atas.
---
## ⁉️ Pertanyaan?

Hubungi:
- Penulis: layyinatul7@gmail.com
- Pembimbing Utama: adhatus@gmail.com
