# AplikasiCekNomorGenapGanjil
Tugas 1 - Muhammad Fadilah (2210010500)

## Deskripsi

Aplikasi GUI sederhana ini dirancang untuk memvalidasi input angka dan memeriksa apakah angka yang dimasukkan adalah bilangan prima. Aplikasi ini dibuat untuk memahami dasar-dasar pemrograman antarmuka pengguna di Java dengan menggunakan komponen `JFrame`, `JPanel`, `JTextField`, `JLabel`, dan `JButton`.

## Fitur

- **Input Angka:** Pengguna dapat memasukkan satu angka ke dalam `JTextField` untuk diperiksa.
- **Validasi Input Angka:** Aplikasi hanya menerima input berupa angka dan akan menampilkan pesan error jika input tidak valid.
- **Pengecekan Bilangan Prima:** Jika input valid, aplikasi akan memeriksa apakah angka tersebut bilangan prima.
- **Tombol Cek:** Tombol ini berfungsi untuk memvalidasi dan menampilkan hasil pengecekan dalam `JLabel` atau melalui dialog `JOptionPane`.
- **FocusListener dan KeyAdapter:** 
  - Menghapus nilai input di `JTextField` ketika field mendapatkan fokus.
  - Membatasi input hanya untuk angka.

## Teknologi yang Digunakan

- **Java SE:** Digunakan untuk logika pemrograman dasar dan validasi input.
- **NetBeans IDE atau IDE lainnya:** Untuk pengembangan GUI dan kompilasi aplikasi.
- **Swing (javax.swing):** Mengelola antarmuka pengguna, termasuk `JFrame`, `JPanel`, `JLabel`, `JTextField`, `JButton`, dan `JOptionPane`.

## Struktur Aplikasi

1. **Antarmuka Pengguna (GUI):** Menyediakan field input, tombol, dan label untuk menampilkan hasil pengecekan.
2. **Logika Program:** Memastikan input valid dan memeriksa apakah input merupakan bilangan prima menggunakan kondisi if-else.
3. **Event Handling:** 
   - Mengelola event `ActionListener` pada tombol **Cek** untuk memicu validasi dan pengecekan angka.
   - Membatasi input hanya berupa angka dengan `KeyAdapter`.
   - Membersihkan `JTextField` dengan `FocusListener` saat mendapatkan fokus.

## Cara Menjalankan

1. Pastikan Anda telah menginstal **Java Development Kit (JDK)** dan **NetBeans IDE** (atau IDE lain yang mendukung Java Swing).
2. Buka proyek ini di NetBeans atau IDE favorit Anda.
3. Jalankan file utama aplikasi untuk membuka GUI.
4. Masukkan angka ke dalam `JTextField` dan tekan tombol **Cek** untuk melihat apakah angka tersebut bilangan prima.

## Screenshot
![AplikasiCekNomorGenapGanjil](https://github.com/user-attachments/assets/35729f61-3205-4038-991a-9cbad204b2bf)
