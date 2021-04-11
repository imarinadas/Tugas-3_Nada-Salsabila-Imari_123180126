Tugas 3
Praktikum Teknologi dan Pemrograman Mobile
Kelas C / 123180126 / Nada Salsabila Imari

Pada tugas 3, saya membuat recylclerview dengan ditambah implementasi intent untuk data-data album musik.
Implementasi intent yang digunakan ada dua, yaitu share dan detail.

Implementasi intent share dapat membagikan informasi item-item terpilih dalam data-data album musik melalui aplikasi berbagi pesan seperti email, dengan menggunakan Intent.ACTION_SEND.

Implementasi intent detail ditujukan untuk berpindah ke activity detail sehingga dapat menampilkan detail dari data-data album musik di halaman baru. Namun, dalam penerapan intent detail belum berhasil. Berdasarkan pesan error di aplikasi Android Studio, terbaca NullPointerException pada activity detail. Kemungkinan, data-data album dari activity sebelumnya, belum berhasil dibaca oleh activity detail.
