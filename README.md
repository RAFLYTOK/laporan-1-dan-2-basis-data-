# laporan-1-dan-2-basis-data-

#### Rafly mahardika
#### XI RPL 2 
#### 29 

### MODUL 1

#### 1.Instal xampp
![Screenshot_2](https://user-images.githubusercontent.com/113566098/190309632-d02ea1d3-d8ee-4189-a370-dfde831afcf5.png)


#### 2.Nyalakan my sql di xampp
![Screenshot_3](https://user-images.githubusercontent.com/113566098/190309997-7ab809ff-a4e3-4220-b54a-9e9dad8ffeb2.png)

#### 3.Buka cmd min 
![Screenshot_4](https://user-images.githubusercontent.com/113566098/190310462-4ce8dd7a-1a1a-4817-9fc7-e1cb23c3487c.png)

#### 4.masuk ke direktori mysql dan tuliskan sintaks berikut  
```
cd xampp/mysql/bin
```

#### 5. tuliskan sintaks 
```
\xampp\mysql\bin>mysql -u root
Welcome to the MariaDB monitor.  Commands end with ; or \g.
Your MariaDB connection id is 17
Server version: 10.4.24-MariaDB mariadb.org binary distribution

Copyright (c) 2000, 2018, Oracle, MariaDB Corporation Ab and others.

Type 'help;' or '\h' for help. Type '\c' to clear the current input statement. 
```
#### Tanda sudah query



## Modul part 2

#### 1.Melihat show database dan tabel dengan kode berikut 
```
MariaDB [(none)]> show databases;
+--------------------+
| Database           |
+--------------------+
| db_basis_data      |
| information_schema |
| mahasiswa          |
| mysql              |
| penjualan          |
| performance_schema |
| phpmyadmin         |
| sekolah            |
| test               |
+--------------------+
9 rows in set (0.001 sec)

MariaDB [(none)]> use mahasiswa ;
Database changed
MariaDB [mahasiswa]> show tables;
+---------------------+
| Tables_in_mahasiswa |
+---------------------+
| dosen               |
| mahasiswa           |
| nilai               |
| siswa               |
+---------------------+
```

#### 2.Menggunakan use dalam cmd 
```
MariaDB [(none)]> use mahasiswa ;
Database changed
```

#### 3.Menggunakan create dan mendambahkan database dan tabel baru 
```
create table dosen( nim int not null, nama char(20),wali int);
```

![Screenshot_7](https://user-images.githubusercontent.com/113566098/190316865-3bb0c121-b1bf-4f59-b96b-2d73b330b948.png)


```
create database mahasiswa;
+--------------------+
| Database           |
+--------------------+
| db_basis_data      |
| information_schema |
| mahasiswa          |
| mysql              |
| penjualan          |
| performance_schema |
| phpmyadmin         |
| sekolah            |
| test               |
+--------------------+
```

#### 4. DESC untuk melihat metadata 
```
desc dosen;
``` 
##### Dan hasil output 
![Screenshot_7](https://user-images.githubusercontent.com/113566098/190316152-1a725e83-ed27-4445-962e-cedf7e219f6b.png)

## Laporan tugas 
 #### membuat database dan tabel 
 
 #### Sebelum itu buatlah 
 ```
 Create database mahasiswa 
 ```
 #### Dan 
 ```
 create table dosen( nim int not null, nama char(20),wali int);
 ```
 ![Screenshot_10](https://user-images.githubusercontent.com/113566098/190317602-b7826561-cbd6-4c79-a66e-debaa54e5c50.png)






