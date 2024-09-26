# Proyecto Text Mining & Image Recognition

El proyecto abarca ejercicios donde se aplican ténicas de Text Mining & Image Recognition.  

### Archivos
1. word_cloud.ipynb - Solución ejercicio 1
2. f_v_recognizer.ipynb - Solución ejercicio 2
3. modelo_1.keras - Modelo 1, ejercicio 2
4. modelo_2.keras - Modelo 2, ejercicio 2
5. modelo_3.keras - Modelo 3, ejercicio 2  
<span style="color: red"> No sé cargo tw_source.csv </span>
<span style="color: red"> No sé cargo Fruits_Vegetables_Dataset(12000) </span>  


## Ejercicio 1
En este ejercicio se utilizó un dataset que contiene tweets. El objetivo es identificar los 3 usuarios más famoso. Después, se realiza procesamiento como Stemming y Lemmatization en los tweets para reducir las palabras a su forma base y de esta manera, creamos un wordcloud con las 10 palabras más frecuentes para cada uno de los usuarios más populares.

Librerías
- Pandas
- Matplotlib
- Re
- Nltk
- Wordcloud
- Collections

## Ejercicio 2
En este ejercicio se utilizó un dataset de frutas y vegetales para realizar un modelo de reconocimiento de imágenes. Para empezar, se aplica aumento de datos y preprocesamiento. Luego se entrena y evaluamos 3 arquitecturas diferentes de redes neuronales convolucionales para clasificar las imágenes.  

Modelo 1: 
- MaxPooling2D
- (3, 3) filtos (kernel)
- 128 y 64 neuronas  
Precisión del modelo: 92.12%

Modelo 2: 
- AveragePooling2D
- (5, 5) filtros (kernel)
- 128 y 64 neuronas
Precisión del modelo: 61.47%

Modelo 3:
- MaxPooling2D
- (7, 7) filtros (kernel)
- 256 y 128 neuronas
Precisión del modelo: 61.47%  
  

Librerías
- Numpy
- Matplotlib
- Os
- Tensorflow
- Sklearn
- Keras