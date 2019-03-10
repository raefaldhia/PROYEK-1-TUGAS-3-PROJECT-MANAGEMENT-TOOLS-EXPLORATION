# DATEVALUE

Mengubah input teks tanggal menjadi nomor seri.

#### Syntax

```text
=DATEVALUE(date_text)
```

| Parameter | Deskripsi |
| :--- | :--- |
| date\_text | Text yang merepresentasikan tanggal dalam format penanggalan excel. |

{% hint style="info" %}
**Keterangan**

Argumen `date_text` harus didalam rentang 1 Januari 1900 hingga 31 Desember 9999 atau fungsi ini akan mengembalikan error `#value` 
{% endhint %}

#### Contoh

| A | Hasil |
| :--- | :--- |
| =DATEVALUE\("10/3/2019"\) | 43534 |

