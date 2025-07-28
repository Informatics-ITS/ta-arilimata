# 🏁 Tugas Akhir (TA) - Final Project

**Nama Mahasiswa**: Ariella Firdaus Imata  
**NRP**: 5025211138  
**Judul TA**: PENAMBAHAN CATATAN PENERBANGAN DRONE PADA 
LINI MASA FORENSIK 
**Dosen Pembimbing**: Hudan Studiawan, S.Kom., M.Kom.,Ph.D.
**Dosen Ko-pembimbing**: Dr. Baskoro Adi Pratomo, S.Kom., M.Kom.

---

## 📺 Demo Aplikasi  


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
   git clone https://github.com/log2timeline/plaso.git
   ```
2. **Masukkan files ```init.py``` dan ```dji_mavic.py``` yang ada pada  ```plaso_files/parsers``` kedalam directory plaso ```plaso/plaso/parsers```**

3. **Masukkan files ```plaso_files/formatters/generic.yaml``` kedalam directory plaso ```plaso/data/formatters/generic.yaml```**

4. **Masukkan files dalam ```plaso_files/formatters/timeliner.yaml``` kedalam directory plaso ```plaso/data/timeliner.yaml```**

***Step dibawah akan dilakukan pada repository plaso yang telah di clone***

5. **Instalasi Dependensi**
   ```bash
   cd plaso/plaso
   pip install -r requirements.txt  # Contoh untuk Python
   pip install setuptools
   ```
6. **Konfigurasi**  
   Masuk ke dalam folder plaso/plaso dan build aplikasi
   ```bash
   python setup.py build
   python setup.py install
   ```
7. **Jalankan Aplikasi**
   ```bash
   log2timeline path/to/output.plaso path/to/artifact   # Membuat plaso storage
   psort -w path/to/output.csv path/to/storage.plaso   # Ekstrak Plaso Storage yang dibuat
   ```
   Contoh file artefak, storage.plaso, dan output.csv sudah disediakan pada folder artifact dan output_plaso

8. **Buka file .csv yang telah dibuat untuk melihat hasil parsing drone**

---

## ⁉️ Pertanyaan?

Hubungi:
- Penulis: [aril.imata061103@gmail.com]
- Pembimbing Utama: [hudan@pembimbing]
- Co-Pembimbing: [baskoro@pembimbing]
