# Medición de la Forma de Arco en Modelos Digitales Usando como Referencia el Voto Mayoritario
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
- 14 Anchos meso-distales (iso17-iso27 o iso37-iso47)  --Float
- 1 ancho intercanino (ancho intercanino (3-3)) --Float
- 2 interpremolares (anchura interpremolar (4-4) y anchura interpremolar (5-5))  --Float
- 1 intermolar (ancho intermolar)  --Float
- 1 Etiqueta dada por experto de la forma del arco (1:cuadrada, 2:ovalada, 3:triangular)  --Int 
- 1 Etiqueta dada por el consenso entre los 3 expertos considerando las dos tomas (Voto mayoritario ponderado)  --Int

## Voto mayoritario ponderado

<img src="https://github.com/jdtamayoq/Dental_shape_database/blob/main/vote_m.png" alt="JuveR" width="300px">


## Datos ejemplo

### Maxilar superior
https://github.com/jdtamayoq/Dental_shape_database/blob/main/maxilar_superior.csv

| **Modelo** | **Toma** | **Experto** | **iso17** | **iso16** | **...** | **iso26** | **iso27** | **ancho intercanino (3-3)** | **anchura interpremolar (4-4)** | **anchura interpremolar (5-5)** | **ancho intermolar** | **Etiqueta (Voto Mayoritario)** | **Etiqueta (experto)** |
|:----------:|:--------:|:-----------:|:---------:|:----------:|:-------:|:---------:|:---------:|:---------------------------:|:-------------------------------:|:-------------------------------:|:--------------------:|:-------------------------------:|:-----------------------:|
| 1          | 1        | Experto 1   | 9,33      | 8,98       | ...     | 9,08      | 9,13      | 36,33                       | 33,46                           | 35,76                           | 38,91                | 2                               | 1                       |
| 4          | 1        | Experto 1   | 9,37      | 10,36      | ...     | 9,82      | 10,25     | 42,04                       | 38,21                           | 46,7                            | 45,84                | 2                               | 2                       |
| 5          | 1        | Experto 1   | 10,15     | 10,55      | ...     | 10,55     | 9,12      | 32,89                       | 28,58                           | 36,52                           | 41,26                | 3                               | 3                       |
| 6          | 1        | Experto 1   | 9,66      | 10,65      | ...     | 10,12     | 10,02     | 36,91                       | 34,13                           | 37,77                           | 40,4                 | 3                               | 3                       |

### Maxilar inferior
https://github.com/jdtamayoq/Dental_shape_database/blob/main/maxilar_inferior.csv

| **Modelo** | **Toma** | **Experto** | **iso37** | **iso36** | **...** | **iso46** | **iso47** | **ancho intercanino (3-3)** | **anchura interpremolar (4-4)** | **anchura interpremolar (5-5)** | **ancho intermolar** | **Etiqueta (Voto mayoritario)** | **Etiqueta (Experto)** |
|:----------:|:--------:|:-----------:|:---------:|:----------:|:-------:|:---------:|:---------:|:---------------------------:|:-------------------------------:|:-------------------------------:|:--------------------:|:-------------------------------:|:-----------------------:|
| 1          | 1        | Experto 1   | 9,9       | 8,71       | ...     | 9,18      | 9,44      | 26,91                       | 31,48                           | 36,4                            | 38,73                | 1                               | 1                       |
| 4          | 1        | Experto 1   | 9,71      | 10,59      | ...     | 10,04     | 9,91      | 29,24                       | 29,97                           | 33,22                           | 38,51                | 2                               | 2                       |
| 5          | 1        | Experto 1   | 9,79      | 10,86      | ...     | 10,12     | 9,39      | 28,99                       | 28,67                           | 35,78                           | 35,81                | 2                               | 2                       |
| 6          | 1        | Experto 1   | 9,47      | 10,38      | ...     | 10,36     | 9,79      | 29,13                       | 31,43                           | 36,69                           | 38,13                | 2                               | 2                       |
