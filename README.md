El participante deberá entrenar dos modelos de redes neuronales para resolver el
problema de clasificación de rostros de Labeled Faces in the Wild (LFW), usando un
subconjunto del dataset homónimo disponible en scikit-learn; este subconjunto está
conformado por los 7 personajes que tienen 70 o más imágenes disponibles dentro del
dataset.
El primer modelo debe ser una red densa y el segundo modelo una red convolucional.
Separe el dataset en conjuntos de entrenamiento y prueba utilizando el comando
train_test_split; la fracción de datos de prueba debe estar entre 20% y 30%. Con cada
uno de los modelos, debe obtenerse una precisión (accuracy) de al menos 90% sobre
el conjunto de entrenamiento y al menos 80% sobre el conjunto de prueba. Además
de la precisión total sobre los conjuntos de entrenamiento y prueba, evalúe el
desempeño de los modelos utilizando la matriz de confusión sobre el conjunto de
prueba. Las etiquetas (labels) de la matriz de confusión deben ser los nombres de los
personajes. Comente los resultados obtenidos.
