---
description: >-
  Fungsi Excel IPMT dapat digunakan untuk menghitung bagian bunga dari
  pembayaran pinjaman yang diberikan dalam periode pembayaran tertentu.
---

# Excel IPMT Function

![Sumber : https://exceljet.net/excel-functions/excel-ipmt-function](../.gitbook/assets/ipmt.png)



#### Syntax

```text
=IPMT (rate, per, nper, pv, [fv], [type])
```

#### Parameter 

| **Parameter** | **Penjelasan** |
| :--- | :--- |
|  rate | presentase bunga \(setiap periode\) |
| per | pembayaran ke-n. |
| nper | total periode pembayaran |
| pv | nilai Awal pinjaman |
| \[fv\] | Uang yang harus dibayar di akhir periode |

{% hint style="warning" %}
* Konsisten dengan input untuk rate
* Berdasarkan konvensi, nilai pinjaman \(pv\) dimasukkan sebagai nilai negatif.
{% endhint %}

