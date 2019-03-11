# IF

Rumus Excel IF adalah rumus logika yang digunakan untuk mengecek suatu kondisi , jika kondisi terpenuhi akan menghasilkan nilai TRUE yang bisa kita tentukan, jika tidak terpenuhi akan menghasilan nilai FALSE yang bisa kita tentukan juga.

Rumus IF ini bisa kita bagi menjadi dua:

1. **Rumus IF Tunggal**
2. **Rumus IF Majemuk**

Berikut akan dijelaskan satu persatu-satu :

**1. Rumus Excel IF Tunggal**

Rumus Excel IF Tunggal ini hanya terdapat satu IF dengan satu logical\_test, rumus if tunggal ini memiliki dua kondisi yaitu Kondisi1 \(value if TRUE\) dan Kondisi2 \(value if FALSE\).

Sintak Penulisan Rumus Exce IF Tunggal

```text
=IF(logical_test;value_if_true;value_if_false)
```

Contohnya :  
![Rumus Excel IF](https://i1.wp.com/www.belajaroffice.com/wp-content/uploads/2015/04/Rumus-Excel-IF.jpg?resize=188%2C178)

Rumus Excel IF

=IF\(C5&lt;6;”Tidak Lulus”;”Lulus”\)

Artinya : Jika nilai kurang dari 6 maka tidak lulus, sebaliknya lulus.

Selain itu rumus Excel IF tungal juga bisa digabung dengan rumus logika OR \(atau\) dan AND \(dan\)

* **2. Rumus Excel IF Majemuk**

Rumus Excel IF Majemuk terdiri dari lebih satu atau banyak IF yang bisa kita sesuaikan sesuai dengan kebutuhan tergantung dari berapa jumlah kondisi yang akan kita tetapkan.

Sintak Penulisan Rumusnya :

```text
=IF(logical_test;value_if_true;IF(logical_test;value_if_true;IF(... "value_if_false dst))
```

Contoh Rumus Excel IF Majemuk

```text
=IF(F34>=3,5;"Cum Laude";IF(F34>=3,4;"Sangat Memuaskan";IF(F34>=2,9;"Memuaskan";IF(F34>=2,4;"Cukup";"Tidak Lulus"))))
```

