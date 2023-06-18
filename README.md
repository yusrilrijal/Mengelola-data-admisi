# Kode di atas adalah implementasi program yang bertujuan untuk mengelola data mahasiswa dalam Program Admisi Prodi Sains Data

Pertama, terdapat kelas `Mahasiswa` yang memiliki atribut seperti `nim` (Nomor Induk Mahasiswa), `nama`, `jenis_kelamin`, dan `berkebutuhan_khusus`. Atribut `berkebutuhan_khusus` memiliki nilai default `False`, yang menandakan apakah mahasiswa tersebut memiliki kebutuhan khusus atau tidak.

Selanjutnya, terdapat kelas `ProgramAdmisi` yang memiliki atribut `mahasiswa` yang akan menampung objek-objek `Mahasiswa`. Kelas ini memiliki beberapa metode, antara lain:
- `tambah_mahasiswa(self, mahasiswa)`: Menambahkan objek `Mahasiswa` ke dalam daftar `mahasiswa`.
- `hapus_mahasiswa(self, nim)`: Menghapus objek `Mahasiswa` dari daftar `mahasiswa` berdasarkan NIM (Nomor Induk Mahasiswa) yang diberikan.
- `tampilkan_semua_mahasiswa(self)`: Menampilkan semua data mahasiswa yang terdapat dalam daftar `mahasiswa`.
- `tampilkan_mahasiswa_berkebutuhan_khusus(self)`: Menampilkan data mahasiswa yang memiliki kebutuhan khusus, yaitu yang memiliki atribut `berkebutuhan_khusus` bernilai `True`.

Kemudian, dilakukan pembuatan objek `program_admisi` dari kelas `ProgramAdmisi`. 

Selanjutnya, terdapat loop `while True` yang digunakan untuk menjalankan program secara terus-menerus sampai pengguna memilih untuk keluar (memilih opsi 5). Di dalam loop tersebut, pengguna diberikan opsi-opsi yang dapat dipilih, yaitu:
1. Tambah Data: Meminta pengguna untuk memasukkan data mahasiswa (NIM, nama, jenis kelamin, dan kebutuhan khusus) dan menambahkannya ke dalam daftar `mahasiswa`.
2. Hapus Data: Meminta pengguna untuk memasukkan NIM mahasiswa yang ingin dihapus, lalu menghapus mahasiswa dengan NIM tersebut dari daftar `mahasiswa`.
3. Tampilkan Semua Data: Menampilkan semua data mahasiswa yang terdapat dalam daftar `mahasiswa`.
4. Tampilkan Hanya penyandang disabilitas: Menampilkan data mahasiswa yang memiliki kebutuhan khusus.
5. Keluar: Menghentikan program dan keluar dari loop.

Kode di atas mengimplementasikan sistem sederhana untuk mengelola data mahasiswa dalam program admisi. Pengguna dapat menambahkan data mahasiswa, menghapus data mahasiswa berdasarkan NIM, serta menampilkan semua data mahasiswa atau hanya data mahasiswa dengan kebutuhan khusus.
