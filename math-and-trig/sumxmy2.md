---
description: Mengembalikan jumlah kuadrat selisih nilai yang terkait dalam dua array.
---

# SUMXMY2

## Syntax

{% code-tabs %}
{% code-tabs-item title="Sintaks Fungsi" %}
```text
SUMXMY2( array_x, array_y )
```
{% endcode-tabs-item %}
{% endcode-tabs %}

## Parameter

| Parameter | Deskripsi |
| :--- | :--- |
| array\_x | Array atau rentang nilai pertama. |
| array\_y | Array atau rentang nilai kedua. |

{% hint style="info" %}

## Keterangan

* Argumen harus berupa angka atau nama, array, atau referensi yang berisi angka-angka.
* Jika sebuah argumen array atau referensi mencakup teks, nilai logika, atau sel kosong, maka nilai-nilai itu diabaikan; akan tetapi sel-sel dengan nilai nol dimasukkan.
* Jika array\_x dan array\_y memiliki jumlah nilai yang berbeda, SUMXMY2 mengembalikan nilai kesalahan \#N/A.
* Persamaan untuk jumlah selisih kuadrat adalah:

  ![Persamaan](https://support.content.office.net/id-id/media/1be4bfbd-aec7-4ab6-bf9a-c00736129537.gif)

## Contoh Implementasi

![Rumus](../.gitbook/assets/screenshot-193.png)

![Hasil](../.gitbook/assets/screenshot-192.png)

