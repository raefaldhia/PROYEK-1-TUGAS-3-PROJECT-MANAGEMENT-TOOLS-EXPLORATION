---
description: >-
  Memotong angka ke bilangan bulat dengan menghilangkan bagian pecahan dari
  angka tersebut.
---

# TRUNCH

### Syntax

{% code-tabs %}
{% code-tabs-item title="Sintaks Fungsi" %}
```text
TRUNC( number, [num_digits] )
```
{% endcode-tabs-item %}
{% endcode-tabs %}

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
      <td style="text-align:left">Number</td>
      <td style="text-align:left">Nomor yang akan dipotong</td>
    </tr>
    <tr>
      <td style="text-align:left">[num_digit]</td>
      <td style="text-align:left">
        <p></p>
        <p>Argumen opsional yang menentukan jumlah tempat desimal untuk memotong
          angka yang disediakan.</p>
        <p>Jika dihilangkan, argumen [num_digits] menggunakan nilai default 0.</p>
        <p>Perhatikan bahwa:</p>
        <ul>
          <li>Nilai [num_digits] positif menentukan jumlah digit di sebelah kanan titik
            desimal;</li>
          <li>Jika [num_digits] adalah 0 (atau dihilangkan), nomor yang diberikan terpotong
            ke bilangan bulat terdekat;</li>
          <li>Nilai [num_digits] negatif menentukan jumlah digit di sebelah kiri titik
            desimal.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>### Contoh Implementasi 

![Rumus](../.gitbook/assets/screenshot-182.png)

![Hasil](../.gitbook/assets/screenshot-181.png)

