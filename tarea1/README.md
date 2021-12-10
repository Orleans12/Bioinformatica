# Bioinformatica
Bioinformatica codes
## Plant-Pollinators Networks

[La data de Saavedra y Stouffer puede encontrarse en](http://dx.doi.org/10.5061/dryad.p2gq8)
Saavedra y Stouffer (2013) estudiaron varias redes planta-polinizador, que pueden representarse como matrices rectangularesen las que las filas son los polinizadores,
las columnas las plantas, un 0 indica la ausencia y un 1 la presencia de una interacción entre la planta y el polinizador.

### Ejercicio 1

Escriba un script que tome uno de estos archivos y determine el número de filas (polinizadores) y columnas (plantas). 
Tenga en cuenta que las columnas están separadas por espacios y que hay un espacio al final de cada línea. Su script debe devolver:

$bashnetsize.sh ../data/Saavedra2013/n1.txt
Filename: ../data/Saavedra2013/n1.txt
Number of rows: 97
Number of columns: 80

### Ejercicio 2

Escriba un script que imprima el número de filas y columnas de cada red

`$bash netsize_all.sh`
`../data/Saavedra2013/n10.txt 14 20`
`../data/Saavedra2013/n11.txt 270 91`
`../data/Saavedra2013/n12.txt 7 72`
`../data/Saavedra2013/n13.txt 61 17`
`...`

### Ejercicio 3
¿Qué archivo tiene el mayor número de filas? ¿Cuál tiene el mayor número de columnas?

### Material recreativo para no estresarse, [clip here](https://www.youtube.com/watch?v=YPIPRbWuKg4)
