# Predicción de planes telefónicos que se adaptan a las necesidades del cliente según su comportamiento.
La compañía móvil Megaline no está satisfecha al ver que muchos de sus clientes utilizan planes heredados. Quieren desarrollar un modelo que pueda analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: Smart o Ultra.


## ¿Plan Smart o Ultra? Un modelo de clasificación para hacer las recomendaciones correctas
El objetivo de este proyecto es crear un modelo de Machine Learning con un umbral de exactitud de 0.75 que escoja el plan correcto para los clientes, esto con ayuda de los datos de comportamiento de los suscriptores que ya se han cambiado a los planes nuevos.

Tras evaluar distintos modelos supervisados de clasificación para machine learning -entre ellos árboles de decisión, bosques aleatorios y regresión logística—, el mejor desempeño se logró con un modelo de **bosque aleatorio** configurado con **n_estimators=8 y max_depth =10.** Este modelo alcanzó aproximadamente un 0.82 de exactitud en el conjunto de prueba, superando holgadamente el umbral requerido de 0.75. Además, la prueba de cordura con un modelo Dummy confirmó que el modelo seleccionado aprende relaciones útiles, ya que su exactitud fue superior a la de una predicción trivial.
