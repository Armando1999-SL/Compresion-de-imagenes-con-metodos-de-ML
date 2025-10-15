# Compresión de imágenes mediante métodos de Machine Learning

En este proyecto se emplean técnicas de *Machine Learning* con el objetivo de reducir el tamaño de las imágenes, buscando preservar la mayor calidad visual posible.

## Metodología

Se implementaron dos enfoques principales para la compresión de imágenes:

- **Análisis de Componentes Principales (PCA):**  
  Este método permite reducir la dimensionalidad de los datos de la imagen. Se evaluaron distintos valores para el número de componentes principales, con el fin de determinar la configuración que optimizara la relación entre compresión y calidad.

- **Clusterización con k-means:**  
  En este enfoque se aplica *k-means* sobre la gama de colores de la imagen, agrupándolos en *n* clústeres. Al disminuir la cantidad de colores únicos, se reduce significativamente el tamaño del archivo manteniendo una representación visual adecuada.

## Resultados

Ambos métodos ofrecieron resultados consistentes y satisfactorios, logrando reducir el tamaño de las imágenes de prueba en aproximadamente un **50 %**, sin evidenciar una pérdida perceptible en la calidad visual.

## Archivos del repositorio

- **codigo.ipynb:**  
  Contiene la implementación detallada de los dos métodos descritos.

- **pictures:**  
  Carpeta que incluye la imagen de prueba utilizada en los experimentos, junto con las versiones comprimidas generadas mediante ambos enfoques.

- **reporte.pdf:**
  Documento donde se reportan los resultados obtenidos.
