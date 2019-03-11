# IFERROR

Fungsi **IFERROR** yaitu digunakan untuk mengecek jika terjadi kesalahan atau eror, bila terjadi kesalahan pada rumus excel maka akan muncul pesan eror seperti **\#DIV/0, \# VALUE, \#N/A** dst, untuk menghilangkan atau menganti pesan error tersebut kita bisa menggunakan fungsi IFERROR ini.Untuk lebih jelasnya berikut contohnya :

[![Fungsi IFERROR pada Excel](https://i1.wp.com/www.belajaroffice.com/wp-content/uploads/2013/12/if-error.jpg?resize=294%2C257)](https://i1.wp.com/www.belajaroffice.com/wp-content/uploads/2013/12/if-error.jpg)

Fungsi IFERROR pada Excel Tabel diatas yaitu pembagian antara nilai A/B dimana jika nilai pembagi 0 atau Kosong makan akan terjadi pesan error, untuk menghilangkan pesan error tersebut kita bisa gunakan fungsi **IFERROR**.  
**Langkah-langkahnya yaitu sebagai berikut :**  
Buat tabel seperti gambar di atas. Pada cell C4 ketikan rumus **=A4/B4** menjadi  **=IFERROR\(A4/B4;””\)  
  
Penjelasan :**   
A8/B8 \(Value\) : rumus yang diuji  
“” \(Value if error \): jika rumus yang diuji terjadi error maka akan mengahasilkan kriteria/nilai ini. Ini “ ” Kosong, dan nilai ini bisa kita ubah/tentukan sesuai keinginan dan kebutuhan.  
  
Berikut contoh hasilnya :

[![Fungsi IFERROR pada Excel](https://i0.wp.com/www.belajaroffice.com/wp-content/uploads/2013/12/if-error2-300x201.jpg?resize=320%2C215)](https://i1.wp.com/www.belajaroffice.com/wp-content/uploads/2013/12/if-error2.jpg)  


