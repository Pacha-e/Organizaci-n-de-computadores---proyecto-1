# Organización de Computadores — Nand2Tetris

Implementación de circuitos lógicos en HDL (Hardware Description Language) siguiendo la metodología de [Nand2Tetris](https://www.nand2tetris.org/), junto con su representación visual en **Logisim** (archivo `.circ`).

---

## Estructura del Proyecto

```
├── Project1/          # Compuertas lógicas básicas
├── Project2/          # Circuitos aritméticos
├── Project3/          # Memoria secuencial (parcial)
├── logisim.circ       # Todos los circuitos implementados en Logisim
└── README.md
```

---

## Proyecto 1 — Compuertas Lógicas

Implementación de todas las compuertas lógicas fundamentales a partir de la compuerta NAND.

| Chip       | Descripción                              |
|------------|------------------------------------------|
| `Not`      | Compuerta NOT (inversor)                 |
| `And`      | Compuerta AND de 2 entradas              |
| `Or`       | Compuerta OR de 2 entradas               |
| `Xor`      | Compuerta XOR (OR exclusivo)             |
| `Mux`      | Multiplexor 2:1                          |
| `DMux`     | Demultiplexor 1:2                        |
| `Not16`    | NOT de 16 bits                           |
| `And16`    | AND de 16 bits                           |
| `Or16`     | OR de 16 bits                            |
| `Mux16`    | Multiplexor 2:1 de 16 bits               |
| `Or8Way`   | OR de 8 entradas                         |
| `Mux4Way16`| Multiplexor 4:1 de 16 bits               |
| `Mux8Way16`| Multiplexor 8:1 de 16 bits               |
| `DMux4Way` | Demultiplexor 1:4                        |
| `DMux8Way` | Demultiplexor 1:8                        |

---

## Proyecto 2 — Aritmética Binaria

Implementación de circuitos aritméticos para la ALU.

| Chip        | Descripción                              |
|-------------|------------------------------------------|
| `HalfAdder` | Sumador de medio bit                     |
| `FullAdder` | Sumador completo de 1 bit                |
| `Add16`     | Sumador de 16 bits                       |

> **Nota:** El chip `Inc16` (incrementador de 16 bits) no está incluido en esta entrega.
> **Nota:** El chip `ALU`  no está incluido en esta entrega.

---

## Proyecto 3 — Memoria Secuencial (Parcial)

Implementación de elementos de memoria básicos con lógica secuencial.

| Chip       | Descripción                              |
|------------|------------------------------------------|
| `Bit`      | Registro de 1 bit (flip-flop con load)   |
| `Register` | Registro de 16 bits                      |

---

## Archivo Logisim

El archivo `Organización de computadores.circ` contiene la implementación visual de **todos los circuitos anteriores** en [Logisim](http://www.cburch.com/logisim/). Permite simular y verificar el comportamiento de cada chip de forma gráfica.

Para abrirlo, descarga Logisim y ejecuta:

```bash
java -jar logisim.jar logisim.circ
```

---

## Tecnologías Utilizadas

- **HDL** — Hardware Description Language (Nand2Tetris)
- **Logisim** — Simulador de circuitos digitales
- **Nand2Tetris** — Plataforma de simulación y validación

---

## Autor Emmanuel Hernández Melo

Proyecto desarrollado para la asignatura **Organización de Computadores**.
