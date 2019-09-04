## Clase 4

## Clustering 2

Matrices de disimilaridad (o distancia)
a=b, d(a,b)=0
Matrices Metrica (Desigualdad triangular)
Matrices Ultrametricas (Desigualdad con el maximo)

Matrices de similaridad
a=b, s(a,b)=1

Hay mapeos de similaridad a disimilaridad
Utiles para distintos algoritmos.

Distancias euclideas y manhattan se generalizan en metricas de minkowski
Podemos definir un peso que se calcula con el desvio estandar o el rango, y tiene que ver con una normalizacion

Variables categoricas
.Puras (Multiestado) Cada categoria es algo distinto
    Se transforman en variables dummies si no tengo muchos estados (Binarias)
    O criterio de coincidencias (calcular). Cantidad de cosas en la que coinciden esos dos items

.Ordinales Estos estados puedo ordenarlos de alguna manera. No son continuas pero tienen un orden
    Definir distancia como saltitos entre los distintos valores ordenados

Angulos de vectores    
    Coeficiente de correlacion de Pearson
    Similitud coseno (Producto interno)

Comparar varialbes de tipos mixtos -> Promediar todas las distancias