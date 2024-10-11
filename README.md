# install-apacheKode
Masalah
Tarik permintaan
Mengedit README.md di Setting-Mikrotik
Tepung rotiPengaturan-Mikrotik
/
README.md
di dalam
utama

Sunting

Pratinjau

Tampilkan Perbedaan
Pengaturan-MikrRobat kuat
Mikrotik adalah sebuah sistem operasi berbasis perangkat lunak yang berfungsi untuk mengubah komputer menjadi router. Sistem mikrotik digunakan di berbagai tempat baik institusi, perusahaan, maupun perorangan.

Cara Setting Mikrotik dari Awal sampai Akhir Mikrotik menggunakan sistem komputer berbasis Linux untuk dijadikan dasar router jaringan. Mikrotik berbeda dengan ruter, software ini memiliki fitur tambahan seperti SNMP, Monitoring, Caching DNS Client, Firewall dan NAT, Web Proxy, dan Tools.

Menghubungkan Router Ada dua jenis router yang bisa digunakan untuk mengatur Mikrotik, yaitu dengan konfigurasi perangkat dan tidak. Jenis ruter yang pertama bisa mengikuti buku petunjuk sesuai ruter yang digunakan. Untuk router yang tidak memiliki konfigurasi, langkah yang harus dilakukan adalah menghubungkan port Enther 1 router ke kabel WAN dan menghubungkan PC ke Ether2.

Setelah itu, buka WinBox dan cari ruter yang sedang digunakan kemudian klik tombol 'Connect' untuk menghubungkan ke router tersebut.

Setting Konfigurasi IP Address Konfigurasi IP Adreess dapat dilakukan melalui berbagai perangkat. Pada contoh kali ini, pengaturan konfigurasi IP Adreess akan dilakukan Winbox. Berikut langkah-langkahnya. Buka jendela 'Bridge' kemudian klik tab 'Bridge'. Tekan tombol (+) dd untuk membuka dialog baru. Masukkan nama jembatan lokal lalu klik OK.

Klik tab 'Ports' lalu klik tombol (+). Nantinya ada jendela baru yang terbuka dan pilih Interface Ether2. Setelah itu pilih Local di bagian Bridge dan tekan OK.

Buka IP dan klik Addresses lalu masukkan tombol (+). Masukkan 192.168.88.1/24 dan pilih 'Local' di bagikan 'Interface'. Tekan 'OK'.

Setting Konfigurasi DHCP Server Setelah konfigurasi IP Address selesai, proses selanjutnya adalah mengatur konfigurasi DHCP Server DHCP. Caranya buka IP kemudian klik 'DHCP Server'. Setelah itu tekan tombol DHCP Set up untuk membuka jendela baru. Klik 'Lokal' pada 'Antarmuka Server DHCP' dan klik 'Berikutnya'.

Setting Konfigurasi Jaringan Internet Pada dasarnya sistem mikrotik bertujuan agar perangkat dapat mengakses jaringan Internet. Cara konfigurasinya bisa dengan membuka kategori segmen PPP dan klik tab Interfaces. Selanjutnya klik tombol (+) dan pilih 'PPPoE Client'. Klik 'Ether 1' dibagian 'Interfce' dan klik 'OK'.

Setelah semua konfigurasi berhasil, pengguna dapat mengakses Internet dari router. Lakukan verifikasi konektivitas IP yang diketahui dengan melakukan Ping ke Alamat IP yang server Google.

Buat Kata Sandi Apabila berhasil terhubung, buat kata sandi untuk meningkatkan keamanan minimal 12 karakter dengan angka, simbol, kapital, dan huruf kecil. Pastikan untuk mengingat kata sandi yang sudah dibuat. Sebab, jika lupa tak ada cara untuk memulihkannya. Pengguna perlu menginstal ulang router yang sudah dikonfigurasi.
