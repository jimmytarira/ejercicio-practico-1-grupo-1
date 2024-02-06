# ejercicio-practico-1-grupo-1
Se descargaron los archivos mnist_train.csv y mnist_test.csv adjuntos.
Se trabajó con el archivo mnist_train.csv
Se creó 2 nuevas característica: "cuanto_mancha" y "simetia".
La simetría se la realizó restando la parte de arriba menos la parte de abajo.
Para crear el modelo y entrenarlo se tomaron las 2 características nuevas creadas.
Se eligió el modelo de regresión lineal.
Una vez entrenado el modelo se lo evaluó con la matriz de confusión de sklearn. 
Se dibujó la matriz de confusión lo que nos ilustra que las características elegidas no son suficiente
para que se reconozcan los números
