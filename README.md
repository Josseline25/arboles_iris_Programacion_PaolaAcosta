# arboles_iris_Programacion_PaolaAcosta

Prueba a entrenar el modelo sin limitar la profundidad 
(max_depth=None). ¿Qué notas en las reglas? 

Con max_depth=2:
El árbol genera pocas reglas, las cuales son simples y fáciles de interpretar. 
Las decisiones se basan en pocas características, lo que permite comprender claramente cómo el modelo clasifica las flores.

Con valores mayores de max_depth:
El árbol incrementa el número de nodos y reglas, utilizando más características para tomar decisiones.
Mejora el ajuste a los datos, pero reduce la interpretabilidad del modelo.
Entrenamiento sin limitar la profundidad (max_depth=None)

Al entrenar el modelo sin limitar la profundidad:
El árbol crece de forma considerable, las reglas se vuelven  mas largas y complejas, aparecen muchas condiciones específicas.


Evaluación de la precisión del modelo
El modelo obtiene una precisión alta (generalmente entre 95% y 100%), lo que indica que clasifica correctamente la mayoría de las muestras del conjunto de prueba.

Cuales son tus opiniones de los resultados?

Los resultados obtenidos son satisfactorios, ya que el árbol de decisión logra una alta precisión en la clasificación del dataset Iris.
Al limitar la profundidad del árbol, se obtienen reglas claras y fáciles de interpretar, lo cual es una ventaja importante de este tipo de modelos.

¿La base de conocimiento cumple con los requerimientos?

Sí, la base de conocimiento cumple con los requerimientos para utilizarse en un modelo de árbol de decisiones.

JUSTIFIACIÓN

El dataset Iris es adecuado para un modelo de árbol de decisión porque, contiene características numéricas bien definidas.
Las clases están claramente diferenciadas, no existen valores faltantes, el tamaño del dataset permite un entrenamiento eficiente.


Características

Longitud del sépalo

Ancho del sépalo

Longitud del pétalo

Ancho del pétalo

Clases
Clase 0: Iris-setosa
Clase 1: Iris-versicolor
Clase 2: Iris-virginica


El uso del dataset Iris en un modelo de árbol de decisión es bueno debido a su estructura clara y bien definida.
Limitar la profundidad del árbol mejora la interpretabilidad, mientras que no hacerlo puede provocar sobreajuste, aunque con una mayor precisión aparente.
