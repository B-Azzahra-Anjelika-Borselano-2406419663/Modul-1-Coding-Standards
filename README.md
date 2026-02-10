Modul 1 - Coding Standards
Azzahra Anjelika Borselano
2406419663

# Reflection 1

_Prinsip Clean Code dan Secure Coding yang Diterapkan_

**1. Penggunaan nama yang jelas**
Saya menggunakan nama variabel, method, dan class yang deskriptif sehingga fungsinya dapat dipahami tanpa perlu komentar penjelasan.

**2. DRY – Don’t Repeat Yourself**
Untuk mengurangi redundansi, saya memanfaatkan kembali method yang sudah ada. Dengan cara ini, logika yang sama tidak ditulis berulang kali, sehingga kode menjadi lebih efisien.

**3. Penerapan Single Responsibility Principle**
Struktur aplikasi dibagi ke dalam beberapa layer, yaitu Controller, Service, dan Repository. Setiap class hanya memiliki satu tanggung jawab utama. Pemisahan ini membuat kode lebih terstruktur.

**4. Fungsi fokus pada satu tugas**
Setiap method dibuat sesederhana mungkin dan hanya menangani satu tujuan spesifik. Contohnya, method delete hanya bertugas untuk menghapus produk tanpa menangani logika lain di luar itu.

_Aspek yang Masih Perlu Dikembangkan_
Saat ini, input yang tidak valid seperti nama produk kosong atau jumlah bernilai negatif masih diterima oleh aplikasi. Untuk mengatasinya, perlu ditambahkan logika validasi pada model Product.