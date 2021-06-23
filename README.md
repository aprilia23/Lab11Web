Nama    : Aprilia Nur Sa'adah<p>
NIM     : 311910302<p>
Kelas   : TI.19.B1<p>
Mata Kuliah : Pemograman Web - Pratikum 11<p>

Untuk mengaktifkan ekstentsi tersebut, melalu XAMPP Control Panel, pada bagian
Apache klik Config -> PHP.ini <p>
![image](https://user-images.githubusercontent.com/54062259/121946364-0d24fa80-cd7f-11eb-8288-c27b69aa8162.png)

Pada bagian extention, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan. Kemudian simpan kembali filenya dan restart Apache web server.<p>
![image](https://user-images.githubusercontent.com/54062259/121946569-43fb1080-cd7f-11eb-904a-f675fba54f24.png)

Instalasi Codeigniter 4<p>
Unduh Codeigniter dari website https://codeigniter.com/download<p>
• Extrak file zip Codeigniter ke direktori htdocs/lab11_ci.<p>
• Ubah nama direktory framework-4.x.xx menjadi ci4.<p>
• Buka browser dengan alamat http://localhost/lab11_ci/ci4/public/<p>
![image](https://user-images.githubusercontent.com/54062259/121981499-f64eca00-cdb7-11eb-9f3d-9b561e203d3c.png)

  
Menjalankan CLI (Command Line Interface)<p>
![image](https://user-images.githubusercontent.com/54062259/121948578-99382180-cd81-11eb-897b-7a568f7194db.png)

![image](https://user-images.githubusercontent.com/54062259/121948665-b836b380-cd81-11eb-88e5-09ccfda3e4e2.png)

Mengaktifkan Mode Debugging<p>
![image](https://user-images.githubusercontent.com/54062259/121948925-16639680-cd82-11eb-9eec-46e2504cbe42.png)

Ubah nama file env menjadi .env kemudian buka file tersebut dan ubah nilai variable CI_ENVIRINMENT menjadi development.<p>
![image](https://user-images.githubusercontent.com/54062259/121949638-e5379600-cd82-11eb-84a7-90c9cc471dda.png)
  
Contoh error yang terjadi. Untuk mencoba error tersebut, ubah kode pada file app/Controller/Home.php hilangkan titik koma pada akhir kode.<p> 
![image](https://user-images.githubusercontent.com/54062259/121949569-cd601200-cd82-11eb-825f-fe7c6eee8331.png)

Routing dan Controller<p>
Membuat Route Baru.<p>
![image](https://user-images.githubusercontent.com/54062259/121949864-2e87e580-cd83-11eb-98d7-d8f46d8e3074.png)

Untuk mengetahui route yang ditambahkan sudah benar, buka CLI dan jalankan perintah berikut.<p>
![image](https://user-images.githubusercontent.com/54062259/121949963-49f2f080-cd83-11eb-8454-e7a99a29a1aa.png)

Membuat Controller<p>
![image](https://user-images.githubusercontent.com/54062259/121950570-0056d580-cd84-11eb-8767-9363593414c1.png)

![image](https://user-images.githubusercontent.com/54062259/121950839-56c41400-cd84-11eb-9073-53dea5a999fd.png)

Auto Routing<p>
![image](https://user-images.githubusercontent.com/54062259/121950692-2d0aed00-cd84-11eb-9ccb-afc27bb9e4c9.png)

![image](https://user-images.githubusercontent.com/54062259/121950769-42801700-cd84-11eb-8b56-a024d884d9f6.png)

Membuat View<p>
![image](https://user-images.githubusercontent.com/54062259/121951208-d3ef8900-cd84-11eb-8fc6-99835ff6bea8.png)

![image](https://user-images.githubusercontent.com/54062259/121951232-db169700-cd84-11eb-81ec-5e524efd6fcc.png)

![image](https://user-images.githubusercontent.com/54062259/121951298-f2ee1b00-cd84-11eb-98ff-14faa617bfa0.png)

Membuat Layout Web dengan CSS<p>
File app/view/template/header.php<p>
![image](https://user-images.githubusercontent.com/54062259/121980327-ef26bc80-cdb5-11eb-8719-ebadc28c42ab.png)

File app/view/template/footer.php<p>
![image](https://user-images.githubusercontent.com/54062259/121980349-fa79e800-cdb5-11eb-92e9-ebc3bc8dba0f.png)

Kemudian ubah file app/view/about.php seperti berikut.<p>
![image](https://user-images.githubusercontent.com/54062259/121980388-06fe4080-cdb6-11eb-83a1-e07a65659d93.png)

![image](https://user-images.githubusercontent.com/54062259/121980453-285f2c80-cdb6-11eb-906a-7921d14b9e50.png)

Pertanyaan dan Tugas
Lengkapi kode program untuk menu lainnya yang ada pada Controller Page, sehinggasemua link pada navigasi header dapat menampilkan tampilan dengan layout yang sama.<p>
![image](https://user-images.githubusercontent.com/54062259/121980883-f00c1e00-cdb6-11eb-8a99-c95a0a1b7f94.png)

![image](https://user-images.githubusercontent.com/54062259/121981042-35c8e680-cdb7-11eb-9a13-70d22a6c51dc.png)

![image](https://user-images.githubusercontent.com/54062259/121981076-44170280-cdb7-11eb-9974-f1a053f42b1a.png)

![image](https://user-images.githubusercontent.com/54062259/121981117-51cc8800-cdb7-11eb-8d0c-0a8d2337dc83.png)


Praktikum 12: Framework Lanjutan (CRUD) <p>
Membuat Database: Studi Kasus Data Artikel<p>
Membuat Database<p>
![image](https://user-images.githubusercontent.com/54062259/122664701-3b666800-d1cd-11eb-9f4d-4fee802c897f.png)

Membuat Tabel<p>
![image](https://user-images.githubusercontent.com/54062259/122664708-47eac080-d1cd-11eb-87e8-e12cb50cb817.png)
 
Konfigurasi koneksi database
![image](https://user-images.githubusercontent.com/54062259/122664739-68b31600-d1cd-11eb-8b6d-b1c5b817eaae.png)

Membuat Model
![image](https://user-images.githubusercontent.com/54062259/122664786-a31cb300-d1cd-11eb-8d3d-8aa52f9eda0b.png)

Membuat Controller
![image](https://user-images.githubusercontent.com/54062259/122664812-cf383400-d1cd-11eb-949d-f7ad73638224.png)

Membuat View
![image](https://user-images.githubusercontent.com/54062259/122664873-22aa8200-d1ce-11eb-95d7-0cc56d5df1d5.png)

Menyisipkan Text 
![image](https://user-images.githubusercontent.com/54062259/122664970-bd0ac580-d1ce-11eb-84a1-492a31ef04bc.png)

![image](https://user-images.githubusercontent.com/54062259/122665057-47ebc000-d1cf-11eb-959f-fb50f75b39db.png)

Membuat Tampilan Detail Artikel
![image](https://user-images.githubusercontent.com/54062259/122665095-82edf380-d1cf-11eb-8847-1193684e2242.png)

Membuat View Detail
![image](https://user-images.githubusercontent.com/54062259/122665172-e7a94e00-d1cf-11eb-9a39-ac83f280918e.png)

Membuat Routing untuk artikel detail
![image](https://user-images.githubusercontent.com/54062259/122665183-fb54b480-d1cf-11eb-9012-6a33e24121b5.png)

![image](https://user-images.githubusercontent.com/54062259/122665197-10314800-d1d0-11eb-9993-7352016851cf.png)

Membuat Menu Admin
![image](https://user-images.githubusercontent.com/54062259/122665229-38b94200-d1d0-11eb-83cb-38dbaf4537fd.png)

Selanjutnya buat view untuk tampilan admin dengan nama admin_index.php
![image](https://user-images.githubusercontent.com/54062259/122665319-bbda9800-d1d0-11eb-9c64-833ae0745757.png)

Tambahkan routing untuk menu admin seperti berikut:
![image](https://user-images.githubusercontent.com/54062259/122665363-f04e5400-d1d0-11eb-8651-3ea2a6a18ed0.png)

![image](https://user-images.githubusercontent.com/54062259/122665375-05c37e00-d1d1-11eb-9d9c-d43720708714.png)

Menambah Data Artikel
![image](https://user-images.githubusercontent.com/54062259/122665395-28559700-d1d1-11eb-8768-18966029fa46.png)

Kemudian buat view untuk form tambah dengan nama form_add.php
![image](https://user-images.githubusercontent.com/54062259/122665431-5935cc00-d1d1-11eb-816f-5eea4896b36f.png)

![image](https://user-images.githubusercontent.com/54062259/122665436-62269d80-d1d1-11eb-9ae9-dd1ac88b2a51.png)

Mengubah Data
![image](https://user-images.githubusercontent.com/54062259/122665459-85e9e380-d1d1-11eb-8643-ff6637da5355.png)

Kemudian buat view untuk form tambah dengan nama form_edit.php
 ![image](https://user-images.githubusercontent.com/54062259/122665479-ac0f8380-d1d1-11eb-8a9a-a1a1b345c072.png)

 ![image](https://user-images.githubusercontent.com/54062259/122665487-b5005500-d1d1-11eb-86b4-cd44e3ad7ac9.png)

Menghapus Data
![image](https://user-images.githubusercontent.com/54062259/122665499-c9dce880-d1d1-11eb-8120-ceefc34377ec.png)

Pertanyaan dan Tugas<p>
Selesaikan programnya sesuai Langkah-langkah yang ada. Anda boleh melakukan improvisasi.<p>

Admin_header.php
![image](https://user-images.githubusercontent.com/54062259/122665654-aebea880-d1d2-11eb-9bc3-096c4bd5890d.png)

Admin_footer.php
![image](https://user-images.githubusercontent.com/54062259/122665693-ed546300-d1d2-11eb-8f2d-21618cc71e7c.png)

Menambahkan Artikel Baru
![image](https://user-images.githubusercontent.com/54062259/122665711-03622380-d1d3-11eb-8495-291e60408d3a.png)

![image](https://user-images.githubusercontent.com/54062259/122665718-0bba5e80-d1d3-11eb-9eef-6bd8f59d19e2.png)

Menghapus Artikel
![image](https://user-images.githubusercontent.com/54062259/122665721-196fe400-d1d3-11eb-80ac-1bee57986bce.png)

![image](https://user-images.githubusercontent.com/54062259/122665724-2391e280-d1d3-11eb-83b1-dafbb0e516d8.png)

Mengedit Artikel
![image](https://user-images.githubusercontent.com/54062259/122665733-2ee50e00-d1d3-11eb-8d38-8700936da4e9.png)

![image](https://user-images.githubusercontent.com/54062259/122665738-36a4b280-d1d3-11eb-981d-a13ec31f73ff.png)

Praktikum 13: Framework Lanjutan (Modul Login)<P>
Membuat Tabel: User Login<P>
![image](https://user-images.githubusercontent.com/54062259/123025575-fe84b600-d404-11eb-8809-06d37fa491b4.png)

Membuat Model User
![image](https://user-images.githubusercontent.com/54062259/123025666-296f0a00-d405-11eb-8877-ecfbc1de0d62.png)

Membuat Controller User
![image](https://user-images.githubusercontent.com/54062259/123026080-ca5dc500-d405-11eb-8140-c3fc58bf5371.png)

Membuat View Login
![image](https://user-images.githubusercontent.com/54062259/123026319-245e8a80-d406-11eb-92ae-3550f0c9d47f.png)

Membuat Database Seeder
