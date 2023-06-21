![Portada](https://www.dqsconsulting.com/wp-content/uploads/2021/09/como-hacer-un-analisis-de-datos.jpg)

<h1 align="center">  MOOC (Massive Open Online Course) </h1>

## 📋 Indice
1. [Descripcion del proyecto](#descripcion)
2. [Flujo de Trabajo](#workflow)
3. [Contenido del Repositorio](#con)
4. [Análisis Exploratorio de Datos (EDA).](#eda)
5. [Dashboard.](#dash)
6. [Dependencias](#depen)


## 1. Descripcion del proyecto <a name="descripcion"></a>

El siguiente proyecto es parte de las practicas de la academia SoyHenry y consta de la realización de un análisis de datos con la consecuente creción del dashboard que materialice la información obtenida. El rol prioritario que se realiza es el de Data Analist, teniendo como objetivo poder generar insights y conocimiento proscriptivo a partir de datos.

## 2. Flujo de trabajo <a name="workflow"></a>

El workflow del proyecto consta de un mínimo proceso de ETL, sobre todo de extracción de datos, creación de variables nuevas y webscrapping para la recolección de datos faltantes. Luego, sigue la etapa de EDA (Analisis Exploratorio de Datos), en la cual se analiza con mayor detalle la información, buscando cruzar variables importantes con el fin de generar nueva información. Por último, con la nueva información obtenida y un crecimiento en el conocimiento del negocio y la temática, se creó un dashboard en PowerBI que sintetiza las conclusiones mas pertinentes y permite mostrar los KPI elegidos. 

## 3. Contenido del Repositorio <a name="con"></a>

El repositorio cuenta con:

+ **EDA.ipynb**: notebook donde se realizó el EDA
+ **Datasets**: carpeta que contiene los CSV con los que se realizo el proyecto
+ **Dashboard**: carpeta que contiene el dashboard creado en PowerBI
+ **Dashboard Udemy.pbix**: dashboard interactivo

## 4. Análisis Exploratorio de Datos (EDA). <a name="eda"></a>

La etapa de EDA puede encontrarse en el siguiente [Link](https://github.com/RoNovau/MOOC/blob/main/EDA.ipynb).

## 5. Dashboard <a name="dash"></a>

En el siguiente [Link](https://github.com/RoNovau/MOOC/blob/main/Dashboard/Dashboard%20Udemy.pbix) puede verse el Dashboard realizado, y debajo puede observarse una imagen a título ilustrativo: 

![Dashboard](https://github.com/RoNovau/MOOC/blob/main/assets/Dashboard_img.jpeg)

En él se pueden observar las métricas y KPI planteados:

* Tasa de conversión
* Ventas totales
* Total de suscriptores/inscriptos
* Precio promedio de los cursos
* Promedio de venta por cliente

Además de algunas gráficas ilustrativas de la información recopilada:

* Distribución de ventas por temática
* Distribución de ventas por año
* Cantidad de cursos por año y por temática
* Top 10 cursos más vendidos

## 6. Dependencias <a name="depen"></a>

Para este proyecto se utilizaron las siguientes librerias de Python:

- pandas
- numpy
- seaborn
- matplotlib
- sklearn
- wordcloud
- datetime
- requests
- beatifulsoup
