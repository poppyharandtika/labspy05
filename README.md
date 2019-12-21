![FLWCHRT 5 FIX-1](https://user-images.githubusercontent.com/56400553/71300900-4decb080-234e-11ea-9a22-f51fa072bb3e.jpg)

Di dalam praktikum 5 ini membahas tentang program sederhana yang akan menampilkan daftar nilai mahasiswa menggunakan Dictionary atau dict{}. Di bawah ini merupakan kode-kode program yang digunakan beserta output dan penjelasannya.

![image](https://user-images.githubusercontent.com/56400553/71300955-a623b280-234e-11ea-83e9-2bec3b831a4b.png)

•	Mendeklarasikan dictionary kosong dengan nama dictionary data = {}
•	Menginput salah satu menu yang tersedia ((L)ihat, (T)ambah, (U)bah, (H)apus, (C )ari, (K)eluar) yang menggunakan perulangan While True

Menu "Tambah Data"

![image](https://user-images.githubusercontent.com/56400553/71300974-d5d2ba80-234e-11ea-85d3-45734e6db895.png)

Untuk menu "Tambah Data" :
•	Menggunakan inputan t dan menggunakan kondisi if
•	Melanjutkan perintah di bawahnya yaitu menginput data (Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS).
•	Setelah itu, akan mengakses dictionary, nama sebagai key dan nama, NIM, tugas, uts, uas sebagai value.
•	Lalu akan mencetak dictionary, setelah data diinput.

Menu "Lihat Nilai"

![image](https://user-images.githubusercontent.com/56400553/71300986-fd298780-234e-11ea-80bd-f94f9580bd0a.png)

Untuk menu"Lihat Nilai" :
•	Menggunakan inputan l dan menggunakan kondisi elif
•	Menggunakan kondisi if dan else
•	Untuk kondisi if apabila sebelumnya sudah melakukan input pada menu "Tambah Data" lalu akan mencetak data dalam bentuk list yang menggunakan perulangan for x in data.values():
•	Tetapi, jika sebelumnya tidak melakukan input data, maka data tidak akan dicetak atau ditampilkan dan akan mencetak TIDAK ADA DATA yang menggunakan kondisi else.

Menu "Keluar"

![image](https://user-images.githubusercontent.com/56400553/71301013-2f3ae980-234f-11ea-8f46-34c1a18a6575.png)

Pada menu "Keluar" menggunakan inputan k dan fungsi pernyataan break, maka program akan berhenti atau keluar.

Menu "Hapus Data"

![image](https://user-images.githubusercontent.com/56400553/71301036-67dac300-234f-11ea-96ef-f8d7267ec551.png)

•	Menggunakan inputan h dan menggunakan kondisi if dan else
•	Menginput nama
•	Untuk kondisi if, kode yang digunakan if nama in data.keys(): dan del data[nama] yang akan menghapus data apabila data tersebut sudah diakses.
•	Dan sebaliknya, untuk kondisi else, maka data tidak berhasil dihapus karena data tidak tersedia atau tidak diinput

Menu "Ubah Data"

![image](https://user-images.githubusercontent.com/56400553/71301052-9c4e7f00-234f-11ea-9cdb-62cdde8a6ac2.png)

•	Menggunakan inputan u dan menggunakan kondisi if else
•	Menginput nama
•	Kondisi if akan menginput (NIM, Nilai Tugas, Nilai UTS, Nilai UAS) yang akan diubah dan data berhasil diubah
•	Kondisi else apabila data belum diakses, maka data tersebut tidak dapat diubah atau data tidak ada.

Menu "Cari Data"

![image](https://user-images.githubusercontent.com/56400553/71301065-c7d16980-234f-11ea-92db-ca9e2abb6df9.png)

•	Menggunakan inputan c dan menggunakan kondisi if else
•	Menginput nama
•	Apabila data tersebut sudah diakses, maka akan mencetak daftar nilai sesuai dengan nama yang dicari
•	Sedangkan, jika data tersebut tidak ada, maka tidak akan mencetak daftar nilai.

Kondisi Else

![image](https://user-images.githubusercontent.com/56400553/71301074-ec2d4600-234f-11ea-8a7e-f65d119c0eb7.png)

Perintah untuk memilih salah satu menu yang tersedia.
Contoh Output yang dihasilkan

![image](https://user-images.githubusercontent.com/56400553/71301082-09621480-2350-11ea-9f55-873ec9692327.png)


