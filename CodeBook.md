El Script Run_analysis posee el desarrollo de los 5 pasos descritos en el proyecto del curso.
En primer lugar, todos los archivos con el mismo número de columnas y que son del mismo tipo son combinados utilizando la función rbind()
Luego las variables con las medias y los promedios de desviación estándar son extraídos del conjunto de datos. Se le asignan los nombres de las variables de features.txt
Como todos los datos poseen valores entre 1:6, los nombres e ID de las actividades de activity_labels.txt son copiadas en el conjunto de datos.
Después se corrigen nombres de las columnas y, finalmente, se genera un último conjunto de datos que incluye los promedios para cada tema y para cada actividad. Este archivo
se llama Base.txt

Variables
x_train, y_train, x_test, y_test, subject_train & subject_test contienen los datos originales descargados de Internet.
x_base, y_base & subject_base combinan los datos originales.
features posee los nombres de las variables de features.txt
base combina x_base, y_base & subject_base en un solo conjunto de datos
Mean.Base agrupa los promedios por tema y actividad mediante la función group.by.
Mediante la función write.table es generado el archivo "Base.txt" que contiene a Mean.Base
