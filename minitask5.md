## flowchart menghitung luas dan keliling lingkaran

```mermaid
flowchart TB
a([start]) --->b[/r/]
b--->c{r % 7 = 0}
c--->|true|d[/phi = 22/7 /]
c--->|false|e[/phi = 3.14/]
d--->g[luas = phi * r * r]
g--->i[keliling = 2 * phi * r]
e--->g
i--->j[/luas/]
j--->k[/keliling/]
k--->l(((end)))
```
