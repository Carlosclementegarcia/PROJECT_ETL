# PROJECT_ETL

A. INTRODUCCIÓN

El objeto de este repo es escrapear tablas, con dos metodos y tres dataframe diferentes, varias páginas web.
Mi trabajo se va a complementar con el trabajo final que voy a titular " Iglesia católica y cash: repercusión ".

B. PROCESO

1. SCRAPPING: Escrapeo 2 páginas web de la Archidiócesis de Madrid, dentro de una pestaña denominada "Transparencia", en ella se 
una supuesta tabla de excel, con un descargable con los datos de 2021 y creo un código con la librería Selenium, a fin de que se haga click 
de manera automática y se descarge la tabla excel. Una vez descargada, visualizo la tabla, limpio algunas filas con nulos y tras ese proceso,
paso el fichero .xlsx a .csv.Ya tengo el fichero preparado para pasar a Mysql workbench. Procedo de la misma manera para descargar otra tabla 
con el año 2020 y realizo la misma operación, ya que las tablas son similares. Preparo otro fichero de la misma manera que contiene datos de los
templos que existen en Madrid, este es un fichero que pasado a csv, tiene un aspecto pésimo y parece poco manipulable. A fin de cumplir con el trabajo encargado, procedo a trabajar con una página web de facebook que escrapeo directamente de una API,que tiene una dimensión de (50,10)

2. EXPORT TO SQL: Importo desde Mysql workbench, los tres csv, creo las tablas, realizo el Reverse engineering y es ahí donde me doy cuenta que las tablas de la archidiocesis, no están organizadas con columnas y que los índices están en las filas. Lamentablemente deberé de cambiar todo, aunque el trabajo está realizado.

3. QUERIES: No las puedo realizar por no tener los índices adecuados.


C. LIBRERIAS

PANDAS
SELENIUM WEBDRIVER
WEBDRIVER CHROMDRIVER MANAGER
SELENIUM WEB DRIVER COMMON   BY WEB DRIVER
PANDAS
REQUEST
XLRD





