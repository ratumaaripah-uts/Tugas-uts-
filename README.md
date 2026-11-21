# Resume Materi Python OOP

## 1. Class dan Object

Dalam Python, class adalah cetakan atau rancangan untuk membuat object. Class bisa dibayangkan seperti cetakan kue. Dari satu cetakan, kita dapat membuat beberapa kue dengan bentuk yang sama.

Sedangkan object adalah hasil yang dibuat dari class tersebut. Setiap object memiliki susunan data dan fungsi yang sama, tetapi isi datanya bisa berbeda.

Contohnya, dari class `Mahasiswa` kita bisa membuat object bernama `Ratu` dan `Jeni`. Keduanya sama-sama Mahasiswa, tetapi nama, jurusan, dan semesternya bisa berbeda.

## 2. Attributes

Attribute adalah variabel yang digunakan untuk menyimpan data di dalam object. Misalnya, pada class `Mahasiswa`, atributnya dapat berupa `nama`, `jurusan`, dan `semester`.

Nilai atribut bisa berbeda pada setiap object. Jadi, object Ratu dapat memiliki jurusan Sistem Informasi, sedangkan object Jeni memiliki jurusan Ilmu Komputer.

## 3. Class Attribute

Class attribute adalah atribut yang ditulis di dalam class dan menjadi nilai bawaan yang dapat digunakan bersama oleh object-object dari class tersebut.

Berbeda dengan instance attribute yang nilainya dimiliki masing-masing object, class attribute berada pada tingkat class. Contohnya, jika semua mahasiswa memiliki nama kampus yang sama, informasi tersebut dapat dijadikan class attribute.

## 4. Methods

Method adalah fungsi yang ditulis di dalam class. Method digunakan untuk menjelaskan tindakan atau hal yang dapat dilakukan oleh object.

Contohnya, pada class `Mahasiswa` terdapat method `perkenalan()` untuk memperkenalkan diri dan method `bicara()` untuk menampilkan kalimat percakapan.

## 5. Parameter self

`self` adalah parameter khusus yang digunakan di dalam method untuk merujuk pada object yang sedang menjalankan method tersebut.

Dengan `self`, method dapat mengambil atau menggunakan atribut milik object itu sendiri. Misalnya, `self.nama` digunakan untuk mengambil nama dari object yang sedang memanggil method.

## 6. Method dengan Parameters

Method juga dapat menerima parameter tambahan selain `self`. Parameter tambahan ini berguna ketika method membutuhkan data dari luar.

Contohnya, method `bicara(self, kalimat)` memiliki parameter `kalimat`. Saat method dipanggil, kita bisa memberikan kalimat yang ingin ditampilkan.

## 7. Naming Conventions

Naming conventions adalah aturan penulisan nama agar kode lebih mudah dibaca dan dipahami. Dalam materi ini, aturan penamaannya adalah:

* Nama class: menggunakan PascalCase, contohnya `Mahasiswa`, `MataPelajaran`, dan `KategoriBarang`.
* Nama method: menggunakan snake_case, contohnya `perkenalan()`, `lari_ke_depan()`, dan `jalankan()`.
* Nama attribute: menggunakan snake_case, contohnya `nama_depan` dan `nama_belakang`.

## Kesimpulan

Class dan object membantu kita menyusun program agar lebih teratur. Dengan satu class, kita dapat membuat beberapa object yang memiliki atribut dan method dengan struktur sama, tetapi data masing-masing object bisa berbeda. Penggunaan attribute, method, `self`, dan aturan penamaan membuat kode lebih mudah dipahami dan digunakan kembali.
