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
