# 🏁 Tugas Akhir (TA) - Final Project

**Nama Mahasiswa**: Ariella Firdaus Imata  
**NRP**: 5025211138  
**Judul TA**: PENAMBAHAN CATATAN PENERBANGAN DRONE PADA 
LINI MASA FORENSIK 
**Dosen Pembimbing**: Hudan Studiawan, S.Kom., M.Kom.,Ph.D.
**Dosen Ko-pembimbing**: Dr. Baskoro Adi Pratomo, S.Kom., M.Kom.

---

## 📺 Demo Aplikasi  
Embed video demo di bawah ini (ganti `VIDEO_ID` dengan ID video YouTube Anda):  

[![Demo Aplikasi](/assets/image.png)](https://www.youtube.com/watch?v=JFDYqSBl2NU)  
*Klik gambar di atas untuk menonton demo*

---


## 🛠 Panduan Instalasi & Menjalankan Software  

### Prasyarat  
- Python 3.10+

### Langkah-langkah  
1. **Clone Repository**  
   ```bash
   git clone https://github.com/Informatics-ITS/TA.git
   ```
2. **Instalasi Dependensi**
   ```bash
   cd plaso/plaso
   pip install -r requirements.txt  # Contoh untuk Python
   pip install setuptools
   ```
3. **Konfigurasi**
- Masuk ke dalam folder plaso/plaso dan build aplikasi
   ```bash
   python setup.py build
   python setup.py install
   ```
4. **Jalankan Aplikasi**
   ```bash
   log2timeline path/to/output.plaso path/to/artifact   # Membuat plaso storage
   psort -w path/to/output.csv path/to/storage.plaso   # Ekstrak Plaso Storage yang dibuat
   ```
   Contoh file artefak, storage.plaso, dan output.csv sudah disediakan pada folder artifact dan output_plaso
5. Buka file .csv yang telah dibuat untuk melihat hasil parsing drone

---

## ✅ Validasi

Pastikan proyek memenuhi kriteria berikut sebelum submit:
- Source code dapat di-build/run tanpa error
- Video demo jelas menampilkan fitur utama
- README lengkap dan terupdate
- Tidak ada data sensitif (password, API key) yang ter-expose

---

## ⁉️ Pertanyaan?

Hubungi:
- Penulis: [aril.imata061103@gmail.com]
- Pembimbing Utama: [hudan@pembimbing]
- Co-Pembimbing: [baskoro@pembimbing]
