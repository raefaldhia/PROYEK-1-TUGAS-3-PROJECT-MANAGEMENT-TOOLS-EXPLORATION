---
description: Mengembalikan jumlah perbedaan kuadrat dari dua set nilai yang disediakan.
---

# SUMX2MY2

### Syntax

{% code-tabs %}
{% code-tabs-item title="Sintaks Fungsi" %}
```text
SUMX2MY2 ( array_x , array_y )
```
{% endcode-tabs-item %}
{% endcode-tabs %}

### Parameter

| Parameter | Deskripsi |
| :--- | :--- |
| array \_x | Array atau rentang nilai pertama. |
| array\_y | Array atau rentang nilai kedua. |

{% hint style="info" %}


### Keterangan

* Argumen harus berupa angka atau nama, array, atau referensi yang berisi angka-angka.
* Jika sebuah argumen array atau referensi mencakup teks, nilai logika, atau sel kosong, maka nilai-nilai itu diabaikan; akan tetapi sel-sel dengan nilai nol dimasukkan.
* Jika array\_x dan array\_y memiliki jumlah nilai yang berbeda, SUMX2MY2 mengembalikan nilai kesalahan \#N/A.
* Persamaan untuk jumlah selisih kuadrat adalah:

  ![Persamaan](https://support.content.office.net/id-id/media/9b81a807-b9a5-4ca7-aad1-0f94dc418208.gif)
{% endhint %}

### Contoh Implementasi

![Rumus](../.gitbook/assets/screenshot-187.png)

![Hasil](../.gitbook/assets/screenshot-186.png)

