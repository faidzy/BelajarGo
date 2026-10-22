# BelajarGo

Website jadwal pelajaran mingguan yang bisa di-host gratis menggunakan GitHub Pages.

## Cara upload ke GitHub

1. Buat repository baru di https://github.com/new, misalnya bernama `belajargo`.
2. Upload file `index.html` dari folder ini ke root repository (bagian paling atas, bukan ke subfolder).
3. Buka **Settings → Pages**.
4. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/ (root)`, lalu tekan **Save**.
6. Tunggu beberapa menit. GitHub akan menampilkan alamat website pada bagian Pages.

## Fitur

- Halaman masuk dan buat akun demo.
- Tabel jadwal untuk Senin–Minggu.
- Sembunyikan/tampilkan hari, atau tambah hari khusus.
- Pilihan mata pelajaran, jam mulai, jam selesai, dan catatan.
- Tambah, edit, dan hapus jadwal.
- Ubah warna utama, latar, dan kartu; tersedia preset tema.
- Data jadwal tersimpan di browser yang digunakan.
- Ekspor jadwal ke CSV.

## Catatan keamanan penting

Login di versi ini hanya demo front-end. Akun dan password disimpan pada `localStorage` browser, sehingga **jangan gunakan password email asli atau password penting**. Tidak ada email yang dikirim dan tidak ada autentikasi server. Setiap browser/perangkat memiliki data sendiri. Untuk aplikasi publik sungguhan, sambungkan sistem autentikasi dan database backend seperti Supabase atau Firebase.
