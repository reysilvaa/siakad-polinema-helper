# Siakad Polinema Menu Helper

Ekstensi browser untuk meningkatkan tampilan dan fungsionalitas Sistem Informasi Akademik (Siakad) Politeknik Negeri Malang.
>[!CAUTION] ini tidak terafiliasi atau didukung oleh polinema, ini hanyalah ekstensi tambahan untuk mempermudah saja

## Fitur

Ekstensi ini menambahkan tampilan yang lebih modern dan informatif pada halaman beranda Siakad Polinema dengan fitur-fitur berikut:

- **Menu Cepat** - Akses cepat ke menu-menu penting seperti Jadwal, KRS, Nilai, UKT, dll.
- **Jadwal Hari Ini** - Menampilkan jadwal kuliah untuk hari ini secara otomatis.
- **Informasi Akademik** - Menampilkan pengumuman dan informasi penting terkait perkuliahan.
- **Riwayat Pembayaran** - Menampilkan ringkasan pembayaran UKT terakhir.
- **Ringkasan Presensi** - Menampilkan statistik kehadiran (hadir, alpha, ijin, sakit) dan detail per mata kuliah.

## Tampilan

Ekstensi ini mengubah tampilan beranda Siakad Polinema menjadi lebih modern dengan:

- Layout yang responsif dan menyesuaikan dengan berbagai ukuran layar
- Kartu menu dengan ikon dan warna yang berbeda untuk navigasi yang lebih mudah
- Visualisasi data presensi yang lebih jelas dengan kode warna
- Tampilan yang bersih dan terorganisir untuk informasi penting

![image](readme/image.png)
## Cara Instalasi

### Chrome / Edge / Browser berbasis Chromium

1. Unduh atau clone repositori ini ke komputer Anda
2. Buka halaman ekstensi di browser (`chrome://extensions/` atau `edge://extensions/`)
3. Aktifkan "Mode Pengembang" (toggle di pojok kanan atas)
4. Klik tombol "Load unpacked" atau "Muat yang belum dikemas"
5. Pilih folder repositori yang sudah diunduh

### Firefox

1. Unduh atau clone repositori ini ke komputer Anda
2. Buka Firefox dan ketik `about:debugging` di address bar
3. Klik "This Firefox" atau "Firefox ini"
4. Klik "Load Temporary Add-on..." atau "Muat Pengaya Sementara..."
5. Pilih file `manifest.json` dari folder repositori yang sudah diunduh

## Cara Penggunaan

1. Setelah ekstensi terpasang, buka situs [Siakad Polinema](https://siakad.polinema.ac.id/)
2. Login dengan akun Anda
3. Buka halaman beranda
4. Tampilan baru akan otomatis dimuat

### Melihat Jadwal Hari Ini

Jadwal kuliah untuk hari ini akan otomatis ditampilkan di bagian "Jadwal Hari Ini".

### Melihat Ringkasan Presensi

1. Pada bagian "Ringkasan Presensi", pilih semester dari dropdown
2. Klik tombol "Filter"
3. Data presensi akan dimuat dan ditampilkan dengan statistik dan detail per mata kuliah

### Melihat Detail Lengkap

Setiap bagian memiliki tombol "Lihat Detail" atau "Lihat Semua" untuk melihat informasi lengkap di halaman terkait.

## Pengembangan

Ekstensi ini dikembangkan menggunakan JavaScript murni dan memanfaatkan API dari Siakad Polinema. Untuk berkontribusi:

1. Fork repositori ini
2. Buat branch fitur baru (`git checkout -b fitur-baru`)
3. Commit perubahan Anda (`git commit -m 'Menambahkan fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buat Pull Request

## Struktur Kode

- `manifest.json` - Konfigurasi ekstensi
- `content.js` - Kode utama yang memodifikasi tampilan Siakad
- `background.js` - Script background untuk menangani event browser
- `popup.html` - Popup saat ikon ekstensi diklik
- `icons/` - Folder berisi ikon ekstensi

## Catatan

- Ekstensi ini tidak menyimpan atau mengirim data kredensial atau informasi pribadi apapun.
- Ekstensi ini hanya memodifikasi tampilan pada sisi klien dan tidak mengubah data di server Siakad.
- Jika terjadi perubahan struktur pada website Siakad Polinema, ekstensi mungkin perlu diperbarui.

## Lisensi

MIT License - Silakan gunakan, modifikasi, dan distribusikan dengan bebas dengan mencantumkan atribusi yang sesuai.
