# CELL

Mengembalikan informasi mengenai formatting, lokasi, atau konten dari cell.

#### Syntax

```text
=CELL(info_type;reference)
```

| Parameter | Deskripsi |
| :--- | :--- |
| info\_type | Nilai bertipe teks yang menentukan informasi yang akan diambil. |
| reference | Referensi cell yang informasinya akan diambil. |

| **info\_type** | Nilai yang didapat |
| :--- | :--- |
| "address" | Referensi ke cell pertama pada referensi sebagai teks |
| "col" | Nomor kolom dari cell pada referensi |
| "color" | Angka 1 bila cell diformat dalam warna untuk nilai negatif. lainnya 0. |
| "contents" | Isi dari cell pojok kanan atas pada referensi. bukan formula. |
| "format" | Nilai teks sesuai dengan format angka sel. Nilai teks untuk berbagai format ditampilkan dalam tabel berikut. Mengembalikan "-" di akhir nilai teks jika sel diformat dalam warna untuk nilai negatif. Mengembalikan "\(\)" di akhir nilai teks jika sel diformat dengan tanda kurung untuk nilai positif atau semua. |
| "parentheses" | Angka 1 bila cell diformat dengan tanda kurung untuk nilai positif atau semua nilai. lainnya 0. |
| "prefix" | Nilai teks sesuai dengan "label awalan" sel. Mengembalikan tanda kutip tunggal \('\) jika sel berisi teks selaras kiri, tanda kutip ganda \("\) jika sel berisi teks selaras kanan, tanda sisipan \(^\) jika sel berisi teks terpusat, garis miring terbalik \(\) jika sel mengandung isi teks yang rata, dan kosongkan teks \(""\) jika sel berisi hal lain. |
| "protect | Nilai 0 jika sel tidak dikunci; jika tidak mengembalikan 1 jika sel terkunci. |
| "row" | Nomor baris dari cell pada referensi |
| "type" | Nilai teks sesuai dengan jenis data dalam sel. Mengembalikan "b" untuk kosong jika sel kosong, "l" untuk label jika sel berisi konstanta teks, dan "v" untuk nilai jika sel berisi hal lain. |
| "width" | Lebar kolom dari cell, dibulatkan ke bilangan bulat. |

