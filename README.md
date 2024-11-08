# Tugas 3 - Aplikasi Perhitungan Diskon ([screenshot](#screenshot))

# JFrameAplikasiPerhitunganDiskon

Aplikasi ini adalah aplikasi **Java Swing** sederhana yang menghitung harga akhir setelah diskon diterapkan. Pengguna dapat memasukkan harga barang, memilih atau mengatur persentase diskon, dan menambahkan kupon diskon opsional untuk mendapatkan hasil perhitungan secara akurat. Hasil akhir dan riwayat perhitungan ditampilkan pada daftar untuk referensi pengguna.

## Fitur
- **Input harga barang**: Memungkinkan pengguna untuk memasukkan harga barang yang ingin dihitung.
- **Pilihan diskon**: Diskon dapat dipilih melalui kotak pilihan atau disesuaikan dengan slider.
- **Kupon diskon**: Pengguna dapat memasukkan kode kupon yang secara otomatis diterapkan pada harga akhir.
- **Riwayat perhitungan**: Semua perhitungan ditampilkan pada panel riwayat, memungkinkan pengguna untuk melihat ringkasan perhitungan sebelumnya.
  
## Prasyarat
- **Java Development Kit (JDK)** versi 8 atau lebih tinggi.
- **NetBeans IDE** atau IDE lain yang mendukung GUI Swing Java.

## Menjalankan Aplikasi
1. **Clone** atau **download** repositori ini.
2. Buka proyek di **NetBeans IDE** atau IDE Java pilihan Anda.
3. Jalankan kelas `JFrameAplikasiPerhitunganDiskon` untuk membuka aplikasi.

## Cara Penggunaan
1. Masukkan **harga** barang di kotak input harga.
2. Pilih **diskon** yang diinginkan menggunakan kotak pilihan atau sesuaikan dengan slider.
3. Klik tombol **"Hitung"** untuk memproses harga setelah diskon.
4. Jika ada, masukkan **kode kupon** untuk diskon tambahan.
5. Hasil perhitungan akan muncul dalam dialog, dan ringkasan hasil akan disimpan di panel **riwayat perhitungan**.

## Contoh Output
- **Input**: Harga = `100000`, Diskon = `10%`, Kupon = `GRATIS`
  - **Output Dialog**:
    ```
    Harga akhir Rp. 0
    Total hemat Rp. 100000
    Diskon -10%
    Diskon kupon -100%
    ```

   - **Ringkasan Riwayat**:
      ```
      harga: Rp. 100000 | diskon: 10% | kupon: "GRATIS" | diskon kupon: 100% | harga akhir: Rp. 0
      ```

## Struktur Kode

- **jButton1ActionPerformed**: Mengambil harga dan diskon yang dipilih, kemudian menghitung harga akhir dan menampilkan hasilnya.
- **cekKupon**: Mengecek dan mengembalikan nilai diskon berdasarkan kode kupon.
- **jSlider1StateChanged**: Menyesuaikan pilihan diskon di kotak pilihan sesuai dengan nilai slider.

## Detail tugas

1. Deskripsi Program:

   - Pengguna memasukkan harga asli dan memilih persentase diskon
   - Setelah menghitung, tampilkan harga akhir dan jumlah penghematan

2. Komponen GUI: JFrame, JPanel, JLabel, JTextField, JComboBox, JButton

3. Logika Program: Perhitungan aritmatika, Penanganan eksepsi

4. Events:

   - ActionListener untuk tombol Hitung
   - ItemListener pada JComboBox untuk memilih persentase diskon

5. Variasi:

   - Tambahkan opsi untuk memasukkan kode kupon diskon tambahan
   - Tambahkan JSlider sebagai alternatif JComboBox untuk memilih persentase diskon
   - Sediakan riwayat perhitungan diskon yang telah dilakukan.

## Screenshot

Nama : Ahmad Yasser

NPM  : 2210010525

Kelas: 5A REGULER BJB TI

1. Tampilan awal
![image](https://github.com/user-attachments/assets/ab79be93-8769-4595-9c57-aac48dd72540)

2. Klik tombol hitung (harga: 20000, diskon 10%)
![image](https://github.com/user-attachments/assets/5d21d0c7-126c-42ff-a9d4-a8d48ecee398)

3. Kupon kosong
![image](https://github.com/user-attachments/assets/a8a9099e-3bf8-4217-a5d7-adbb43dec242)

4. Kupon GRATIS (diskon tambahan 100%)
![image](https://github.com/user-attachments/assets/a82a30df-c4fb-4447-9ec1-cc4092eca382)

5. Tampilan riwayat perhitungan
![image](https://github.com/user-attachments/assets/0ee542fc-ff5c-49b9-ad96-03e31893d9a6)
![image](https://github.com/user-attachments/assets/a1ee6b18-ee35-4951-9fef-b81e2c19bbdd)

6. Pilih diskon dengan slider
![image](https://github.com/user-attachments/assets/2457e95a-bdc2-43e7-9727-304f4b522dfb)
