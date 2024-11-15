## Aplikasi Perhitungan Diskon

Aplikasi ini digunakan untuk menghitung harga akhir setelah diskon berdasarkan harga asli yang dimasukkan oleh pengguna. Pengguna dapat memilih diskon persentase melalui slider dan memilih diskon tambahan melalui combo box. Selain itu, pengguna juga dapat memasukkan kode kupon untuk mendapatkan diskon tambahan jika berlaku.

## Fitur

- **Input Harga Asli**: Pengguna dapat memasukkan harga asli produk.
- **Slider Diskon**: Pengguna dapat memilih persentase diskon menggunakan slider.
- **Combo Box Diskon Tambahan**: Pengguna dapat memilih diskon tambahan yang berlaku untuk item tertentu.
- **Kode Kupon**: Pengguna dapat memasukkan kode kupon untuk mendapatkan diskon tambahan (misalnya, `DISKON10`).
- **Hasil Perhitungan**: Menampilkan harga akhir setelah diskon, total penghematan, dan riwayat perhitungan.
- **Validasi Input**: Memastikan harga asli yang dimasukkan valid dan lebih besar dari 0.

## Prasyarat

Aplikasi ini membutuhkan beberapa perangkat lunak berikut agar dapat dijalankan dengan baik:

- **Java**: Aplikasi ini dibangun menggunakan Java dengan library Swing untuk antarmuka pengguna.
- **NetBeans**: IDE yang digunakan untuk pengembangan aplikasi.

## Cara Penggunaan

1. **Masukkan Harga Asli**: Masukkan harga asli produk pada kolom "Harga Asli".
2. **Pilih Diskon**: Geser slider untuk memilih persentase diskon.
3. **Pilih Diskon Tambahan**: Pilih diskon tambahan melalui dropdown (ComboBox).
4. **Masukkan Kode Kupon (Opsional)**: Masukkan kode kupon jika memiliki, seperti `DISKON10` untuk diskon tambahan.
5. **Klik Hitung**: Tekan tombol "Hitung" untuk menghitung harga akhir setelah diskon dan penghematan.
6. **Lihat Hasil**: Hasil perhitungan, termasuk harga akhir, penghematan, dan riwayat diskon, akan muncul di bawah tombol "Hitung".

## Instalasi

### Langkah 1: Clone atau Unduh Repository

Clone repositori atau unduh file ZIP untuk mendapatkan kode sumber aplikasi.

```bash
git clone https://github.com/kouuch/AplikasiPerhitunganDiskon.git
Atau unduh file ZIP dan ekstrak.

Langkah 2: Buka di NetBeans
Buka NetBeans IDE.
Pilih File > Open Project.
Arahkan ke direktori tempat Anda menyimpan proyek dan pilih folder proyek.
Klik Open Project untuk memuat proyek.
Langkah 3: Jalankan Aplikasi
Klik kanan pada AplikasiPerhitunganDiskon.java di dalam Projects.
Pilih Run untuk menjalankan aplikasi.
Struktur Proyek
Berikut adalah struktur dasar proyek:

AplikasiPerhitunganDiskon.java: File utama yang berisi kode untuk antarmuka pengguna dan logika perhitungan diskon.
JTextField untuk input harga asli, harga akhir, hemat, dan kode kupon.
JComboBox untuk memilih diskon tambahan.
JSlider untuk memilih persentase diskon.
JTextArea untuk menampilkan hasil perhitungan.
Troubleshooting
Harga Asli Tidak Valid: Pastikan Anda memasukkan harga asli yang valid (angka lebih besar dari 0).
Kode Kupon Tidak Diterima: Pastikan kode kupon yang dimasukkan sesuai dengan yang didukung (misalnya DISKON10).
