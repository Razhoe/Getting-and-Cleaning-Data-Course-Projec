# Getting-and-Cleaning-Data-Course-Projec

 *Este es el proyecto del curso para el curso Obtención y limpieza de datos de Coursera.
 *El script R incluido, run_analysis.R, realiza lo siguiente:

  *Descargue el conjunto de datos de la web si aún no existe en el directorio de trabajo.
  
  *Lea los conjuntos de datos del tren y de la prueba y combínelos en x (medidas), y (actividad) y sujeto, respectivamente.
  
  *Cargue la función de datos (x), la información de la actividad y extraiga las columnas denominadas "mean" (- mean) y "standard" (- std). Además, modifique los nombres de las columnas a descriptivos. (-mean to Mean, -std to Std, y elimine símbolos como -, (,)).
  
  *Extraiga los datos por columnas seleccionadas (del paso 3) y combine x, y (actividad) y los datos del sujeto. Además, reemplace la columna y (actividad) por su nombre haciendo referencia a la etiqueta de actividad (paso 3 cargado).
  
  *Genere un "Conjunto de datos ordenado" que consista en el promedio (media) de cada variable para cada tema y cada actividad. El resultado se muestra en el archivo tidy_dataset.txt.
