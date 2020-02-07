# tekn-basis-data
# latihan2
1. create database 
Membuat database dengan nama inggridDB
![create database](C:\Users\hp\Documents\tekn-basis-data\minggu1\db1.png)
2. SHOW DATABASES
Menampilkan database
(C:\Users\hp\Documents\tekn-basis-data\minggu1\db2.png)
3.CREATE TABLE
CREATE TABLE pelanggan (
   id VARCHAR (2) NOT NULL,
   nama VARCHAR (30) NOT NULL,
   alamat VARCHAR (30) NOT NULL,
   bagian VARCHAR (2) NOT NULL,
   PRIMARY KEY (id));

Membuat tabel pelanggan 
(C:\Users\hp\Documents\tekn-basis-data\minggu1\db3.png)
4.desc
menampilkan isi tabel
(C:\Users\hp\Documents\tekn-basis-data\minggu1\db4.png)
5.CREATE TABLE movies (
    -> movies VARCHAR (30) NOT NULL PRIMARY KEY,
    -> id VARCHAR (2) NOT NULL,
    -> FOREIGN KEY (id) REFERENCES pelanggan (id));
    (C:\Users\hp\Documents\tekn-basis-data\minggu1\db5.png)
6.desc movies
menampilkan isi tabel movie
(C:\Users\hp\Documents\tekn-basis-data\minggu1\db6.png)
7.	Insert query
menambah data kedalam tabel
(C:\Users\hp\Documents\tekn-basis-data\minggu1\db7.png)
8.SELECT
Menggunakan perintah Select tabel
Memilih kolom dari tabel yang ingin ditampilkan
(C:\Users\hp\Documents\tekn-basis-data\minggu1\db8.png)
9.Menampilkan id, nama dari tabel pelanggan dan movies dari movies.
(C:\Users\hp\Documents\tekn-basis-data\minggu1\db9.png)

