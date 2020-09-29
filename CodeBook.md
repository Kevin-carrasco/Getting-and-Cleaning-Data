Español: 
El Script Run_analysis posee el desarrollo de los 5 pasos 
descritos en el proyecto del curso.

En primer lugar, todos los archivos con el mismo número de columnas 
y que son del mismo tipo son combinados utilizando la función rbind()

Luego las variables con las medias y los promedios de desviación estándar 
son extraídos del conjunto de datos. Se le asignan los nombres de las variables de features.txt

Como todos los datos poseen valores entre 1:6, los nombres e ID de las 
actividades de activity_labels.txt son copiadas en el conjunto de datos.

Después se corrigen nombres de las columnas y, finalmente, se genera un último conjunto de 
datos que incluye los promedios para cada tema y para cada actividad. Este archivo se llama Base.txt


Variables

x_train, y_train, x_test, y_test, subject_train & subject_test
contienen los datos originales descargados de Internet.

x_base, y_base & subject_base combinan los datos originales.

features posee los nombres de las variables de features.txt

base combina x_base, y_base & subject_base en un solo conjunto de datos

Mean.Base agrupa los promedios por tema y actividad mediante la función group.by.

Mediante la función write.table es generado el archivo "Base.txt" que contiene a Mean.Base
############################################################################################

ENG:
The Run_analysis Script has the development of the 5 steps
described in the course project.

First, all files with the same number of columns
and that are of the same type are combined using the rbind () function

Then the variables with the means and the averages of standard deviation
are extracted from the data set. Variable names are assigned from features.txt

As all the data have values ​​between 1: 6, the names and IDs of the
activities from activity_labels.txt are copied into the dataset.

Then column names are corrected and, finally, a last set of columns is generated.
data including averages for each topic and for each activity. This file is called Base.txt


Variables

x_train, y_train, x_test, y_test, subject_train & subject_test
contain the original data downloaded from the Internet.

x_base, y_base & subject_base combine the original data.

features owns the names of the variables from features.txt

base combines x_base, y_base & subject_base into a single dataset

Mean.Base groups averages by topic and activity using the group.by function.

By means of the write.table function the file "Base.txt" is generated which contains a Mean.Base
