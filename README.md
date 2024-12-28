# ren_ddosv4 -  Fitur Terbaru Dari REN9999

**ren_ddosv4** adalah skrip Python untuk melakukan pengujian beban pada server menggunakan simulasi DDoS. Skrip ini memungkinkan Anda untuk menguji ketahanan server terhadap trafik yang tinggi dan memastikan performa server dalam kondisi tekanan.

---

## ⚙️ Cara Menggunakan

### 1. **Install Dependensi**:
   Pastikan Anda menginstal pustaka yang dibutuhkan sebelum menjalankan skrip:
   bash
   pip install requests colorama

2. Jalankan Skrip:

Setelah dependensi terpasang, buka terminal Anda dan jalankan skrip dengan perintah berikut:

python ren_ddosv4.py

3. Pilih Opsi Pengujian:

Setelah menjalankan skrip, Anda akan melihat menu interaktif di terminal. Pilih salah satu opsi untuk melanjutkan pengujian:

Kirim Request: Pilih metode HTTP dan tentukan jumlah request yang ingin dikirim.

Cek Status Website: Cek apakah situs yang ditargetkan aktif atau down.

Cek IP Website: Peroleh alamat IP dari situs yang Anda uji.

Keluar: Menutup skrip.



---

# 🌟 Fitur Utama

Metode HTTP: Mendukung GET, POST, PUT, DELETE, HEAD untuk pengujian berbagai jenis request.

Threading: Mengirimkan request secara paralel menggunakan threading untuk meningkatkan beban pada server.

Cek Status & IP: Memudahkan untuk mengetahui apakah server aktif dan mendapatkan informasi IP dari website yang diuji.



---

# ⚖️ Peraturan Penggunaan

Hanya untuk Pengujian yang Sah: Skrip ini hanya boleh digunakan untuk menguji server atau situs yang Anda miliki atau memiliki izin eksplisit untuk diuji.

Tidak untuk Serangan Tanpa Izin: Dilarang keras menggunakan skrip ini untuk menyerang situs yang tidak Anda miliki atau tanpa izin eksplisit dari pemilik situs.



---

# 💡 Rekomendasi Penggunaan

Pengujian Server:

Gunakan ren_ddosv4 untuk menguji performa server Anda dalam menghadapi trafik tinggi. Skrip ini bisa memberikan gambaran apakah server dapat bertahan di bawah tekanan yang besar.

Simulasi DDoS:

ren_ddosv4 memungkinkan Anda untuk mensimulasikan serangan DDoS pada server yang Anda miliki untuk menguji ketahanan dan memastikan bahwa server siap menangani trafik tinggi.


---

Threading dan Pengaturan Jumlah Request:

Jumlah Thread: Untuk pengujian ringan, gunakan jumlah thread yang lebih sedikit (misalnya 10-50 thread). Jika server memiliki kapasitas terbatas, disarankan untuk memulai dengan jumlah thread yang lebih rendah.

Jumlah Thread Tinggi: Untuk simulasi DDoS atau pengujian beban tinggi, Anda bisa menambah jumlah thread lebih banyak (100 atau lebih). Hati-hati, semakin banyak thread yang digunakan, semakin besar beban yang diberikan kepada server yang diuji.

Pertimbangkan Kapasitas Server: Pastikan server yang diuji dapat menangani jumlah thread dan request yang dikirim tanpa menyebabkan kerusakan pada server tersebut.



---
