# BD_Praktikum3
```
1. Lakukan penambahan data pada tabel mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen. 
2. Hapus satu record dat pada tabel dosen yang telah dirujuk pada tabel mahasiswa. 
3. Ubah mode menjadi ON UPDATE CASCADE ON DELETE RESTRICT. 
4. Lakukan perubahan data pada tabel dosen (kd_ds). 
5. Lakukan penghapusan data pada tabel dosen. 
6. Ubah mode menjadi ON UPDATE CASCADE ON DELETE SET NULL.
7. Lakukan penghapusan data pada tabel dosen.
```
1. Lakukan penambahan data pada tabel mahasiswa dengan mengisi kd_ds yang belum ada pada data dosen
![image](https://github.com/RadjaAzukio/BD_Praktikum3/assets/115551911/ef5e10a7-415c-4d1a-87ea-7f0148bca02c)
![image](https://github.com/RadjaAzukio/BD_Praktikum3/assets/115551911/fdcc86aa-7108-4065-9bfc-c89b0072642c)
![image](https://github.com/RadjaAzukio/BD_Praktikum3/assets/115551911/b8bea4ed-223e-43de-b3e3-8c24ae568fdc)

2. Hapus satu record dat pada tabel dosen yang telah dirujuk pada tabel mahasiswa
![image](https://github.com/RadjaAzukio/BD_Praktikum3/assets/115551911/1a6608f8-497c-451a-97de-136c59bcdb1d)

3. Ubah mode menjadi ON UPDATE CASCADE ON DELETE RESTRICT
![image](https://github.com/RadjaAzukio/BD_Praktikum3/assets/115551911/ea5444b6-da7e-43ec-9b6f-3a837ac8fa7b)

4. Lakukan perubahan data pada tabel dosen (kd_ds)
![image](https://github.com/RadjaAzukio/BD_Praktikum3/assets/115551911/7f3fea68-df12-4b68-8858-5b9c815e3139)

5. Lakukan penghapusan data pada tabel dosen 
![image](https://github.com/RadjaAzukio/BD_Praktikum3/assets/115551911/01973ea9-62b0-45fc-871e-d697c19404f3)

6. Ubah mode menjadi ON UPDATE CASCADE ON DELETE SET NULL
![image](https://github.com/RadjaAzukio/BD_Praktikum3/assets/115551911/6f9edbee-7897-4bce-a05f-28b3a6108b60)

7. Lakukan penghapusan data pada tabel dosen
![image](https://github.com/RadjaAzukio/BD_Praktikum3/assets/115551911/35979de6-cccf-407f-a70e-fe323a2c06dc)

### Evaluasi dan Pertanyaan
```
1. Apa bedanya pengguna RESTRICT dan CASCADE ?
```
- Penggunaan RESTRICT dan CASCADE adalah dua jenis aturan referential integrity (keutuhan referensial) yang dapat diterapkan pada kunci asing (foreign key) di basis data relasional.
- Penggunaan RESTRICT dan CASCADE adalah dua jenis aturan referential integrity (keutuhan referensial) yang dapat diterapkan pada kunci asing (foreign key) di basis data relasional.
- Jika ada, maka sistem basis data akan mencegah penghapusan atau perubahan data pada baris data di tabel induk yang berdampak pada baris data di tabel anak yang masih merujuk ke baris data tersebut.
- Sementara itu, CASCADE adalah sebuah baris data di tabel induk dihapus atau diubah, maka sistem basis data akan secara otomatis menghapus atau mengubah baris data di tabel anak yang merujuk ke baris data yang dihapus atau diubah tersebut.
```
2. Berikan kesimpulan
```
- RESTRICT dan CASCADE adalah aturan refential intrgrity Yang dapat diterapkan pada kunci asing yang basis data relasional. RESTRICT mencegah penghapusan atau perubahan data pada tabel induk yang berdampak pada tabel anak yang masih merujuk ke data yang di hapus atau di ubah.
- Sementara CASCADE dengan secara otomatis menghapus atau mengubah data pada tabel anak yang merujuk ke data yang di apus atau di ubah pada tabel induk.
- Kedua aturan tersebut memiliki kelebihan dan kekurangan masing-masing dan harus dipilih secara bijak sesuai dengan kebutuhan dan konteks penggunaannya agar dapat memastikan keutuhan data didalam sistem basis data.
