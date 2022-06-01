# Tugas-6-SBD-TI-20-D1

<table>
  <tr>
    <td>Nama</td>
    <td>Deni Luqmantoro</td>
  </tr>
  <tr>
    <td>NIM</td>
    <td>312010071</td>
  </tr>
  <tr>
    <td>Kelas</td>
    <td>TI 20 D1</td>
  </tr>
  <tr>
    <td>Matkul</td>
    <td>Sistem Basis Data</td>
  </tr>
</table>

<b>Pertanyaan dan Tugas</b>
1. Masuk ke databse nama_nim!
![image](https://user-images.githubusercontent.com/101716699/171130388-dd1718b5-6437-4d43-93ac-51ff037b95ec.png)

2. Lakukan proses backup dan recovery dengan sql dari database tugas seblumnya!

  a. Proses Backup
  
   Melakukan proses penguncian/lock table.
  ![image](https://user-images.githubusercontent.com/101716699/171131230-c25aec8e-f2e1-44df-b0de-cf5c15b21232.png)

   Lakukan proses backup table dengan perintah : SELECT * INTO OUTFILE
  ![image](https://user-images.githubusercontent.com/101716699/171350402-e819db4e-d243-4c88-bae9-557a2f7450ad.png)
  
  Proses backup berhasil, dapat dibuktikan file backup ada pada direktori C:\xampp\mysql\data\denil_312010071
  ![image](https://user-images.githubusercontent.com/101716699/171351061-28486f78-d3f6-4383-b84a-d13fa8144f90.png)
  
  b. Proses Recovery/Restore
  
  Untuk membutikan bahwa proses berhasil langkah pertama yang harus dilakukan yaitu menghapus tabel deniluqmantoro_312010071, kemudian lihat hasilnya. jikas sudah       kosong berarti proses hapus berhasil.
  
  Kemudian lakukan recovery dengan sql seperti pada gambar dibawah ini, dan lihat lagi hasilnya.
  ![image](https://user-images.githubusercontent.com/101716699/171353174-12581744-f142-48f0-9abc-bbfb49152efc.png)
  




