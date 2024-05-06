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

<!---

### Mapa de Karnaugh:

|   | 00 | 01 | 11 | 10 |
|:-:|:--:|:--:|:--:|:--:|
| 0 |  0 |  1 |  0 |  1 |
| 1 |  1 |  0 |  0 |  1 |
-->

### OUT = a'.b + a'.c + a.b'.c'

![Sintesis lógica de R30](circuit-20240505-2001.png "Sintesis lógica de R30")

![R30 de tres celdas](circuit-20240505-2035.png "R30 de tres celdas")


#### [Simulación](https://tinyurl.com/2whdor7w)

![Simulación física](circuit-20240506-0957.png "Simulación física")
[Simulación de una celda](https://tinyurl.com/3xkusjz4)
