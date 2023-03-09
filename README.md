# Lab 5

### Binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aleg001/Lab5-IA/main)


### TASK 1.1 
- Metrica 
    * Nuestro modelo: 0.83683289
    * Modelo con librerias: 0.84

- Descripción de la métrica 
    * Como se puede ver la métrica obtenida fue de 0.8368, se puede decir que esta predicción es muy precisa ya que se acerca a 1. 

- ¿Cuál implementación fue mejor? ¿Por qué?
    *  Como se puede observar en este caso el modelo que tuvo un mejor desempeño es el que nos brindan las librerias. Cabe resaltar que nuestro modelo no se aleja del valor brindado por las librerias lo cual puede atribuirse a que se utilizo el mimso tamaño de prubera al y el mismo  random state. 


### TASK 1.2 
- Metrica 
    * Nuestro modelo: 0.5109361
    * Modelo con librerias: 0.629046

- Descripción de la métrica 
    * Como se puede observar la métrica obtenida fue del 0.5109, en base a esto se puede mencionar que este no fue muy eficiente para realizar predicciones puesto a que el valor obtenido se encuentra por debajo del 70%. 

- ¿Cuál implementación fue mejor? ¿Por qué?
    *  Como se puede ver la implementacion que tuvo un mejor desempeño fue la que hace uso de librerias puesto a que este obtuvo un valor de 0.6290. Esta diferencia se le puede atribuir a la forma en la que se realiza la funcion de predicción principalmente por los pesos que se le asignaron a las muestras. 

### Preguntas Generales
-¿Cómo difirieron los grupos creados por ambos modelos?
    * Los grupos principalmente difieren en que en el modelo KNN estos se generan en base a las instancias vecinas, es decir los puntos más cercanos en base a una instancia. Mientras que con SVM separamos la data en dos clases las cuales en este caso fueron "legitimate" y "phishing"

-¿Cuál de los modelos fue más rápido?
    * En cuanto al tiempo de ejecución que cada algoritmo toma el modelo más rápido fue el de SVM ya que este únicamente tomo 9.55 segundos en ejecutarse; mientras que el modelo KNN se tomo 42.2 segungos en terminar su ejecución 

-¿Qué modelo usarían?
    * 