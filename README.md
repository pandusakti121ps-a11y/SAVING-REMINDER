# Savings Reminder

Savings Reminder adalah aplikasi desktop berbasis Python yang dikembangkan menggunakan CustomTkinter. Aplikasi ini dirancang untuk membantu pengguna mengelola tabungan pribadi secara terstruktur dan terorganisir. Dengan aplikasi ini, pengguna dapat menetapkan target tabungan, memantau progres tabungan, serta menerima pengingat terjadwal agar kebiasaan menabung dapat dilakukan secara konsisten.

---

## Fitur Utama

### Autentikasi Pengguna
- Sistem login dan registrasi  
- Mendukung banyak pengguna (multi-user)  
- Data akun pengguna disimpan secara lokal menggunakan file Excel  
- Setiap pengguna memiliki data tabungan yang terpisah dan aman  

### Manajemen Tabungan
Pengguna dapat membuat, mengubah, dan menghapus target tabungan dengan informasi berikut:
- Nama tabungan  
- Target nominal tabungan  
- Nominal setoran  
- Rencana menabung (harian, mingguan, atau bulanan)  

### Pelacakan Progres
- Menampilkan progres tabungan dalam bentuk progress bar dan persentase  
- Status tabungan secara otomatis dikategorikan sebagai **Ongoing** atau **Completed**  

### Dukungan Gambar
- Setiap target tabungan dapat dilengkapi gambar sebagai motivasi visual  
- Gambar disimpan secara lokal di folder khusus masing-masing pengguna  

### Sistem Pengingat (Reminder)
- Notifikasi desktop menggunakan Windows Toast Notification  
- Pengingat muncul sesuai dengan rencana menabung yang dipilih  
- Proses notifikasi berjalan di background menggunakan multiprocessing  

### Penyimpanan Data Lokal
- Data pengguna dan data tabungan disimpan dalam file `data.xlsx`  
- Data gambar disimpan secara lokal per pengguna  
- Informasi pengguna yang sedang aktif disimpan dalam file teks lokal  

---

## Library yang Digunakan
- CustomTkinter  
- OpenPyXL 
- Pillow   
- Win10Toast   
- Multiprocessing  

---

## Tujuan Pengembangan
Proyek ini dikembangkan sebagai proyek pembelajaran dengan tujuan untuk:
- Menerapkan pengembangan aplikasi desktop menggunakan Python  
- Mempelajari perancangan antarmuka grafis (GUI)  
- Mengimplementasikan penyimpanan data berbasis file  
- Mengelola proses background dalam aplikasi  
- Membuat sistem autentikasi pengguna sederhana  

---

## Catatan
- Aplikasi ini dibuat untuk keperluan edukasi  
- Dirancang untuk berjalan pada sistem operasi Windows karena penggunaan notifikasi berbasis Windows  
