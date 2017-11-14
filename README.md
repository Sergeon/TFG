# TFG

## Clustering para mejora de prestaciones

Con este notebook intentaremos ilustrar y comprender el uso de clustering para la mejora de prestaciones de un modelo de machine learning concreto. Aplicaremos dos de los algorítmos más utilizados, **k-means** y **DBSCAN**, para clasificar por grupos y aplicar un modelo diferente (o no) para cada uno de esos grupos. Por último comprobaremos si realmente mejora o no la precisión de nuestro predictor, comparándolo con soluciones anteriores del proyecto.

### Tareas hechas hasta ahora

- Aprender sobre **scikit-learn**, **pandas** y **numpy** principalmente.
- Extracción de los datos de Kaggle, concretamente de la [European Soccer Database](https://www.kaggle.com/hugomathien/soccer)
- Limpieza del dataset.
- Tratado de los datos para obtener las *features* que necesitamos.
- Mapeo de los *ratings* de los jugadores para cada partido, teniendo en cuenta las fechas de los mismos.
- Representación del mapa de puntos (partidos), enfrentando los *ratings* de ambos equipos.
- Representación de las correlaciones entre las variables.
- Aprender como funcionan **k-means** y **DBSCAN** para poder aplicarlos.
- Añadir un mayor número de *features*, ya que el modelo de 5 es muy simple y no tiene sentido hacer clustering por variables ni *feature selection*.
  - Desagregar las variables, de los ratings pueden salir 22 (1 por jugador) y de las apuestas 18 (6 por cada signo de la quiniela).
  - Explorar más el *dataset*, atributos de jugadores y equipos.
- Ordenar las variables de cada grupo en función cómo correlan con la variable que queremos predecir.
- Hacer todas las combinaciones de modelos de manera que para cada modelo se utilice una variable de cada grupo.
- Ordenar todos los modelos por *accuracy* y hacer la elección.
- Aprender como funcionan los *ensemble methods*
- Aplicar un *ensemble method* a la salida de todos los modelos para hacer la predicción final y ver el resultado

### Tareas que quedan por hacer

- Ninguna

### Tareas bloqueantes

- Ninguna
