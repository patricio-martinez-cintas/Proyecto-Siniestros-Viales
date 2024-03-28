 # <h1 align="center">**`Siniestros viales - C.A.B.A`**</h1>

<p align='center'>
<img src = 'https://static.lajornadaestadodemexico.com/wp-content/uploads/2022/08/Siniestros-viales.jpg' height = 500>
<p>

## **Descripción del proyecto**

El objetivo de este proyecto es a travez de un archivo de tipo excel sedido por la pagina del gobierno de la Ciudad de Buenos Aires: [Buenos Aires Data](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales) titulado 'homicidios', realizar mediciones de 3 KPI que establezcamos y visualicemos los resultados a travéz de Power BI.


## **Pasos del proyecto que se realizo**

**Analisis exploratorio de los datos:**
En primer lugar, se centró en leer, preparar y realizar un análisis exploratorio de las bases de datos de siniestros viales de CABA con Python y sus librerías de Pandas, Matplotlib y Seaborn. Esto incluyó la generación de un DataFrame final combinado para facilitar su uso en Power BI.

+ [EDA y Preparación](/EDA%20y%20Preparacion/EDA.ipynb)

**Se establecieron los KPI:**
 Las KPS que se propucieron fueron:
 * 1ro) Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.
 
* 2do) Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

* 3ro) Reducir en un 20% la cantidad de accidentes mortales de motocicletas entre el rango etario(18-35) en el ultimo semestre en CABA comparando el en el semestre anterior. 

**importación de la base de dato preparada a Power BI y transformación en Power Query:** Se importó la base de datos ya preparada previamente y se realizaron todas las transformaciones necesarias en Power Query para llevar a cabo las métricas necesarias y realizar las mediciones de KPI.

**Creación de las visualizaciones en los dashboard:**
Se crearon los diferentes dahsboard para visualizar la información obtenida de los datos donde se realizo una vista general de los homicidios, un segundo dashboard se visualiza la tasa de homicidios y finalmente se creo un tercer dashboard  donde visualizamos los accidentes de motos.

