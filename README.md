# LCA_automata-celular

## RULE 30

| a | b | c | OUT|
| - | - | - |:--:|
| 1 | 1 | 1 | 0  |
| 1 | 1 | 0 | 0  |
| 1 | 0 | 1 | 0  |
| 1 | 0 | 0 | 1  |
| 0 | 1 | 1 | 1  |
| 0 | 1 | 0 | 1  |
| 0 | 0 | 1 | 1  |
| 0 | 0 | 0 | 0  |


<img src="mapa_karnaugh.jpg" width="500" />

### El resultado es OUT = a'.b + a'.c + a.b'.c' que en compuertas lógicas se traduce a:
<!-- **### OUT = a'.b + a'.c + a.b'.c' -->

![Sintesis lógica de R30](circuit-20240505-2001.png "Sintesis lógica de R30")

<!---
![R30 de tres celdas](circuit-20240505-2035.png "R30 de tres celdas")

#### [Simulación](https://tinyurl.com/2whdor7w)
![Simulación física](circuit-20240506-0957.png "Simulación física")
[Simulación de una celda](https://tinyurl.com/3xkusjz4)
-->

### [Simulación de todo el autómata con 3 celdas](https://tinyurl.com/246u2hgd)
![](circuit-20240601-1953.png)


### [Dentro de cada celda](https://tinyurl.com/2aovvxox)
![](circuit-20240601-1959.png)
