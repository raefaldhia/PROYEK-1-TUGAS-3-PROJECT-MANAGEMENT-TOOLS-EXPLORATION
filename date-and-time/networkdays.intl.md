# NETWORKDAYS.INTL

Rumus Excel NETWORKDAYS yaitu digunakan untuk menghitung jumlah hari kerja dengan ketentuan 5 hari kerja dalam satu pekan \(libur dua hari yaitu sabtu dan minggu\).  RUMUS EXCEL NETWORKDAYS.INTL yaitu digunakan untuk menghitung hari kerja dengan ketetapan hari libur yang bisa kita tentukan, misalnya libur kerjanya hanya hari Minggu, bisa juga kita mengantinya hari lain misalnya Jum’at, Sabtu saja sesuai dengan kebutuhan masing-masing.

Untuk lebih jelasnya simak berikut ini contohnya :

[![Rumus Excel NETWORKDAYS.INTL](https://i1.wp.com/www.belajaroffice.com/wp-content/uploads/2014/11/Rumus-NETWORKDAYS.INTL_-300x173.jpg?resize=300%2C173)](https://i0.wp.com/www.belajaroffice.com/wp-content/uploads/2014/11/Rumus-NETWORKDAYS.INTL_.jpg)

Rumus Excel NETWORKDAYS.INTL

Contoh diatas, kita akan menghitung hari kerja karyawan dengan hari libur hanya hari minggu saja setiap pekan dan libur nasional jika ada.

Syntak penulisan rumusnya yaitu : 

```text
=NETWORKDAYS.INTL(start_date;end_date;weekend;holiday)
```

_ket :_

_start\_date : tanggal mulai kerja  
end\_date : tanggal selesai kerja  
weekend : ketentuan libur pekanan  
holiday : Hari libur nasional jika ada_

Pada cell E4 ketikan rumusnya : **=NETWORKDAYS.INTL\(C4;D4;11;C11\)**

Untuk kode holiday sebagai berikut bisa dipilih sesuai kebutuhan satu hari atau dua hari.

[![weekend](https://i1.wp.com/www.belajaroffice.com/wp-content/uploads/2014/11/weekend.jpg?resize=223%2C255)](https://i1.wp.com/www.belajaroffice.com/wp-content/uploads/2014/11/weekend.jpg)

Selanjutnya kita tambahakan simbol alamat cell absolute \($\) pada cell hari libur **$C$11**karena setiap karyawan libur pada tanggal merah supaya ketika kita drag rumusnya akan tetap.  
****

Rumusnya menjadi **=NETWORKDAYS.INTL\(C4;D4;11;$C$11\)**  
Berikut ini contoh hasilnya :

[![NETWORKDAYS.INTL Hasil](https://i0.wp.com/www.belajaroffice.com/wp-content/uploads/2014/11/NETWORKDAYS.INTL-Hasil-300x185.jpg?resize=300%2C185)](https://i0.wp.com/www.belajaroffice.com/wp-content/uploads/2014/11/NETWORKDAYS.INTL-Hasil.jpg)

Catatan : Penulisan tanggalnya jangan sampai salah misalnya tanggalnya harusnya hanya  30 ditulisanya jadi 31, hasilnya akan error  \#VALUE!

