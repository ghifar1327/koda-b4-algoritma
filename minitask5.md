## flowchart menghitung luas dan keliling lingkaran

```mermaid
flowchart TB
a([start]) --->b[/masukan nilai r/]
b--->c{r dibagi habis dengan 7}
c--->|ya|d[phi 22/7 ]
c--->|tidak|e[phi 3.14]
d--->f{rumus}
e--->f
f--->|luas|g[phi x r x r]
f--->|keliling|i[2 x phi x r]
g--->j[cetak hasil]
i--->j
j--->k(((end)))
```
