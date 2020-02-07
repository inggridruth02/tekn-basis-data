# tekn-basis-data
# latihan2
1. create database.
Membuat database dengan nama inggridDB
![create database](db1.png)
2. SHOW DATABASES.
Menampilkan database
![show](db2.png)
3. CREATE TABLE.
```CREATE TABLE pelanggan (
   id VARCHAR (2) NOT NULL,
   nama VARCHAR (30) NOT NULL,
   alamat VARCHAR (30) NOT NULL,
   bagian VARCHAR (2) NOT NULL,
   PRIMARY KEY (id));```
   Membuat tabel pelanggan 
   (db3.png)
4. desc.
   menampilkan isi tabel
   ![menampilkan](db4.png)
5. ```CREATE TABLE movies (
    -> movies VARCHAR (30) NOT NULL PRIMARY KEY,
    -> id VARCHAR (2) NOT NULL,
    -> FOREIGN KEY (id) REFERENCES pelanggan (id));```
    ![show](db5.png)
6. desc movies.
menampilkan isi tabel movie
![desc](db6.png)
7. Insert query.
menambah data kedalam tabel
![insert](db7.png)
8.SELECT.
Menggunakan perintah Select tabel
Memilih kolom dari tabel yang ingin ditampilkan
![select](db8.png)
9.Menampilkan id, nama dari tabel pelanggan dan movies dari movies.
![show](db9.png)

