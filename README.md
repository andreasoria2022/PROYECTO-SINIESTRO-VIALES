# PROYECTO-SINIESTRO-VIALES
PROYECTO SINIESTROS VIALES
Este repositorio es un análisis de datos de los siniestros viales acaecidos en la Ciudad de Buenos Aires durante el período 2016 – 2021. Se procede a detallar las carpetas que contiene:

                                                                                                                             
-![data](https://github.com/andreasoria2022/PROYECTO-SINIESTRO-VIALES/assets/105015078/de5ff90e-1bfc-481a-9a0c-0ab650f0b0e2)  contiene los siguientes archivos:

homicidios.xlsx  es un archivo con extensión xlsx brindado por la página Buenos Aires Data que nos informa sobre los siniestros viales con víctimas fatales ocurridas en la Ciudad desde el año 2016 – 2021.  Los datos incluyen fecha y ubicación 
del hecho y tipo de transporte involucrados.

lesiones.xlsx es un archivo con extensión xlsx brindado por la pagina Buenos Aires Data que nos informa sobre las lesiones en siniestros viales ocurridos en la Ciudad desde el año 2019 – 2021. Los datos incluyen fecha, ubicación del hecho y tipo 
de transporte involucrado.

homicidos.csv este archivo es el resultado de haber realizado el proceso de extracción, transformación y carga de datos  y contiene los datos de los siniestros viales con víctimas fatales ocurridas en la Ciudad de Buenos Aires desde el año 2016 
-2021 

lesiones.csv este archivo es el resultado de haber realizado el proceso de extracción, transformación y carga de datos y contiene los datos de las lesiones de los siniestros viales ocurridas en la Ciudad de Buenos Aires desde el año 2019 -2021 

resumen_EDA.xlsx: este archivo es un resumen del EDA en Excel.

                                                                                                                             
 ![etl](https://github.com/andreasoria2022/PROYECTO-SINIESTRO-VIALES/assets/105015078/4a4fadf3-cb8f-48a4-a301-00fa5b0cac4c)  contiene el siguiente archivo:
 
ETL.ipynb: es un archivo notebook en el que se realiza el proceso de extracción, transformación y carga de los datos de los siniestros viales tanto de lesiones como los que tienen víctimas fatales. Los datos de los siniestros viales con víctimas fatales que fueron extraídos de la página Buenos Aires Data no poseían duplicados y pocos nulos en  datos de la ubicación. Se eliminaron  la columna año, la columna mes y también la columna día ya que la columna fecha contenía toda esta información. En cuanto a los datos de las lesiones de los siniestros viales extraídos de la página Buenos Aires Data no poseía duplicados y si muchos nulos en cuanto a los datos de la ubicación del hecho. De este dataset también se eliminaron  la columna año, la columna mes y también la columna día ya que la columna fecha contenía toda esta información. Este proceso de ETL dio origen a los archivos homicidos.csv y lesiones.csv que fueron incorporados en la carpeta Data.


                                                                                                                            
 ![EDA](https://github.com/andreasoria2022/PROYECTO-SINIESTRO-VIALES/assets/105015078/1d15a0ab-3279-43eb-81a8-33f35d830941)  contiene el siguiente archivo:

EDA.ipynb: es un archivo notebook en los que se realizó el análisis exploratorio de datos de los siniestros viales tanto los que tuvieron víctimas fatales como los que tuvieron lesiones como consecuencia del hecho. Se realizó el análisis de los siniestros por año, según el vehículo que ocupaba la víctima, según el vehículo que ocupaba el acusado del hecho para los cuales se realizaron gráficos de barras también se llevó a cabo el análisis estadístico de las variables numéricas, gráficos de cajas, gráficos de dispersión, mapa de calor, etc.

-	Readme: es un detalle de lo que vamos a encontrar en el repositorio. Y vamos a encontrar un informe. 

Reporte de Análisis.












