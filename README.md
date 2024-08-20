# Sertifikat-Generator
Generate Sertifikat Super Cepat dengan Python 

## Deskripsi
Proyek ini adalah sebuah script Python yang secara otomatis menambahkan nama peserta ke dalam template sertifikat. Nama-nama peserta diambil dari file CSV, kemudian diproses dan ditempatkan pada gambar sertifikat yang telah disiapkan. Hasil akhir dari proses ini adalah file PDF yang berisi sertifikat untuk setiap peserta.

## Fitur
- Membaca nama-nama peserta dari file `peserta.csv`.
- Menempatkan nama pada gambar sertifikat (`sertif.png`) dengan posisi dan ukuran font yang disesuaikan secara otomatis.
- Menyimpan sertifikat yang sudah diproses sebagai file PDF dalam folder `hasil`.

## Prasyarat
Pastikan Anda telah menginstall Python 3.8 atau versi latest, serta library yang diperlukan sebelum menjalankan script ini:

### Instalasi Library
1. **PIL** (Python Imaging Library):
    ```bash
    pip install pillow
    ```
2. **pandas**:
    ```bash
    pip install pandas
    ```

## Cara Penggunaan
1. **Persiapan File:**
    - **Template Sertifikat:** Simpan file gambar sertifikat dengan nama `sertif.png` di direktori yang sama dengan script.
    - **Nama Peserta:** Buat file CSV dengan nama `peserta.csv` yang berisi kolom `Name` untuk daftar nama peserta.
    - **Font:** Pastikan font `Poppins-Bold.ttf` sudah ada di direktori yang sama dengan script atau sesuaikan path-nya.

2. **Jalankan Script:**
    - Buka terminal di direktori tempat script berada.
    - Jalankan perintah berikut:
      ```bash
      python nama_script.py
      ```
    - Script akan memproses nama-nama dari file CSV dan menghasilkan file PDF sertifikat untuk setiap peserta.

3. **Cek Hasil:**
    - Setelah proses selesai, file sertifikat akan disimpan di folder `hasil` dengan nama file berdasarkan nama peserta.

Selamat Belajar dan Mencoba!
