# Praktikum8
## $${\color{blue}OOP (Objek Oriented Programming)}$$

## Profil
| Variable | Isi |
| -------- | --- |
| *Nama* | Muhammad Iqbal Al Anshori  |
| *NIM* |  312310659 |
| *Kelas* | TI.23.A.6 |
| *Mata Kuliah* | Bahasa Pemrograman |

# $${\color{blue}PYTHON}$$

![gambar](Screenshot/ss1.png)

# Menambah Data
![gambar](Screenshot/TambahData.png)

# Menampilkan Data
![gambar](Screenshot/LihatData.png)

# Menghapus Data
![gambar](Screenshot/HapusData.png)

# Mengubah Data
![gambar](Screenshot/UbahData.png)

# Diagram Class
![gambar](Screenshot/DiagramKelas.jpg)

# Flowchart
![gambar](Screenshot/Flowchart.jpg)

### Penjelasannya : 

Program kita kali ini akan menggunakan sistem OOP(Object-Oriented Programming), apa itu OOP?
OOP(Object-Oriented Programming) merupakan sebuah cara untuk membangun sebuah aplikasi dengan memandang sebagai presentasi objek-objek yang saling mendukung serta berinteraksi dari satu objek ke objek yang lainnya, dan dapat dikatakan code program akan terbentuk berkelompok berdasarkan objek. 
Fungsi secara singkat yakni meringkas sebuah program yang berulang-ulang dengan menggunakan syntaks def nama_fungsi(argument). def diartikan sebagai definisi.

1. Kita akan mendeklarasikan atau menginput sebuah variabel bertipe data dictionary kosong data={} yang nantinya akan kita inputkan sebuah data yang terdiri dari: nama, nim, nilai_tugas, nilai_uts, nilai_uas dan nilai_akhir.

2. kita membuat class `data_mahasiswa()`

3. Membuat fungsi
    * Fungsi tambah(), untuk menambahkan data def tambah()
    * Fungsi tampilkan(), untuk menampilkan data def tampilkan()
    * Fungsi hapus(nama), untuk menghapus nama pada data def hapus(nama)
    * Fungsi ubah(nama), untuk mengubah nama pada data def ubah(nama)
    * Fungsi salah(), untuk inputan yang tidak sesuai perintah def salah()

4. Menggunakan Perulangan while (while loop)
while True:, dapat diartikan perulangan akan terus mengulang jika inputan benar dan masuk kedalam proses jika tidak maka perulangan berhenti atau lanjut ke proses selanjutnya. 
variabel lanjut kita gunakan untuk menginput perintah yang akan kita proses lanjut=input(str('(L)ihat, (T)ambah, (U)bah, (H)apus, (K)eluar)), disini kita menggunakan statement if untuk memproses perintah yang di inginkan sesuai inputan pada variabel lanjut:
    ```python
     if lanjut.lower() == 'l':

        if data.items():

        tampilkan()

        else:

        salah()

    * if lanjut.lower() == 't':

        tambah()

    * if lanjut.lower() == 'h':

        nama = input(str('Nama\t: '))

        if nama in data.items():

        hapus(nama)

        else:

        salah()

    * if lanjut.lower == 'u':

        nama = input(str('Nama\t: '))

        if nama in data.items():

        ubah(nama)

        else:

        salah()
    ```
