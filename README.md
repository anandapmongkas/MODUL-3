##### Nama: Ananda Pratama Hadi Pamungkas
##### Kelas: XII RPL 1
##### No: 13

Sesudah melihat modul ke 1&2 Kita Memberi MODUL Ke 3
```
https://github.com/anandapmongkas/Test_readme/blob/main/README.md
```
Langkah Pertama cari folder web.php seperti di bawah ini:

![image](https://user-images.githubusercontent.com/109930488/182099301-78ca941e-db26-41e8-91de-ca9c83017720.png)

# MODUL 3
### Selanjutnya kita akan membuat Route yang akan menuju ke halaman kategori 
```
<?php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class KategoriControllers extends Controller
{
   public function home()
   {
    return 'Mengakses Fungsi di controllers menggunakan route';
   }

   public function add()
   {
    return 'Mengakses halaman tambah data di setiap route Kategoricontroller';
   }
}
```
Tampilan seperti di bawah:

![image](https://user-images.githubusercontent.com/109930488/182098450-84f65939-4877-4ab1-9523-c6499213957e.png)

Lalu Membuat folder kategoricontroller dibawah ini:

*Saran menggunakan fitur terminal diVSCODE
```
php artisan make:controller kategoricontroller
```
hasilnya:

![image](https://user-images.githubusercontent.com/109930488/182105457-64a440dc-f792-48d7-875c-84d7025eef54.png)

Hasilnya ada difolder App/Http/Controller:

![image](https://user-images.githubusercontent.com/109930488/182265718-8ff256b6-bdf0-427c-89ed-80e8ef93f83a.png)

Lalu ubah script seperti ini:
```
<?php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class KategoriControllers extends Controller
{
   public function home()
   {
    return 'Mengakses Fungsi di controllers menggunakan route';
   }

   public function add()
   {
    return 'Mengakses halaman tambah data di setiap route Kategoricontroller';
   }
}
```
 #### CONTOH GAMBAR:
 
 ![image](https://user-images.githubusercontent.com/109930488/182265877-c2c46b29-c5b1-4a20-8d53-09b1535693ca.png)

Lalu untuk cek project yang kita buat buka fitur terminal VSCODE:
```
php artisan serve
```
![image](https://user-images.githubusercontent.com/109930488/182266030-207dc249-5896-45dd-a5f6-20a45c285548.png)

Hasilnya

![image](https://user-images.githubusercontent.com/109930488/182266105-7ba5d265-e7bf-4e43-9d2e-91ebafbc3c78.png)

Lalu Salin Dan Search dicrome/google
```
http://127.0.0.1:8000
```

![image](https://user-images.githubusercontent.com/109930488/182266410-beb34792-42d2-48a5-aea2-f2c4a109de5b.png)

Jika memanggil Route yang kita buat hasil dari search tambahkan dengan nama route sebagai berikut:

![image](https://user-images.githubusercontent.com/109930488/182266700-ce888410-17aa-4bcd-9812-0fecb6bcacd5.png)
