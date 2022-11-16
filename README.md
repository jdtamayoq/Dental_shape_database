# Variabilidad intra e inter examinador en la medición de la forma de arco en modelos digitales usando como estándar el voto mayoritario
#
## Introdución:
Mantener la forma de arco, o generar el menor cambio posible durante los tratamientos de ortodoncia, conduce a una mejor estabilidad en la fase de retención. El objetivo de este trabajo es brindar a la comunidad un estudio de la variabilidad de las mediciones de las formas del arco a partir de tres expertos y su consenso por medio del voto mayoritario.

## Adquisición:
La adquisición de los 50 modelos digitales se realizó con el AutoScan-DS-EX en la facultad de odontología de la Universidad Nacional de Colombia y la anotación de las 19 variables fue llevada a cabo por 3 expertos:

- Experto 1: residente de primer año de la especialidad en ortodoncia y ortopedia maxilar de la Universidad Nacional de Colombia
- Experto 2: residente de tercer año de la especialidad de ortodoncia y ortopedia maxilar de la Universidad Nacional de Colombia.
- Experto 3: odontóloga general de la Universidad Autónoma de Manizales con un año de experiencia.

## Caracteristicas:
23 variables: dos tomas con 15 días de diferencia.

- 1 Numero modelo (1- 60) 10 modelos fueron descartados --Int
- 1 Toma (1-2) 15 días de diferencia entre toma --Int
- 1 Experto (1-3) --String
- 14 Anchos meso-distales  --Float
- 1 ancho intercanino  --Float
- 2 interpremolares  --Float
- 1 intermolar  --Float
- 1 Etiqueta dada por experto de la forma del arco (1:cuadrada, 2:ovalada, 3:triangular)  --Int 
- 1 Etiqueta dada por el consenso entre los 3 expertos considerando las dos tomas (Voto mayoritario ponderado)  --Int

## Data 
| **Modelo** | **Toma** | **Experto** | **iso17** | **iso16** | **...** | **iso26** | **iso27** | **ancho intercanino (3-3)** | **anchura interpremolar (4-4)** | **anchura interpremolar (5-5)** | **ancho intermolar** | **Etiqueta (Voto Mayoritario)** | **Etiqueta (experto) ** |
|------------|----------|-------------|-----------|------------|---------|-----------|-----------|-----------------------------|---------------------------------|---------------------------------|----------------------|---------------------------------|-------------------------|
| 1          | 1        | Experto 1   | 9,33      | 8,98       | ...     | 9,08      | 9,13      | 36,33                       | 33,46                           | 35,76                           | 38,91                | 2                               | 1                       |
| 4          | 2        | Experto 1   | 9,37      | 10,36      | ...     | 9,82      | 10,25     | 42,04                       | 38,21                           | 46,7                            | 45,84                | 2                               | 2                       |
| 5          | 3        | Experto 1   | 10,15     | 10,55      | ...     | 10,55     | 9,12      | 32,89                       | 28,58                           | 36,52                           | 41,26                | 3                               | 3                       |
| 6          | 4        | Experto 1   | 9,66      | 10,65      | ...     | 10,12     | 10,02     | 36,91                       | 34,13                           | 37,77                           | 40,4                 | 3                               | 3                       |
