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
