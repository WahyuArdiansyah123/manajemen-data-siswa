Manual Book Aplikasi Manajemen Data Siswa

1. Login dan Register
- Buka browser dan akses http://localhost:8000 atau http://127.0.0.1:8000
- Untuk login, masukkan email, password, dan kode captcha, lalu klik Log in
- Untuk register, klik link "Belum punya akun? Register di sini", isi data, lalu submit
- Masukkan kode captcha yang muncul, klik Reload jika ingin mengganti captcha

2. Hak Akses Multilevel
- Admin: Bisa menambah, mengedit, menghapus, dan melihat data siswa
- User: Hanya bisa melihat data siswa
- Untuk menjadi admin, edit kolom level pada tabel users di database (phpMyAdmin), ubah dari user ke admin

3. Dashboard
- Setelah login, klik menu Dashboard
- Terdapat statistik total siswa, total user, total admin, dan jumlah siswa per kelas

4. Data Siswa
- Klik menu Data Siswa di navbar
- Admin dapat menambah, mengedit, menghapus, dan melihat detail siswa
- User hanya dapat melihat data siswa dan detail siswa

5. Pencarian Data Siswa
- Gunakan kolom pencarian di atas tabel untuk mencari siswa berdasarkan nama, NIS, atau kelas

6. Export Data Siswa ke Excel
- Klik tombol Export Excel di atas tabel siswa
- File Excel data_siswa.xlsx akan otomatis terunduh berisi data siswa

7. Edit Profil dan Logout
- Klik nama akun di pojok kanan atas, pilih Profile untuk mengedit profil atau ganti password
- Pilih Log Out untuk keluar dari aplikasi

8. Fitur Keamanan
- Setiap user harus login untuk mengakses data
- Captcha pada login untuk mencegah spam atau bot

9. Data Siswa Dummy
- Data siswa sudah otomatis terisi dengan nama-nama Indonesia

10. Upload Proyek ke GitHub Release
- Jika ingin membagikan project, upload file ZIP hasil kompres folder project ke menu Releases di GitHub
- Klik tab Releases di repo GitHub, klik Draft a new release, isi tag misal v1.0.0, beri judul dan deskripsi, lalu upload file ZIP di bagian Attach binaries
- Klik Publish release
- Cara ini digunakan karena ukuran file project terlalu besar untuk upload langsung ke repository

11. Catatan Teknis
- Pastikan menjalankan npm run dev agar tampilan modern aktif
- Jangan upload file .env ke publik, buat file .env baru jika install di komputer lain

12. Kontak dan Bantuan
- Jika ada kendala, hubungi pengembang aplikasi atau cek dokumentasi Laravel di laravel.com

Aplikasi ini siap digunakan untuk kebutuhan manajemen data siswa di sekolah, dengan fitur keamanan dan kemudahan penggunaan.
