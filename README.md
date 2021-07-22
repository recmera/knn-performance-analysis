# k-Nearest Neighbors 


## Integrantes
- **Ricardo Coronado**, ricardo dot coronado at alumnos dot uach dot cl
- **Eduardo Hopperdietzel**, eduardo dot hopperdietzel at alumnos dot uach dot cl
- **Diego Sandoval**, diego dot sandoval01 at alumnos dot uach dot cl

## Descripcion

Tarea grupal de la asignatura *Computación científica con python* INFO147 de la carrera Ingenieria Civil Informatica.


### Indicaciones

- Considere la implementación "ingenua" del algoritmo KNN que se adjunta a esta tarea con los parámetros $p$ y $k$ por defecto
  - Use la función adjunta create_data para crear un conjunto de N=1000 datos-
  - Realice un profiling completo de la función KNN usando las magias timeit, prun y lprun
  - Reporte sus resultados y comente sobre los cuellos de botella del algoritmo
- Implemente una nueva versión de la función KNN
  - Utilice Cython con tipos fijos, vistas de arreglos y funciones de la librería estándar matemática de C
  - Muestre que obtiene el mismo resultado que la versión original
  - Grafique el speed-up de su nueva función con respecto a la implementación "inocente" original para $N=[10, 50, 100, 500, 1000, 5000, 10000]$
- Usando la nueva versión de KNN y el conjunto de N=1000 datos creados con create_data realice una validación cruzada en el conjunto $E$ para encontrar el mejor valor de los parámetros $k$ y $p$
-  Evalue su mejor clasificador en el conjunto $T$ y haga un reporte completo de resultados que incluya curvas ROC y las métricas vistas en el curso. Muestre una gráfica de la frontera de decisión de su clasificador en el rango $[(-2,2), (-2,2)]$


## Caracteristicas del entorno


### Entorno virtual conda
|Elemento|Versión|
|--------|-------|
|python|3.9.5|
|pip|21.1.3|
|scikit-learn|0.24.2|
|numpy|1.20.3|
|matplotlib|3.3.4|
|cython|0.29.24|
## Referencias
