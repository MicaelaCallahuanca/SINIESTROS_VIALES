# PI 02: Análisis de Datos de Siniestros Viales en la Ciudad de Buenos Aires

---

![img siniestros viales](src/portada_pi_dos.jpg)


## Introducción:

En el Proyecto Integral de Análisis de Siniestros Viales en la Ciudad Autónoma de Buenos Aires (CABA), se presenta una iniciativa colaborativa con el Observatorio de Movilidad y Seguridad Vial (OMSV). El propósito de este es realizar un análisis exhaustivo de datos relacionados con siniestros viales ocurridos entre los años 2016 y 2021. Consiste en proporcionar información valiosa que permita a las autoridades locales tomar medidas efectivas para reducir el número de víctimas fatales en accidentes de tráfico.

## Contexto:

En Argentina, entre 2018 y 2022, se registraron 19.630 muertes en accidentes de tráfico en todo el país, lo que equivale a un promedio de 11 personas fallecidas por día. Estas estadísticas evidencian una problemática que afecta a nivel nacional, siendo esencial abordarla de manera específica en la Ciudad de Buenos Aires debido a la alta tasa poblacional que presenta y circula por día. El proyecto se enfoca en analizar los siniestros viales en CABA, identificando patrones, tendencias y factores clave que puedan contribuir a la toma de decisiones informadas. Se busca comprender la dinámica de estos incidentes, desde aspectos temporales y geográficos hasta la influencia de diferentes tipos de vehículos y actores en las vías públicas.


## Descripción del Proyecto:

El principal objetivo  de este proyecto es identificar información importante que pueda ayudar a reducir los accidentes fatales en la ciudad de Buenos Aires. Para lograrlo, se llevó a cabo un análisis integral de los datos proporcionados por el Departamento de Transporte, la Subsecretaría de Planificación de Movilidad y la Oficina de Supervisión de Movilidad y Seguridad Vial (OSMV), de 2016 a 2021. 

Los datos fueron extraidos  de la siguiente página: 
- https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales

# Tecnologías usadas

El proyecto hace uso de diversas tecnologías y herramientas para realizar un análisis exhaustivo de los siniestros viales. Algunas de las principales tecnologías utilizadas fueron:

[![Visual Studio Code](https://img.shields.io/badge/IDE-Visual%20Studio%20Code-blue)](https://code.visualstudio.com/) 
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-brightgreen)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-blue)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Library-Seaborn-yellow)](https://seaborn.pydata.org/)
[![GitHub](https://img.shields.io/badge/Platform-GitHub-lightgrey)](https://github.com/)
[![Git](https://img.shields.io/badge/Version%20Control-Git-blue)](https://git-scm.com/)
[![Power BI](https://img.shields.io/badge/BI%20Tool-Power%20BI-yellow)](https://powerbi.microsoft.com/)

## Desarrollo del proyecto

**EDA** :En el análisis exploratorio de datos (EDA) se analizó detalladamente, valga la redundancia, los datos. Se identificaron los duplicados y nulos aunque no se eliminaron debido a que un analista de datos no elimina data, sino, la analiza y luego en power bi la excluye. Se vieron los outliers,se separaron las variables para poder realizar gráficos y matricez y se pudo ver datos que no corcondaban, por ejemplo, aparecia una comuna cero cuando no existia. Los detalles se pueden ver en el [EDA](https://github.com/MicaelaCallahuanca/SINIESTROS_VIALES/blob/main/EDA.ipynb)



**Dashboard**:

En el programa Power BI  se crearon  páginas. En estas se hicieron un análisis por ubicación, temporal y de victimas. Además se agregaron unos KPI (indicadores clave de desempeño) para poder llegar al objetivo, que es la disminución de los accidentes por siniestros viales.
Recomendamos descargar el panel para acceder a la información más detallada y  una experiencia interactiva. [Dashboard](https://github.com/MicaelaCallahuanca/SINIESTROS_VIALES/blob/main/pi02_siniestros_viales.pbix)



## Hallazgos


- El tipo de vehículo más usado por las víctimas es la moto

- Los accidentes se redujeron significativamente en el año 2020, posiblemente debido al confinamiento por el covid-19

- El mes con mayor cantidad de accidentes es en diciembre

- La mayor cantidad de accidentes se registraron los fines de semanas (viernes, sábado, domingo)

- Las 7 de la mañana es el horario con mayor cantidad de accidentes

- Hay más víctimas del género masculino que del género femenino. La mayoría del género femenino son acompañantes

- Las víctimas tienen entre 20 y 40 años


## KPI

### Primer KPI

**Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.**

Definimos a la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100


Se dío un aumento en accidentes de motociclistas en 2021 con respecto a 2020 es un resultado muy negativo, y está muy lejos de la meta de disminuir un 7% los accidentes de motociclistas.

### Recomendaciones para mejorar este KPI

- instalar cámaras de seguridad para identificar y sancionar a los conductores que cometan infracciones que puedan causar accidentes.

- En los casos en los que la víctima iba en moto, mayormente era el que iba conduciendo por lo que es necesario endurecer los requisitos para obtener el permiso para conducir ese tipo de vehículo. Esto podría incluir requisitos de edad mínima para conducir más estrictos, mayor tiempo de formación teórica y práctica y pruebas más rigurosas.

### Segundo KPI

**Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.**

Definimos a la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico. Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000

Hubo una reducción, en el primer sementre se regitraron 54 víctimas y en el segundo 42

### Recomendaciones para mejorar el KPI

- controles policiales de alcoholemia
- revisión de papeles para verificar que el vehículo está en condiciones para circular
-escaneo de patente para verificar si cometío alguna infracción 

### Tercer KPI 
**Reducir en un 15% la cantidad de accidentes mortales de peatones en el último año, en CABA, respecto al año anterior.**

Definimos a la cantidad de accidentes mortales de peatones en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas peatones en un determinado período temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas peatones es: (Número de accidentes mortales con víctimas peatones en el año anterior - Número de accidentes mortales con víctimas peatones en el año actual) / (Número de accidentes mortales con víctimas peatones en el año anterior) * 100

En el año 2019 hubo un total de 34 víctimas, esto se mantuvo en el año 2020 y el 2021 se registraron 33 víctimas

### Recomendaciones para mejorar el KPI

- Publicidad de concientización de la seguridad vial
- Enseñar en las escuelas el adecuado cruce de las calles o lugares donde pueden, y no pueden, circular

## Estructura del Repositorio

- 📂 **CSV**: Contiene los archivos que se obtuvieron en el EDA y luego usados en el dashboard.

- 📂 **src**: Contiene las imágenes utilizadas para realizar este repositorio y las que se usaron en el dashboard.

- 📂 **Data_Original**: Contiene los archivos original. Estan en formato excel, dentro también tiene diccionarios de la data.


## Disclaimer
Este es un proyecto con fines educativos

## Contactos:
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](www.linkedin.com/in/micaelacallahuanca)

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MicaelaCallahuanca)

