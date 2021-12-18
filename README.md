# Clasificador-FIFA19
Autores: [Carlos Golvano](https://github.com/CarlosGolvano), [Carlos Yanguas](https://github.com/c-yanguas), [Jorge Casajus](https://github.com/jogecodes).


Para una correcta comprensión de los objetivos de este proyecto así como la evolución del mismo, es muy aconsejable la lectura de [documentación.pdf](https://github.com/c-yanguas/Clasificador-FIFA19/blob/main/Documentacion.pdf).

De manera resumida, el objetivo de este proyecto es mostrar el proceso de convergencia de modelos basados en redes neuronales durante la fase de entrenamiento. Para ello, se irán cambiando los principales hiperparámetros:
- Learning rate
- Número de épocas
- Tamaño de batch
- Número de capas y de neuronas por capa
- Funciones de activación
- Regularización:
  - Dropout
  - Normalización de batch
  - Regularización L2

Además, se mostrará como interpretar las gráficas de entrenamiento de los modelos, junto con los cambios que pueden ser oportunos para el mismo.

- Es relevante destacar que el [conjunto de datos brutos](https://github.com/c-yanguas/Clasificador-FIFA19/blob/main/FootballPlayerRawDataset.csv) cuenta con el orden de 20.000 datos, los cuales representan los valores de las características asociadas a los jugadores profesionales de fútbol para el videojuego FIFA19, por lo que este proyecto solo se centra en el ajuste de hiperparámetros, no en la construcción óptima de un modelo predictor. Así pues, también se expone en la  que otros enfoques basados en aprendizaje automático son óptimos.
- Otra circunstancia a tener en cuenta es que el conjunto de datos puede ser preprocesado mediante diferentes enfoques, también demostramos la importancia de esta fase, existiendo hasta un 9% de diferencia entre modelos entrenados por diferentes conjuntos de datos.
- Dejamos a continuación el conjunto de características obtenidas mediante diferentes umbrales de correlación respecto de la variable a predecir 'Overall', de manera resumida son:
  -   [atributos con correlación >= 50%](https://github.com/c-yanguas/Clasificador-FIFA19/blob/main/Preprocesado/atributos50.csv) | [etiquetas asociadas](https://github.com/c-yanguas/Clasificador-FIFA19/blob/main/Preprocesado/etiquetas50.csv)
  -    [atributos con correlación >= 60%](https://github.com/c-yanguas/Clasificador-FIFA19/blob/main/Preprocesado/atributos60.csv) | [etiquetas asociadas](https://github.com/c-yanguas/Clasificador-FIFA19/blob/main/Preprocesado/etiquetas60.csv) --> Opción recomendada
  -   [atributos con correlación >= 70%](https://github.com/c-yanguas/Clasificador-FIFA19/blob/main/Preprocesado/atributos70.csv) | [etiquetas asociadas](https://github.com/c-yanguas/Clasificador-FIFA19/blob/main/Preprocesado/etiquetas70.csv)



 
