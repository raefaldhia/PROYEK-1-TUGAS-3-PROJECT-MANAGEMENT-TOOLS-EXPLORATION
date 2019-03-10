---
description: >-
  Fungsi Excel MDURATION mengembalikan durasi Macauley yang dimodifikasi untuk
  keamanan dengan nilai par yang diasumsikan $ 100
---

# MDURATION

Fungsi Excel MDURATION mengembalikan durasi Macauley yang dimodifikasi untuk keamanan dengan nilai par yang diasumsikan $ 100.

![Sumber : https://exceljet.net/excel-functions/excel-mduration-function](../.gitbook/assets/mduration.png)

#### Syntax

```text
=MDURATION(settlement;maturity;coupon;yld;freq;[basis])
```

| **Parameter** | **Penjelasan** |
| :--- | :--- |
| settlement | Settlement tanggal keamanan. |
| maturity | Maturity tanggal keamanan. |
| coupon | Tingkat kupon tahunan keamanan. |
| yld | Hasil tahunan keamanan. |
| freq | Jumlah pembayaran kupon per tahun. |
| basis | \[opsional\] Dasar hitungan hari. |

{% hint style="warning" %}
* Jika tanggal tidak valid \(mis. Bukan tanggal sebenarnya\) MDURATION mengembalikan `#VALUE!`
{% endhint %}

