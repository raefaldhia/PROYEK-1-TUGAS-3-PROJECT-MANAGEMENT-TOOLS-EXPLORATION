# TIMEVALUE

## Syntax

{% code-tabs %}
{% code-tabs-item title="Sintaks Fungsi" %}
```text
TIMEVALUE ( time_text )
```
{% endcode-tabs-item %}
{% endcode-tabs %}

## Parameter

| Parameter | Deskripsi |
| :--- | :--- |
| time\_text | string teks yang mewakili waktu. Dalam string teks ini, jam, menit dan detik harus dipisahkan dengan titik dua. |

{% hint style="info" %}
### Interpretasi String Teks Waktu

Jika hanya dua nilai \(dipisahkan oleh titik dua\) diberikan \(mis. 02:54\), ini akan diperlakukan sebagai jam dan menit, bukan menit dan detik. Jika Anda ingin mewakili 2 menit dan 54 detik, ini harus dilengkapi dengan jam yang ditentukan sebagai nol \(mis. "00:02:54"\).

Perhatikan juga bahwa, jika argumen time\_text berisi tanggal dan waktu, fungsi Timevalue mengabaikan bagian tanggal dari string teks.

Aturan-aturan ini diilustrasikan dalam contoh di bawah ini.
{% endhint %}

## Contoh Implementasi

![Rumus](../.gitbook/assets/screenshot-207.png)

![Hasil](../.gitbook/assets/screenshot-206.png)

