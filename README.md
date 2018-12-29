# Unique-ID-Maker

# Deskripsi
Unique ID Maker v.1 adalah suatu program yang berfungsi sebagai sebuah generator atau pembuat username. Dengan memasukkan sebuah nama sesuai keinginan pengguna, Unique ID Maker v.1 akan membuat username secara acak dan menghasilkan username yang berbeda setiap saat digunakan. Fitur-fitur yang terdapat di dalam program ini adalah antara lain pembuatan username unik setiap saat, penyimpanan data nama dan username yang telah dibuat, serta penghapusan data username yang telah dibuat dengan menggunakan menu administrator yang telah dilengkapi dengan kata sandi yang dapat diubah sesuai keinginan.
	
# Cara Kerja	
Program ini dibuat dengan menggunakan bahasa C dan menggunakan dasar prinsip linked list. Username yang dibuat pada program ini terdiri dari tiga elemen yaitu sebuah kata asal di depan, nama yang dimasukkan oleh pengguna di tengah, dan waktu lokal komputer untuk empat digit angka di akhir. Kata asal yang terdapat di depan username ditentukan oleh angka apa yang dihasilkan oleh metode srand program yang akan memilih sebuah angka antara 1 hingga 100. Angka 0-10 menjadi "xx", 11-20 menjadi "bob", 21-30 menjadi "pop", 31-40 menjadi "the", 41-50 menjadi "mo", 51-60 menjadi "my", dan angka diatas 60 akan menjadi "our". Empat digit angka diakhir username diambil dari menit dan detik jam komputer yang sedang digunakan. Username yang sudah dihasilkan oleh program ini akan disimpan pada sebuah file .txt dan akan tetap sama hingga pengguna menghapus daftar username dari menu administator. Menu tersebut akan memampangkan nama-nama yang sudah dimasukkan dan username yang bersangkutan.

