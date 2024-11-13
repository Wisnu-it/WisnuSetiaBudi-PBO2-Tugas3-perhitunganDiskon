# WisnuSetiaBudi-PBO2-Tugas3-perhitunganDiskon
# Program Hitung Diskon

Pengguna dapat memasukkan harga, memilih metode diskon (menggunakan slider atau combo box), dan melihat hasil akhir setelah diskon diterapkan.
Fitur Utama

    Input Harga: Pengguna dapat memasukkan harga produk yang ingin dihitung diskonnya.
    Metode Diskon:
        Slider Diskon: Pengguna dapat mengatur nilai diskon dari 0% hingga 50% dengan menggeser slider.
        Combo Box Diskon: Pilihan diskon dalam bentuk persentase tetap mulai dari 5% hingga 50%.
        Pilihan Metode: Radio button memungkinkan pengguna untuk memilih antara slider atau combo box sebagai metode untuk menentukan diskon.
    Output: Harga setelah diskon akan ditampilkan di area teks.
    Tombol Tambahan:
        Hitung: Menghitung harga akhir setelah diskon.
        Hapus: Membersihkan semua input dan output.
        Keluar: Menutup aplikasi.

Cara Penggunaan

    Masukkan Harga: Ketikkan harga awal produk pada kolom input.
    Pilih Metode Diskon:
        Jika memilih slider, geser slider ke nilai diskon yang diinginkan.
        Jika memilih combo box, pilih persentase diskon yang tersedia.
    Klik tombol Hitung untuk mendapatkan harga setelah diskon.
    Gunakan tombol Hapus untuk membersihkan input dan hasil.
    Klik tombol Keluar untuk menutup aplikasi.

Struktur Kode

    Inisialisasi Komponen: Semua komponen GUI diinisialisasi dalam initComponents(), termasuk slider, combo box, dan tombol.
    Action Listeners:
        sliderDiskon.addChangeListener: Mengupdate tooltip pada slider saat pengguna menggeser slider untuk menunjukkan persentase diskon.
        buttonKeluar.addActionListener: Menutup aplikasi saat tombol "Keluar" diklik.
        buttonHapus.addActionListener: Membersihkan semua input dan hasil output.
        radioComboBox dan radioSlider: Mengaktifkan atau menonaktifkan komponen (slider atau combo box) berdasarkan metode diskon yang dipilih.
    Hitung Diskon (jButton1ActionPerformed): Mengambil harga dari input, membaca nilai diskon dari slider atau combo box, menghitung harga setelah diskon, dan menampilkan hasilnya di textAreaOutput.

![image](https://github.com/user-attachments/assets/4e041557-e15f-4362-896a-de977d43f801)

