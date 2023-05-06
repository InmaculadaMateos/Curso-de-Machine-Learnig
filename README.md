# Curso-de-Machine-Learnig

## DIA 1 - MARTES

### 1_Python
  #### Básico:
  
+ Variables y tipos
+ Listas
+ Operadores
+ Formato de cadena (string)
+ Condiciones
+ Bucles
+ Funciones
+ Diccionarios

 #### Avanzado (Opcional):
    
+ Cadenas (Strings)
+ Generadores
+ Comprensión de listas
+ Tuplas
+ Funciones
+ Avanzado para iteradores
+ Funciones lambda
+ Funciones map
+ filter y reduce

### 2_Condicionales
  #### Condicionales:
   
+ Operadores de comparación
+ ¿Qué es cierto?
+ Ejercicios
  + Ejercicio 1
  + Ejercicio 2
  + Ejercicio 3

### 3_Bucles
  #### Bucles:
    
+ Repetir con while
  + Bucle Infinito
  + Continuar un bucle
+ Iterar con for
  + Ejercicios
+ Generar secuencias de números
  + Bucles anidados 
  + Ejercicios

## DIA 2 - MIERCOLES

### SpaceX - 1 - Data Collection Api v2
  ####  Etapa 1: Obtencion de datos:
  
+ Objetivos
+ Importación de librerias
  + Parte 1: Obtén los datos mediante peticiones GET y crea un dataframe
  + Parte 2: Filtra el dataframe para que solo incluya los lanzamientos de falcon 9
  + Parte 3: Ajustes finales

### SpaceX - 2 - EDA
  #### Etapa 2: Análisis de datos exploratorio:
    
+ Objectivos
+ Importación de librerias
  + Análisis de datos
  + Tarea 1: Calcula el número de lanzamientos en cada plataforma
  + Tarea 2: Calcula el número de lanzamientos para cada órbita 
  + Tarea 3: Calcula el número de diferentes resultados de aterrizaje distingue los exitosos de los fallidos
  + Tarea 4: Crea una columna Class utilizando LandingOutcome Utilizando la columna Class

### SpaceX - 4 - EDA with Data Visualization
#### Etapa 4: Visualización de datos

+ Objetivos: 
  + Importación de librerias.
+ Tarea 1: Ejemplo 
  + Ejercicio 1: Visualiza la relación entre el número de vuelo y la plataforma de despegue. 
  + Ejercicio 2: Visualiza la relación entre masa de la carga y la plataforma
  + Ejercicio 3: Visualiza la relación entre número de vuelos y órbita
  + Ejercicio 4: Visualiza la relación entre órbita y masa de la carga 
  + Ejemplo 2: Visualiza la proabilidad de éxito según la orbita
  + Ejercicio 5: Visualiza la proabilidad de éxito según la plataforma 
  + Ejemplo 3: Visualizar la evolución de la carga con el tiempo
  + Ejercicio 6: Visualización de la probabilidad de éxito en cada mes
 
## DIA 3 - JUEVES

### 06 - Introducción a Machine Learning con Scikit-Learn

+ Introducción a Machine Learning con Scikit-Learn
  + Un primer ejemplo.
    + Ejercicio 1
  + ¿Cómo mejorar nuestro modelo?
    + Ejercicio 2
+ La importancia de los conjuntos test y train.
+ Los Hiperparametros (GridSearchCV)
   + Ejercicio 3

### 09 - Folium
  #### Generando mapas con Python

  + Introducción
+ Importando las librerías
+ Introducción a Folium
  + Ejercicio
  + Stamen Toner Maps
  + Stamen Terrain Maps
    + Ejercicio
+ Mapas con indicadores
+ Mapas de Coropletas

## DIA 4 - VIERNES

### SPACEX2 - 5 - Interactive Visual Analytics con Folium
  #### Etapa 5: Análisis de las ubicaciones de los sitios de lanzamiento con Folium

  + Objetivos
  + Tarea 1: Marcar todos los lugares de lanzamiento en un mapa
    + Crear y añadir folium.Circle y folium. Marker para cada sitio de lanzamiento en el mapa del sitio
+ Tarea 2: Marcar en el mapa los lanzamientos exitosos/fracasados de cada sitio
  + Crea una nueva columna en el dataframe spacex_df llamada marker_color para almacenar los colores de los marcadores basados en el valor 'class
  + Para cada resultado de lanzamiento en el marco de datos spacex df, añadir un folium.Marker a marker cluster 
+ TAREA 3: Calcular las distancias entre un lugar de lanzamiento y sus proximidades

### SPACEX2 - 6 - Machine Learning Predicciones
  #### Etapa 6: Predicción mediante aprendizaje automático
  
+ Objetivos
+ Importar librerias y Definir Funciones Auxiliares
+ Cargar el dataframe
