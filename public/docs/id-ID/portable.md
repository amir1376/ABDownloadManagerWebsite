## Bagaimana cara membuat aplikasi menjadi portable (Kustomisasi Folder Konfig)

Secara bawaan, aplikasi menyimpan file-file konfigurasinya di:

`~/.abdm`

Kamu punya dua cara untuk mengubah ini:

### Opsi 1: Gunakan sebuah folder lokal `.abdm`

Buat sebuah folder bernama `.abdm` di dalam folder pemasangan aplikasi. 

Setelah folder ini ada, aplikasi akan secara otomatis menggunakannya sebagai folder konfig dibandingkan lokasi bawaan.

### Opsi 2: Gunakan sebuah file `.portable`

Buat sebuah file bernama `.portable` di dalam folder pemasangan aplikasi. 

Di dalam file ini, tulis path penuh dari folder yang ingin kamu gunakan sebagai folder konfig.

Aplikasi akan membaca file ini dan menggunakan path yang ditentukan untuk menyimpan data konfigurasi.
