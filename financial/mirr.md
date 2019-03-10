---
description: >-
  Fungsi Excel MIRR adalah fungsi keuangan yang mengembalikan tingkat
  pengembalian internal yang dimodifikasi (MIRR) untuk serangkaian arus kas,
  dengan mempertimbangkan tingkat diskonto dan tingkat inve
---

# Excel MIRR Function

![Sumber : https://exceljet.net/excel-functions/excel-mirr-function](../.gitbook/assets/mirr.png)



#### Syntax

```text
=MIRR (values, finance_rate, reinvest_rate)Parameter 
```

| **Parameter** | **Penjelasan** |
| :--- | :--- |
|  values | referensi ke sel yang mengandung arus kas |
| finance\_rate | Tingkat pengembalian yang diperlukan \(tingkat diskont\) sebagai persentase. |
| reinvest\_rate | Suku bunga yang diterima pada arus kas diinvestasikan kembali sebagai persentase |

{% hint style="warning" %}
* Array nilai harus mengandung setidaknya satu nilai positif dan satu nilai negatif.
{% endhint %}

