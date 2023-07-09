# FINAL_IMG_UIDE
CLASIFICADOR TIPO DE CARNES
En este proyecto, se muestra cómo utilizar una Red Neuronal Convolucional (CNN) en Python utilizando la biblioteca TensorFlow. El código se divide en varias secciones para realizar tareas como la importación de imágenes, entrenamiento del modelo, evaluación y predicción.

1. Importación de Imágenes
El código comienza con la importación de imágenes desde una carpeta local en la pc. Utilizando TensorFlow y su función flow_from_directory, las imágenes se cargan y se dividen en conjuntos de entrenamiento y se  prueba, las imágenes también se redimensionan a un tamaño específico para que coincida con el formato de entrada esperado por la CNN.
"D:\Tdatos\train" y "D:\Tdatos\test"

2. Definición del Modelo de la CNN
La definición de la CNN se realiza utilizando la biblioteca Keras, que es una API de alto nivel para construir modelos de redes neuronales. En el código generado, se utiliza la secuencialidad de Keras para construir un modelo de red neuronal convolucional.
En la definición del modelo, se agregan capas de convolución y pooling para extraer características de las imágenes. Luego, se aplana la salida y se conecta a capas densas para realizar la clasificación final. Se utilizan activaciones 'relu' en las capas de convolución y densas, y una activación 'softmax' en la capa de salida para la clasificación multiclase.

3. Entrenamiento del Modelo
El entrenamiento del modelo se realiza utilizando el método fit de Keras. En el código generado, se compila el modelo con una función de pérdida, un optimizador y una métrica de evaluación. Luego, se ajusta el modelo a los datos de entrenamiento durante un número determinado de épocas.
Durante el entrenamiento, se muestra información sobre la precisión y la pérdida en cada época. Esto permite monitorear el progreso del entrenamiento y verificar si el modelo está mejorando con el tiempo.

4. Evaluación del Modelo
Una vez entrenado el modelo, se evalúa su rendimiento utilizando los datos de prueba. Se calcula la precisión y la pérdida del modelo en el conjunto de prueba para obtener una medida objetiva de su desempeño.
Para evaluar el rendimiento del modelo, se utilizan las matrices de confusión. 
En el código generado, se muestra cómo utilizar la función confusion_matrix para calcular la matriz de confusión para los datos de entrenamiento y de prueba. También se muestra cómo visualizar la matriz de confusión como un mapa de calor, o como una tabla utilizando la biblioteca pandas.

5. Predicción con una Imagen Individual
Finalmente, se proporciona un código para realizar una predicción utilizando una imagen individual. El usuario debe colocar una imagen en la ruta indicada en su  PC, y el modelo cargado se utiliza para predecir la clase de la imagen. Se muestra la clase real y la clase predicha, y también se muestra la imagen en sí para una mejor comprensión visual.

Conclusion
El uso de redes neuronales convolucionales con tensorflow son muy flexibles y eficientes para el procesamiento de datos visuales, su capacidad de aprendizaje, robustez, hacen que las CNNs sean muy buenas para ser utilizadas en una variedad de aplicaciones parael reconocimiento de patrones, vision de computadora
