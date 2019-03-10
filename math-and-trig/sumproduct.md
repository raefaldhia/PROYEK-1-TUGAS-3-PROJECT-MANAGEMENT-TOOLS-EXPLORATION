---
description: >-
  Mengalikan komponen-komponen terkait dalam array yang diberikan, dan
  mengembalikan jumlah dari setiap hasil perkalian tersebut.
---

# SUMPRODUCT

### Syntax

```text
SUMPRODUCT( array1, [array2], [array3], ... )
```

### Parameter

<table>
  <thead>
    <tr>
      <th style="text-align:left">Parameter</th>
      <th style="text-align:left">Deskripsi</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <p></p>
        <p><b>Array1</b> 
        </p>
        <p></p>
      </td>
      <td style="text-align:left">Diperlukan. Argumen array pertama yang komponen-komponennya ingin Anda
        kalikan lalu tambahkan.</td>
    </tr>
    <tr>
      <td style="text-align:left"><b>Array2,array3,...</b>
      </td>
      <td style="text-align:left">Opsional. Argumen array 2 sampai 255 yang komponen-komponennya ingin Anda
        kalikan lalu tambahkan</td>
    </tr>
  </tbody>
</table>{% hint style="info" %}


### Keterangan

* Argumen array harus memiliki dimensi yang sama. Jika tidak, SUMPRODUCT mengembalikan nilai kesalahan \#VALUE!.
* SUMPRODUCT memperlakukan entri array yang bukan numerik seperti angka nol.
{% endhint %}

### Contoh Implementasi

![Rumus](../.gitbook/assets/screenshot-201.png)

![Hasil](../.gitbook/assets/screenshot-200.png)

