# PI 02: Análisis de Datos de Siniestros Viales en la Ciudad de Buenos Aires

---

![img siniestros viales](src/portada_pi_dos.jpg)


## Descripción del Proyecto

El principal objetivo  de este proyecto es identificar información importante que pueda ayudar a reducir los accidentes fatales en la ciudad de Buenos Aires. Para lograrlo, se llevó a cabo un análisis integral de los datos proporcionados por el Departamento de Transporte, la Subsecretaría de Planificación de Movilidad y la Oficina de Supervisión de Movilidad y Seguridad Vial de 2016 a 2021. 

Información extraída de la siguiente página: 
- https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales




## Desarrollo del proyecto

**EDA** :Durante el análisis exploratorio de datos (EDA) se identificaron patrones interesantes que proporcionaron información valiosa sobre la naturaleza de los datos. Los detalles concretos de estos resultados se detallan en el notebook [EDA](https://github.com/MicaelaCallahuanca/SINIESTROS_VIALES/blob/main/EDA.ipynb)



**Dashboard**:

En el programa Power BI  se crearon  páginas. Estas páginas brindan información detallada sobre la ubicación, el momento y las características de las víctimas. Además, hemos agregado una página  que muestra los indicadores clave de desempeño (KPI) del proyecto para brindar una descripción general y completa de los resultados. El dashboard creado se encuentra en este repositorio.

Recomendamos descargar el panel para acceder a información más detallada y  una experiencia interactiva. [Dashboard](https://github.com/MicaelaCallahuanca/SINIESTROS_VIALES/blob/main/pi02_siniestros_viales.pbix)



### Hallazgos


- El vehículo de la víctima en los accidentes fatales en las autopistas más probable es la motocicleta

- La comuna con más accidentes fatales es la 1

- Los accidentes fatales se redujeron significativamente en el año 2020, posiblemente debido al confinamiento por la pandemia

- El mes con mayor cantidad de accidentes fatales es diciembre

- Ocurren más accidentes fatales los fines de semana.

- La mayoría de los accidentes fatales que ocurren los fines de semana se dan mayormente a las 7 de la mañana .

- Hay más víctimas del género masculino que del género femenino.

- Las víctimas fatales tienen entre 20 y 40 años. En contraste, en los demás rangos de edad, la mayoría de los incidentes fatales el vehiculo de la víctima es la motocicleta.


## KPI


**Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.**

Definimos a la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100


Se dío un aumento en accidentes de motociclistas en 2021 con respecto a 2020 es un resultado muy negativo, y está muy lejos de la meta de disminuir un 7% los accidentes de motociclistas.

### Recomendaciones para mejorar este KPI

- La avenida es el lugar donde ocurren más accidentes donde la víctima es el motociclista. Por lo que una opción es instalar cámaras de seguridad en la autopista para identificar y sancionar a los conductores que cometan infracciones que puedan causar accidentes.

- En los casos en los que la víctima era motociclista, también era el que iba conduciendo por lo que es necesario endurecer los requisitos para obtener el permiso de motocicleta. Esto podría incluir requisitos de edad mínima para conducir más estrictos, mayor tiempo de formación teórica y práctica y pruebas más rigurosas.

## Estructura del Repositorio

- 📂 **CSV**: Contiene los archivos usados en el análisis.

- 📂 **src**: Contiene las imágenes utilizadas para realizar este repositorio.

- 📂 **Data_Original**: Contiene los archivos original. 

## Tecnologías

💻 Python
📊 Power BI

## Disclaimer
Este es un proyecto con fines educativos