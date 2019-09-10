## Clase 5
## Clustering 3

# Metodos de validaciones
Es importante validar porque siempre clusterizan, por mas que este bien o mal.
Determinar el mejor K.
Comparar distintos metodos sobre mismos datos.

Ver si existe una tendencia al cluster, si los datos mas o menos se agrupan
Supervisado -> Externa
No superv -> Interna

No hay una medida de validacion mejor, para cada conjunto hay mejores y peores.

Cohesion vs Separacion

Vale probar distintas cosas porque yo lo que quiero ver es como se agrupan mis datos, no con un metodo particular

# Tendencia al Clustering (Hopkins)
Estadistico o Coeficiente de Hopkins
Tiende a pequeño si hay un buen cluster
Al azar tiende a 1/2
No esta implementado, ver el notebook Clustering3 para una implementacion manual

# Validacion externa
.Matriz de confusion, uno mas preponderante que el resto por cada columna/fila (Podemos usar pandas para armarla, tiene varias funciones para visualizar)
.Medida Normalizada de van Dongen. Medida mejorada de la pureza
.Indice RAND (o RAND ajustado/normalizado) - Esta en scikit-learn. Se fija cuanto coinciden las etiquetas y los clusters.


# Validacion interna
.Silhouete -> Maximizar cohesion
Se puede usar clustering jerarquico para ordenar la matriz (Matriz de distancias). Funcion imshow para ver grafico tipo mapa de calor
.Correlacion Confetico (Jerarquico) Cuanto mas cerca de 1 mejor
.Particion de arbol por distancia o por numero (Jerarquico)
.Bootstrapping (Resample con reposicion y generar cluster)