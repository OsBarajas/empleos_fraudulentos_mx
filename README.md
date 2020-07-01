# empleos_fraudulentos_mx
Se utiliza un dataset que contiene una variedad de empleos publicados por diferentes compañías para múltiples áreas profesionales. 
Se analiza la descripción de cada oferta mediante modelos de Procesamiento de Lenguaje Natural (NLP). 
Se genera un mapa de las palabras con (Stopwords) que contienen elementos que den paso a posibles empleos de origen desconocido o fraudulentos y una correlación.

Contenido:

NOTEBOOKS: 

  1_Empleos_Falsos_WordCloud_Dataset.ipynb
  2_Empleos_falsos_Exploracion_Analisis_y_visualizacion_datos
  3_Empleos_Falsos_Predicciones_ML

CARPETAS: 

 /datasets
  job_es -------------------------> Excel con datos descriptivos al que se agregaron columnas de longitud y latitud con Google Maps API, así como nombre de Estados
  geografia_empleos_MX -----------> CVS limpio ya con longitud y latitud donde se aplica Exploración, Análisis y Visualización de los datos 
  dataset_limpio_empleos ---------> CVS alineado para aplicar los modelos ML-NLP
  
  /datasets/datasets_origen
  * ------------------------------> Todos los archivos utilizados originalmente al que se les aplicaron diversos tratamientos de limpieza. 
  /visualizaciones
  * ------------------------------> Visualización del análisis exploratorio del dataset. 
  
  
  


