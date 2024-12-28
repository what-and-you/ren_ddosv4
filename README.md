# 🌐 ren_ddosv4 🛡️

`ren_ddosv4` adalah skrip Python untuk mengirim request HTTP secara bersamaan untuk tujuan **pengujian performa server** atau **simulasi serangan DDoS**. Skrip ini mendukung berbagai metode HTTP dan penggunaan threading untuk meningkatkan beban pengujian.

## 🚀 Cara Menggunakan

### 1. **Install Dependensi**:
   Sebelum menjalankan skrip, pastikan Anda telah menginstal pustaka yang dibutuhkan:
   ```bash
   pip install requests colorama

2. Jalankan Skrip:

Untuk menjalankan skrip, buka terminal dan ketik:

python ren_ddosv4.py

3. Pilih Opsi:

Setelah dijalankan, Anda akan melihat tampilan menu interaktif di terminal. Pilih salah satu opsi berikut:

Kirim Request: Pilih metode HTTP dan jumlah request yang ingin dikirim.

Cek Status Website: Cek apakah situs aktif atau down.

Cek IP Website: Dapatkan alamat IP dari situs yang ditargetkan.

Keluar: Menutup skrip.


🌟 Fitur Utama

Metode HTTP: Mendukung GET, POST, PUT, DELETE, HEAD.

Threading: Mengirimkan request secara paralel untuk meningkatkan beban.

Cek Status & IP: Mengetahui apakah server sedang aktif dan memperoleh alamat IP situs.


⚖️ Peraturan Penggunaan

Hanya untuk Uji Coba: Gunakan skrip ini hanya untuk situs yang Anda miliki atau dengan izin eksplisit.

Tidak untuk Serangan Tanpa Izin: Dilarang keras menggunakan skrip ini untuk menyerang situs yang tidak Anda miliki atau tanpa izin eksplisit.


💡 Rekomendasi Penggunaan

Pengujian Server: Gunakan untuk menguji performansi server dan ketahanannya terhadap trafik tinggi.

Simulasi DDoS: Dapat digunakan untuk simulasi DDoS pada server yang Anda miliki.


Threading:

Jumlah Thread: Disarankan menggunakan jumlah thread yang lebih sedikit jika server yang diuji memiliki kapasitas terbatas atau untuk pengujian ringan. Misalnya, mulai dengan 10-50 thread.

Jumlah Thread Tinggi: Untuk simulasi DDoS atau pengujian beban tinggi, Anda dapat menambah jumlah thread hingga 100 atau lebih. Hati-hati, karena semakin banyak thread, semakin besar beban pada server yang diuji.

Pertimbangkan Kapasitas Server: Pastikan server yang diuji dapat menangani jumlah thread dan request yang dikirim tanpa menyebabkan kerusakan yang tidak diinginkan.


🔥 Tips dan Trik

Penggunaan Terbaik: Cobalah untuk mengatur jumlah request, ukuran damage, dan jumlah bot yang seimbang. Jangan terlalu memaksakan server Anda untuk hasil yang optimal.

Menguji Server Pribadi: Sebelum menguji server yang lebih besar atau situs web publik, pastikan Anda menguji di server yang Anda miliki untuk memastikan pengujian berjalan dengan aman.
