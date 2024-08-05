# Laboratorio 1
Este laboratorio de procesamiento de imágenes incluye varias técnicas y experimentos realizados con imágenes utilizando la libreria OpenCV y Matplotlib. Se aplicaron filtros de color a las imágenes, se generó una imagen original a partir de imágenes en escala de grises y se generó las escalas de grises de una imagen, así mismo se investigo y aplicó la escala de grises ponderada. Por ultimo, se investigó sobre el espacio de color HSV.  

# Archivos
1. LAboratorio1.pdf - Instrucciones.
2. Laboratorio1.ipynb - Solución a las instrucciones.
3. imagen1 - Carpeta con imágenes a tratar para problema 2.
4. imagen2 - Carpera con imágenes a tratar para problema 2.
5. perro - Carpeta con imágenes a tratar para problema 2. 
6. prueba.jpg - Imagen a utilizada en el laboratorio.
7. prueba_azul.jpg - Imagen resultante aplicando filtro.
8. prueba_rojo.jpg - Imagen resultante aplicando filtro.
9. prueba_verde.jpg - Imagen resultante aplicando filtro.

# Librerias requeridas
* cv2
* numpy
* matplotlib

# Descripción de Funciones
1. problema_uno(dir_img, color): aplicar filtros de color a una imagen.
2. problema_dos(dir_img1, dir_img2, dir_img3): permite generar una imagen a color a partir de tres imágenes en escala de grises. 
3. problema_tres(dir_img): genera y guarda las imágenes en escala de grises.
4. problema_cuatro(dir_img): genera el histograma de cada canal de color y de escala de grises. Incluyendo linea de media.
5. problema_cinco(imagen_ponderada): aplica la conversión a escala de grises ponderada.

# Ejemplos de uso
### Problema 1  
```python
dir_imagen = "prueba.jpg"
prueba_azul = problema_uno(dir_imagen, 4)
```
### Problema 2  
Ejemplo utilizando 'imagen1'  
```python
dir_img1 = "imagen1/imagen1_salida_gray_rojo.jpg"
dir_img2 = "imagen1/imagen1_salida_gray_verde.jpg"
dir_img3 = "imagen1/imagen1_salida_gray_azul.jpg"
prueba_dos = problema_dos(dir_img1, dir_img2, dir_img3)
```

### Problema 3   
```python
dir_img = "prueba.jpg"
prueba_tres = problema_tres(dir_img)
```

### Problema 4   
```python
dir_img = "prueba.jpg"
prueba_tres = problema_cuatro(dir_img)
```

### Problema 5   
```python
dir_img = "prueba.jpg"
prueba_cinco = problema_cinco(dir_img)
```