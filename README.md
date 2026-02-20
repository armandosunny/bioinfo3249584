# bioinfo3249584

#Respuesta de ejercicios Sofia

#para seleccionar el directoriao de trabajo
setwd("~/Desktop")

# para leer la base de datos
base=read.csv("genes2.csv")

#para leer las 6 primeras filas

head(base)

#para conocer la estructura de la base de datos

str(datos)


#para cambiar una columna del df a factores

base$Tejido <- as.factor(base$Tejido)
[Figure 6.tif](https://github.com/user-attachments/files/25445413/Figure.6.tif)
