                                          APLIKASI JAVA GUI CRUD TENTANGG MATA KULIAH 
                                          -------------------------------------------

1. 	Pertama-tama, buat class non-main dengan nama sesuai keinginan. Didalam class tersebut akan diisi dengan method-method yang menjadi pendukung bagi class Java Swing
2. 	Setelah itu, buat class baru dengan tipe JFrameForm, lalu buat struktur tampilan GUI sebagai tampilan output saat class Java Swing dijalankan. Contohnya seperti berikut:

      ![image](https://github.com/user-attachments/assets/b1e987a7-8d88-424b-a698-a9883ba778af)


3.  Langkah selanjutnya, buat inisialisasi dengan menggunakan ‘DriverManager.getConnection()’ untuk koneksi database. Lalu membuat objek ‘PreparedStatement’ dan ‘ResultSet’ untuk menjalankan operasi database. 
4. 	Setelah itu masuk pada pembuatan CRUD. Buat method-method 'Insert' untuk memasukkan dan menyimpan data yang diinginkan.
5.  Kemudian, buat method Update untuk memperbaharui data yang telah diinput dan disimpan.
6. 	Langkah selanjutnya, buat method 'Delete' untuk menghapus data baik yang telah disimpan maupun diupdate.
7.  Setelah itu kita buat 'Clear', fungsinya adalah untuk membersihkan textfield sehingga proses input data lebih cepat. 
8.  Lalu pindah ke laman "Design" pada class terkait, klik kanan pada area tabel. Kemudian pilih events >>> Mouse >>> mouseClicked
9.  Fungsi dari mouseClicked sendiri adalah untuk menangkap events atau kejadian yang terjadi saat mouse ditekan. Contoh saat mengklik Insert, maka program akan menangkap maksud pengguna untuk Insert dsb.
10. Terakhir, kita buat method 'Tampil' untuk menampilkan data dari database atau yang sudah kita input sebelumnya kedalam tabel GUI
11. Dan hasilnya akan terlihat seperti ini,

     A. INSERT
    -------------

    ![image](https://github.com/user-attachments/assets/27104326-f52c-4d95-b018-b5c2557e92ec)


    B. UPDATE
    ------------

    ![image](https://github.com/user-attachments/assets/b108ed5c-fb0f-43e9-b142-6ddb9ada38e8)


    C. DELETE
    -----------

    ![image](https://github.com/user-attachments/assets/1bd7f5ff-d8dc-4860-9215-b31e867721ae)

    





    


  
