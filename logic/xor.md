# XOR

Pengertian Fungsi Excel XOR adalah digunakan untuk mengembalikan logika Exclusive Or dari semua argumen.

Sintak penulisan Fungsi Excel XOR :

```text
=XOR(logical1, [logical2], dst)
```

logical : Pernyataan1 atau argument1 dengan ketentuan  TRUE atau FALSE.

Pengertian diatas masih sulit untuk dipahami, untuk itu akan dijelaskan fungsi dari rumus XOR ini berdasarkan percobaan berikut ini.[![Fungsi Excel XOR](https://i2.wp.com/www.belajaroffice.com/wp-content/uploads/2015/11/Fungsi-Excel-XOR.jpg?resize=428%2C264)](https://i2.wp.com/www.belajaroffice.com/wp-content/uploads/2015/11/Fungsi-Excel-XOR.jpg)

Fungsi Excel XOR

Pada tabel Excel diatas ketikan rumus sebagai berikut

=XOR\(3&gt;4\) argument 3 lebih besar 4 logical tersebut adalah salah. maka didapat hasil FALSE

=XOR\(3&gt;4;4&gt;5\) argumen 3 lebih besar dari 4 logical adalah Salah, dan argument 4 lebih besar dari 5 adalah salah, didapatkan hasil FALSE.

=XOR\(3&lt;4\) argument 3 lebih kecil dari 4 logical tersebut adalah Benar . maka didapat hasil TRUE.

=XOR\(3&gt;4;4&gt;5\) argumen 3 kurang dari 4 logical adalah Benar, argument 4 kurang dari 5 adalah Benar, didapatkan hasil FALSE.

dst

Kita bisa perhatikan pada percobaan diatas jika logical yang jumlah argument benar adalah ganjil akan menghasilkan TRUE sedangkan jika argument benar jumlahnya genap hasilnya FALSE.

jadi kesimpulannya fungsi Excel XOR digunakan untuk mengembalikan nilai TRUE jika logical yang nilainya benar jumlahnya ganjil dan akan memgembalikan nilai FALSE jika logical benar jumlahnya genap.

