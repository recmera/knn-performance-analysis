# k-Nearest Neighbors 


## Integrantes
- **Ricardo Coronado** ricardo dot coronado at alumnos dot uach dot cl
- **Eduardo Hopperdietzel** eduardo dot hopperdietzel at alumnos dot uach dot cl
- **Diego Sandoval** diego dot sandoval at alumnos dot uach dot cl

## Descripcion

Tarea grupal de la asignatura *Computación científica con python* INFO147 de la carrera Ingenieria Civil Informatica.


### Instrucciones específicas

El objetivo de esta actividad es entrenar y evaluar una red neuronal profunda para clasificar automáticamente el prendas de vestir a partir de imágenes. Usted entrenará este modelo usando un conjunto de 70,000 imágenes con 10 categorías de prendas conocido como Fashion-MNIST

En esta tarea ustedes deben diseñar, entrenar y evaluar un modelo de red convolucional para resolver el problema anteriormente presentado

Implemente una red convolucional con arquitectura Lenet5
Diseñe e implemente una nueva arquitectura de red convolucional que proponga mejoras sobre Lenet5
Para cada arquitectura experimente con distintos optimizadores (SGD, RMSProp y Adam), tasa de aprendizaje y tamaño de batch de entrenamiento
Indicaciones.

### Indicaciones

Separe las imágenes del conjunto de entrenamiento en dos subconjuntos para ajustar los parámetros (entrenamiento propiamente tal) y evitar sobreajuste (validación), respectivamente.
Utilice early stopping, decida experimentalmente la paciencia y el número de épocas de entrenamiento
Implemente un esquema de aumentación aleatoria de datos para el conjunto de entrenamiento, considere al menos recortes aleatorios. Compare contra la opción de no realizar aumentación aleatoria
Compare sus modelos y entrenamientos en base a las curvas de aprendizaje y acompañe sus figuras con observaciones
Evalue la capacidad de generalización de la mejor Lenet5 y red propia midiendo su rendimiento en el subconjunto de prueba. Utilice matrices de confusión y reportes de clasificación (precisión, recall y f1-score). ¿Cuáles clases son más difíciles de clasificar? ¿Cuáles clases tienden a confudirse entre sí?
Reporte el proceso, justifique sus decisiones y discuta sus resultados

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
