# U2A4.-Splits-reproducibles-en-un-dataset-abierto
Aplicar una partición train/test a un dataset abierto usando una semilla fija, para generar archivos reproducibles y explicar la importancia de los splits en la preparación de datos para IA.

### Importancia de splits en un dataset
Los splits de un dataset consisten en dividir un conjunto de datos en diferentes subconjuntos, principalmente: Entrenamiento (train), usado para entrenar el modelo, y Prueba (test), usado para evaluar su desempeño.
- Permiten evaluar qué tan bien generaliza un modelo con datos nuevos
- Evitan el sobreajuste (overfitting)
- Hacen posible comparar modelos de manera justa
- Con una semilla fija (random_state), los resultados son reproducibles
La división de un dataset en conjuntos de entrenamiento y prueba es una etapa fundamental en el desarrollo de modelos de inteligencia artificial. Permite evaluar el desempeño del modelo con datos no vistos previamente, asegurando su capacidad de generalización.

### Nota técnica
- Nombre del dataset: Wine Dataset, caracteristicas quimicas de diferentes tipos de vino.
- Fuente original: repositorio UCI Machine Learning Repository
- Proporción usada en la partición: 80% para entrenamiento y 20% para prueba
- Semilla utilizada: semilla fija con valor 42 mediante el parametro random_state, para que la division de datos siempre sea la misma en cada ejecución del código
- Criterio de division empleado: Aleatorio, ya que los datos fueron distribuidos de forma aleatoria entre los conjuntos de prueba y entrenamiento. 
