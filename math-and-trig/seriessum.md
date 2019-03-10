# SERIESSUM

Mendapatkan jumlah dari seri perpangkatan berdasarkan formula:

$$SERIES(x, n, m, a) = a_1x^n + a_2x^{n+m}+a_3^{n+2m}+...+a_ix^{n+(i-1)m}$$ 

#### Syntax

```text
=SERIESSUM(X;N;M;Coefficients)
```

| Parameter | Deskripsi |
| :--- | :--- |
| X | Nilai input untuk seri perpangkatan. |
| N | Nilai awal pangkat yang akan meningkatkan X. |
| M | Langkah untuk meningkatkan N untuk tiap masa dalam seri. |
| Coefficients | Sekumpulan koefisien yang mana setiap perpangkatan X dikalikan berturut-turut. |

