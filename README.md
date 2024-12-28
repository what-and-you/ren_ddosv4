
# ren_ddosv4

`ren_ddosv4` adalah skrip Python untuk mengirim request HTTP secara bersamaan untuk tujuan pengujian performa server atau simulasi serangan DDoS. Skrip ini mendukung berbagai metode HTTP dan penggunaan threading untuk meningkatkan beban pengujian.

## Cara Menggunakan

1. **Install Dependensi**:
   Pastikan Anda telah menginstal pustaka yang dibutuhkan:
   ```bash
   pip install requests colorama

2. Jalankan Skrip: Untuk menjalankan skrip, buka terminal dan ketik:

python ren_ddosv4.py


3. Pilih Opsi: Setelah dijalankan, pilih salah satu opsi berikut:

Kirim Request: Pilih metode HTTP dan jumlah request yang ingin dikirim.

Cek Status Website: Cek apakah situs aktif atau down.

Cek IP Website: Dapatkan alamat IP dari situs yang ditargetkan.

Keluar: Menutup skrip.




Fitur

Metode HTTP: GET, POST, PUT, DELETE, HEAD.

Threading: Mengirimkan request secara paralel.

Cek Status & IP: Cek status server dan alamat IP situs.


Peraturan Penggunaan

Gunakan skrip ini hanya untuk situs yang Anda miliki atau dengan izin eksplisit.

Jangan gunakan untuk menyerang situs tanpa izin.


Rekomendasi

Pengujian Server: Gunakan untuk menguji performa server dan ketahanannya terhadap trafik tinggi.

Simulasi DDoS: Lakukan simulasi serangan DDoS pada server yang Anda miliki.

Threading:

Jumlah Thread: Disarankan menggunakan jumlah thread yang lebih sedikit jika server yang diuji memiliki kapasitas terbatas atau untuk pengujian ringan. Misalnya, mulai dengan 10-50 thread.

Jumlah Thread Tinggi: Untuk simulasi DDoS atau pengujian beban tinggi, Anda dapat menambah jumlah thread hingga 100 atau lebih. Hati-hati, karena semakin banyak thread, semakin besar beban pada server yang diuji.

Pertimbangkan Kapasitas Server: Pastikan server yang diuji dapat menangani jumlah thread dan request yang dikirim tanpa menyebabkan kerusakan yang tidak diinginkan.



Lisensi

Skrip ini dilisensikan di bawah MIT License.

---

Penambahan di bagian **rekomendasi** memberikan saran tentang penggunaan thread, terutama untuk memastikan pengujian tidak menyebabkan kerusakan pada server atau layanan yang sedang diuji.

