# ProyectoFinalMaestriaDS
Repositorio de información Proyecto Final Maestría en Ciencia de Datos y Analítica

Proyecto: Identificación de anomalías en el aislamiento de líneas de transmisión a partir de imágenes

Daniel Alonso Sánchez Echeverri

Maestría en Ciencias de los Datos y Analítica
Universidad EAFIT

======================================================================

En este repositorio se encuentran los códigos fuente (scripts de Python) construidos durante el desarrollo del proyecto de maestría.
Adicionalmente, se incluyen algunas imagenes de validación del funcionamiento de los modelos implementados.

En el repositorio se Encuentran 2 carpetas

1. Notebooks
     - Modelado Identificacion_segmentacion_clasificacion.ipynb --> Notebook con el desarrollo paso a paso de cada una de las etapas del modelado.
     - Pipeline_Identificacion_segmentacion_clasificacion.ipynb --> Pipeline construido para que recoba una imágen de una cadena de aisladores y entregue como resultado una carpeta con las imágenes de cada plato de aislamiento clasificado en "Normal" o "Con anomalía"
  
       
2.Imágenes
     - Clasificacion Aislamiento en Buenas Condiciones --> Contiene una imagen de una cadena de aisladores en buen estado, y una imagen de cada plato de aislamiento con el resultado de la predicción (Class: Normal)
     - Clasificacion Aislamiento en Malas Condiciones --> Contiene una imagen de una cadena de aisladores en mal estado, y una imagen de cada plato de aislamiento con el resultado de la predicción (Class: Anomalía)
