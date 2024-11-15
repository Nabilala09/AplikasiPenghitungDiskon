# Tugas 3: Aplikasi Perhitungan Diskon

**Nabila Parastiwi - 2210010420 - Kelas 5A Reg Pagi Banjarmasin**  
Mata Kuliah: Pemrograman Berbasis Objek

## Deskripsi

Aplikasi ini digunakan untuk menghitung harga akhir setelah diskon diterapkan berdasarkan harga asli dan persentase diskon yang dipilih.

## Fitur

- **Penghitungan Diskon**: Menghitung harga akhir dan jumlah penghematan.
- **Pilihan Persentase Diskon**: Menggunakan JComboBox atau JSlider untuk memilih nilai diskon.
- **Kode Kupon**: Menyediakan opsi untuk memasukkan kode kupon tambahan.
- **Riwayat Perhitungan**: Menampilkan riwayat diskon yang sudah dihitung.
- **Validasi Input**: Memastikan input valid dengan penanganan eksepsi.

## Komponen

- GUI menggunakan JFrame, JPanel, JLabel, JTextField, JComboBox, JButton, JSlider.
- Logika program mencakup perhitungan aritmatika dan validasi input.
- Event Handling:
  - **ActionListener** untuk tombol "Hitung".
  - **ItemListener** untuk JComboBox (pemilihan diskon).

## Cara Menjalankan

1. Clone repositori ini ke perangkat Anda.
2. Jalankan aplikasi dengan memastikan Java Runtime Environment (JRE) telah terinstal.
3. Masukkan harga asli, pilih persentase diskon, dan tekan tombol "Hitung".
4. Jika ada kode kupon, masukkan untuk tambahan diskon.
5. Lihat hasil harga akhir dan jumlah penghematan.
