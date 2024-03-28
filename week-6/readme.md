<div align="center">
  <h1 style="text-align: center;font-weight: bold">Praktikum 4B<br>Sistem Operasi</h1>
  <h4 style="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h4>
</div>
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : </h3>
  <p style="text-align: center;">
    <strong>Fauzan Abderrasheed (3123500020) </strong><br>
    <strong>Muhammad Rafi Dhiyaulhaq (3123500004) </strong><br>
    <strong>Arva Zaki Fanadzan (3123500014)</strong>
  </p>
<h3 style="text-align: center;line-height: 1.5">Politeknik Elektronika Negeri Surabaya<br>Departemen Teknik Informatika Dan Komputer<br>Program Studi Teknik Informatika<br>2023/2024</h3>
  <hr><hr>
</div>

<h1 style="text-align: center;font-weight: bold">Proses dan Manajemen Proses</h1>

## Daftar isi
1. [Jawaban Tugas Pendahuluan](#tugas-pendahuluan)
2. [Laporan Hasil Percobaan](#percobaan)

### Percobaan 5 : Menghentikan dan Memulai Kembali Job

1. Instruksi `yes > /dev/null`

    ![App Screenshot](img/yes-dev-null-z.png)

    Analisa : 
    Cara lain meletakkan job pada background dengan memulai job secara normal (pada foreground), stop job dan memulai lagi pada background. Gunakan perintah `yes > /dev/null` untuk memulai job baru. Hentikan sementara job (suspend), bukan menghentikannya (terminate), tetapi menghentikan sementara job sampai di restart. Untuk menghentikan sementara job gunakan *Ctrl + Z*

2. Instruksi `fg`

    ![App Screenshot](img/fg.png)

    Analisa : 
     

3. Instruksi `bg`

    ![App Screenshot](img/bg.png)

    Analisa : 
     
    Instruksi `fg`

    ![App Screenshot](img/fg-2.png)

    Analisa : 
     

4. Instruksi `yes &`

    ![App Screenshot](img/yes-&.png)

    Analisa : 
     

5. Instruksi `fg %2`, `bg %2` atau `%2`

    ![App Screenshot](img/fg-bg-2.png)

    Analisa : 
     

6. Instruksi `fg`

    ![App Screenshot](img/fg-3.png)

    Analisa : 
     

7. Instruksi `ps -fae`

    ![App Screenshot](img/ps-fae.png)

    Analisa : 
     

8. Instruksi `kill -9 <Nomor PID>`

    ![App Screenshot](img/kill-9-PID.png)

    ![App Screenshot](img/killed-9-PID.png)

    Analisa : 
     


     