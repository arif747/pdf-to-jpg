# PDF ke JPG Converter

Web sederhana untuk mengubah setiap halaman PDF menjadi JPG, dengan pratinjau dan unduhan satu per satu atau sebagai ZIP.

## Menjalankan di HP/komputer
1. Ekstrak ZIP ini.
2. Buka `index.html` menggunakan browser modern.
3. Koneksi internet diperlukan saat pertama kali memuat pustaka PDF.js dan JSZip dari CDN.
4. Pilih PDF, pilih resolusi dan kualitas, lalu tekan **Konversi ke JPG**.

## Publikasi gratis dengan GitHub Pages
1. Masuk ke GitHub dan buat repository baru, misalnya `pdf-to-jpg`.
2. Unggah `index.html` ke bagian paling atas/root repository.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu tekan **Save**.
6. Tunggu proses publikasi. URL akan muncul di bagian GitHub Pages pada halaman Settings.

## Catatan
- PDF diproses di browser perangkat; isi PDF tidak dikirim ke server aplikasi.
- Pustaka PDF.js dan JSZip dimuat dari CDN, jadi koneksi internet diperlukan.
- PDF besar atau resolusi sangat tinggi bisa memakai banyak memori. Jika gagal, coba resolusi lebih rendah.
