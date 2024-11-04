# MEMBUAT-APLIKASI-TOP-UP
![Screenshot (28)](https://github.com/user-attachments/assets/d109ae36-ce27-47aa-a169-7bb51ab65bef)
Kita membuat sebuah kelas bernama Toko. Kelas ini akan digunakan untuk mengelola saldo (uang) dan gems (mata uang dalam game) pengguna.
Di dalam kelas, ada fungsi khusus yang disebut __init__. Fungsi ini dijalankan saat kita membuat objek baru dari kelas ini.
Kita mulai dengan mengatur:
saldo: 500000 rupiah (uang pengguna).
gems: 0 (mata uang dalam game, awalnya tidak ada).
kurs: 1000 (nilai tukar 1 gem setara dengan 1000 rupiah).
Fungsi saldo_ke_gems digunakan untuk mengubah saldo rupiah menjadi gems.
Jika jumlah saldo yang ingin ditukar lebih besar dari saldo pengguna, program akan memberi tahu bahwa saldo tidak cukup.
Jika saldo cukup, program akan menghitung berapa banyak gems yang didapat dan mengurangi saldo pengguna.
Setelah berhasil, program akan mencetak pesan konfirmasi.
Fungsi buy_barang digunakan untuk membeli barang menggunakan gems.
Jika gems pengguna tidak cukup untuk membeli barang, program akan memberi tahu bahwa gems tidak mencukupi.
Jika cukup, program akan mengurangi jumlah gems yang dimiliki dan memberi tahu bahwa pembelian berhasil.
Fungsi status digunakan untuk menampilkan saldo dan jumlah gems yang dimiliki pengguna saat ini.
Kita mulai dengan membuat sebuah kelas bernama Toko. Kelas ini berfungsi sebagai kerangka untuk semua fitur yang ada di dalam toko.
Kita mulai dengan membuat sebuah kelas bernama Toko. Kelas ini berfungsi sebagai kerangka untuk semua fitur yang ada di dalam toko.
Fungsi ini digunakan untuk mengubah sejumlah uang (saldo) menjadi gems.
Pertama, kita cek apakah jumlah saldo yang ingin ditukar lebih besar dari saldo yang dimiliki. Jika iya, tampilkan pesan bahwa saldo tidak cukup.
Jika saldo cukup, kita hitung berapa banyak gems yang didapat.
Jumlah gems ditambahkan ke total gems pengguna, dan saldo dikurangi dengan jumlah uang yang ditukar.
Tampilkan pesan bahwa top up berhasil.
Fungsi membeli digunakan untuk membeli barang dengan menggunakan gems.
Kita cek apakah pengguna memiliki cukup gems untuk membeli barang. Jika tidak, tampilkan pesan untuk melakukan top up terlebih dahulu.Jika cukup, kurangi jumlah gems yang digunakan untuk pembelian dan tampilkan pesan bahwa pembelian berhasil.
Fungsi status menampilkan saldo dan jumlah gems yang dimiliki pengguna saat ini.
![Screenshot (29)](https://github.com/user-attachments/assets/f704ee83-40cb-42b3-9bf9-2febbd253102)
Fungsi main adalah titik masuk utama program. Di sinilah semua interaksi dengan pengguna terjadi.Saat program dimulai, kita membuat objek dari kelas Toko. Ini berarti kita memulai sebuah sesi toko untuk pengguna.Program akan berjalan terus-menerus hingga pengguna memilih untuk keluar. Ini memungkinkan pengguna untuk melakukan beberapa transaksi tanpa harus memulai ulang program.Setiap kali pengguna melihat menu ini, mereka memiliki empat opsi:
1. Top up: Mengubah uang menjadi gems.
2. Beli Barang: Membeli barang dengan gems.
3. Cek Status: Melihat saldo dan jumlah gems.
4. Keluar: Menutup program.selanjutnya Pengguna diminta untuk memasukkan pilihan mereka dari menu.Program akan memeriksa apa yang dipilih oleh pengguna dan menjalankan aksi yang sesuai:

Opsi 1: Top Up

Pengguna diminta untuk memasukkan jumlah uang yang ingin ditukar menjadi gems.
Jika saldo cukup, program akan mengubah uang tersebut menjadi gems.
Opsi 2: Beli Barang

Pengguna diminta untuk memasukkan nama barang dan harga dalam gems.
Program akan memeriksa apakah pengguna memiliki cukup gems untuk membeli barang tersebut.
Opsi 3: Cek Status

Program akan menampilkan saldo dan jumlah gems yang dimiliki pengguna saat ini.
Opsi 4: Keluar

Program akan mengucapkan terima kasih dan berhenti.
Opsi Tidak Valid

Jika pengguna memasukkan pilihan yang tidak ada, program akan memberi tahu bahwa pilihan tersebut tidak valid.
 cara untuk memastikan bahwa fungsi main dijalankan hanya ketika program ini dijalankan secara langsung, bukan ketika diimpor ke program lain.
