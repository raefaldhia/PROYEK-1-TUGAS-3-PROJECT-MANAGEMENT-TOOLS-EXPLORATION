---
description: >-
  Melakukan perhitungan yang ditentukan (mis. Jumlah, produk, rata-rata, dll.)
  Untuk sekumpulan nilai yang disediakan.
---

# SUBTOTAL

## Syntax

{% code-tabs %}
{% code-tabs-item title="Sintaks Fungs" %}
```text
SUBTOTAL ( function_num , ref1 , [ref2] , ...)
```
{% endcode-tabs-item %}
{% endcode-tabs %}

## Parameter

<table>
  <thead>
    <tr>
      <th style="text-align:left">Parameter</th>
      <th style="text-align:left">Deskripsi</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">function_num</td>
      <td style="text-align:left">Integer yang menunjukkan tipe perhitungan (mis. Jumlah, rata-rata, dll.).</td>
    </tr>
    <tr>
      <td style="text-align:left">ref1, [ref2], ...</td>
      <td style="text-align:left">
        <p>Satu atau lebih referensi ke sel yang berisi nilai perhitungan yang harus
          dilakukan.
          <br />
        </p>
        <p>(Sel kosong dan sel yang berisi nilai non-numerik diabaikan dalam perhitungan).</p>
      </td>
    </tr>
  </tbody>
</table>