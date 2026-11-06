# Sistem KangParkir
Kang Parkir adalah prototipe sistem manajemen parkir digital berbasis Python dengan 
antarmuka CLI (command line interface). Sistem ini berdiri sendiri (stand-alone) dan 
dirancang untuk menertibkan parkir yang selama ini kurang teratur: pencatatan dilakukan 
manual, karcis kertas mudah hilang, rusak, atau dipalsukan, dan tarif dihitung petugas 
sehingga rawan salah hitung. Sistem bersifat semi-otomatis, yaitu slot parkir ditentukan oleh 
sistem dan tidak dipilih bebas oleh pengunjung. 

## Fungsi Produk 
1. Pencatatan kendaraan masuk  Sistem mencatat data kendaraan (plat nomor dan jenis kendaraan) secara   otomatis menggunakan data dummy. Jika terjadi kesalahan, operator memasukkannya secara manual. Sistem mencatat waktu masuk. 
2. Pencarian dan pembaruan slot  Sistem menampilkan slot kosong dan terisi, menempatkan kendaraan pada slot, serta memperbarui statusnya saat kendaraan masuk dan keluar. 
3. Pembuatan token unik  Sistem membuat token berupa kode acak yang unik sebagai bukti kepemilikan kendaraan; saat keluar, token diperiksa dan petugas dapat memastikan kepemilikan secara manual. 
4. Penghitungan durasi, tarif, dan denda  Sistem menghitung biaya dari durasi parkir berdasarkan tarif, batas waktu, dan kebijakan denda yang berlaku.

## Rumusan Masalah
1. Lahan parkir yang masih berantakan
2. Hasil transaksi tidak tertata
