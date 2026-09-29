# Aplikasi Pembuka Mutasi Siswa

Halaman pembuka untuk GitHub Pages yang menampilkan logo Pemerintah Kabupaten Berau,
kemudian mengalihkan pengguna ke aplikasi Google Apps Script.

## Isi
- `index.html` — halaman pembuka + redirect otomatis 5 detik.
- `assets/logo-pemkab.png` — logo yang diberikan.

## Target aplikasi
https://script.google.com/macros/s/AKfycbyb3WUnQ3fBIK7i58WJTx-RWIqAY_3xPUDmwJrlGooKK02PPG8CUSosW7Hk8iDXop_z/exec

## Cara publish ke GitHub Pages
1. Buat repository baru di GitHub, misalnya `mutasi-siswa`.
2. Upload `index.html` dan folder `assets`.
3. Buka **Settings → Pages**.
4. Pada **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`.
6. Klik **Save**.
7. Tunggu GitHub Pages selesai diterbitkan.
8. Buka alamat GitHub Pages yang diberikan GitHub.

Pengguna yang membuka GitHub Pages akan melihat halaman pembuka, lalu otomatis
diarahkan ke aplikasi Mutasi Siswa setelah sekitar 5 detik. Tombol **Masuk ke Aplikasi**
dapat digunakan untuk langsung membuka aplikasi tanpa menunggu.
