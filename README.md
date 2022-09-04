# note-app-back-end

Project ini adalah RESTful API untuk aplikasi catatan sederhana. 
Di mana aplikasi tersebut berfungsi untuk menyimpan (create), melihat (read), mengubah (update), dan menghapus (delete) catatan.
Fungsionalitas ini dikenal sebagai operasi CRUD.

Berkas dan code yang ditulis;

server.js : Memuat kode untuk membuat, mengonfigurasi, dan menjalankan server HTTP menggunakan Hapi.
routes.js : Memuat kode konfigurasi routing server seperti menentukan path, method, dan handler yang digunakan.
handler.js : Memuat seluruh fungsi-fungsi handler yang digunakan pada berkas routes.
notes.js : Memuat data notes yang disimpan dalam bentuk array objek.

Semua berkas JavaScript disimpan di dalam folder src. Hal ini bertujuan agar terpisah dari berkas konfigurasi proyek seperti
.eslintrc.json, package.json, package-lock.json, dan node_modules.
