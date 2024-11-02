# PROYECTO INDIVIDUAL N2 Data Analitycs.📊    
## Siniestros Viales en Buenos Aires  
![imagen principal](https://www.inforegion.com.ar/wp-content/uploads/2022/01/accidente-ezeiza.jpg)

Los accidentes de tráfico representan una problemática seria que impacta principalmente a conductores, motociclistas y peatones, poniendo en riesgo tanto la seguridad como la movilidad en las vías.   
El propósito fundamental de este proyecto es examinar y comprender detalladamente la información concerniente a los incidentes de tráfico, con el fin primordial de elevar los estándares de seguridad y eficiencia en el flujo vehicular de Buenos Aires, evitando así posibles percances en el futuro. Para llevar a cabo esta tarea, contamos con la colaboración de la Oficina Municipal de Seguridad Vial (OMSV), una institución de investigación afiliada a la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, que nos ha proporcionado un conjunto de datos exhaustivo sobre los accidentes fatales ocurridos en la metrópolis entre los años 2016 y 2021.  

# ETL (Extract, Transform, Load)  
Durante esta fase, la ejecución del proyecto se desarrolló de manera fluida y eficiente, enfrentando mínimos obstáculos que pudieran entorpecer el avance del trabajo. Se dedicó un esfuerzo considerable a la construcción de una base sólida y robusta que servirá como punto de partida para el análisis exhaustivo que se llevará a cabo en las siguientes etapas del proyecto.  
  
# Exploración de Datos (EDA, por sus siglas en inglés: Exploratory Data Analysis)
Después de culminar el proceso de Extracción, Transformación y Carga (ETL) y generar el conjunto de datos consolidado, nos adentramos en la fase de Exploración de Datos (EDA). Esta etapa implica sumergirse en los detalles de los lamentables sucesos que deseamos comprender a fondo.  

Durante el análisis estadístico y visualización de los datos, llevamos a cabo las siguientes actividades:  

Utilizamos diversas técnicas gráficas y herramientas de visualización para discernir patrones y relaciones entre las variables, permitiendo una comprensión más profunda de la información.  

Identificamos las variables que presentan una mayor incidencia de siniestros viales, lo que nos proporciona una visión clara de los aspectos más críticos que deben abordarse.  

Investigamos las áreas geográficas, roles desempeñados, rangos de edad y tipos de vehículos asociados con el mayor número de víctimas fatales en estos eventos desafortunados.  

Este análisis exhaustivo nos permite obtener una visión holística de los datos, lo que a su vez nos capacita para tomar decisiones fundamentadas y efectivas orientadas a la prevención y mitigación de futuros incidentes.  

Aca mostramos algunas graficas del EDA: 
  
#### Siniestros Fatales por Edad.  
La edad con mayor incidencia de siniestros fatales se da en la edad entre 20 y 40 años.  
![imagen eda1](/Imagenes/edad_siniestro.png)  
  
#### Siniestros Fatales por Comuna.  
Las comunas con mayor incidencias de siniestros son la comuna 1 con 93 victimas, 4 con 79 victimas y la 9 con 75 victimas.    
![imagen eda2](/Imagenes/comuna.png)    
  
#### Siniestros fatales por tipo de calle.   
El tipo de calle con mas incidencia en siniestros viales son en avenidas con un total de 442 victimas  
![imagen eda3](/Imagenes/tipocalle.png)   
  
#### Siniestros fatales por Sexo.  
En los  siniestros del año 2016-2021 la mayoria de victimas son del sexo Masculino con un 76.1%.  
![imagen eda4](/Imagenes/sexo.png)   

# Herramientas utilizadas
Pandas  
Matplotlib    
Numpy  
Seaborn  
Plotly.graph_objects 

# Dashboard  
![imagen dashboard](/Imagenes/imagen%200.PNG)  
Hemos dado el toque final con un impresionante dashboard interactivo en PowerBI. Este tablero informativo cuenta con una portada cautivadora, ocho páginas llenas de contenido intrigante y una página de conclusiones que te dejará reflexionando. ¿Y lo mejor de todo? ¡Botones interactivos que te guiarán a través de cada rincón de nuestro emocionante proyecto con solo un clic! Sumérgete en esta experiencia única y déjate sorprender 🚀📊

### Graficas Generales  
En nuestro análisis, hemos incorporado filtros por año y comuna para una exploración detallada de los siniestros. Esta configuración nos permite examinar los datos de manera precisa, segmentándolos por año y mes. Además, hemos agregado un panel que muestra de forma rápida la cantidad de víctimas y la cantidad de siniestros por vehículos, tanto del acusado como de la víctima.  
![imagen dashboard1](/Imagenes/imagen3gen.PNG)  

### Graficas Comunas  
En las siguientes gráficas, proporcionamos una visualización clara de la cantidad de siniestros ocurridos en cada comuna. Además, hemos segmentado estos datos por año, lo que te permite filtrarlos según tus necesidades específicas. Esta segmentación por año te permite aprovechar el análisis en cada faceta, brindándote una comprensión más detallada de la evolución de los siniestros a lo largo del tiempo y su distribución geográfica.  
![imagen dashboard2](/Imagenes/imagen%202.PNG)   

### Graficas Genero  
En esta gráfica de géneros, presentamos una visualización detallada de los siniestros según el género y el rol que desempeñaban en el momento del accidente. Además, calculamos el promedio de la edad de las víctimas según su género. La segmentación de estos datos está distribuida por año y comuna, lo que permite un análisis más profundo y contextualizado de la distribución de los siniestros en diferentes áreas y períodos de tiempo.
![imagen dashboard3](/Imagenes/imagen%203.PNG)  
## KPI

###  KPI Siniestros fatales   
En esta grafica presentamos la cantidad de accidentes clasificados por tipo de vehículo (moto, auto y peatón). Además, hemos segmentado estos datos por año, lo que te permite verificar los años anteriores y realizar comparativas entre períodos. Esta visualización nos permite identificar tendencias y patrones en la incidencia de accidentes a lo largo del tiempo, lo que resulta valioso para la planificación y la implementación de medidas preventivas.  
Realizamos las proyecciones nacionales de población para la Ciudad Autónoma de Buenos Aires (CABA) del año 2021. Estas proyecciones se basan en la segmentación anual que se realiza a partir del primero de julio. Calculamos la tasa de homicidios por semestre durante el año 2021, considerando el número total de homicidios en cada semestre en relación con la población total estimada para ese período.  
![imagen dashboard4](/Imagenes/imagen%204.PNG)  

### KPI Siniestros Moto  
Para este segundo KPI, nos enfocamos en los siniestros viales que implicaban motocicletas durante el año 2021. Inicialmente, calculamos el total de víctimas relacionadas con accidentes de motocicleta en dicho año.
Luego, realizamos un análisis comparativo con el año anterior para determinar la reducción porcentual esperada de siniestros mortales. Basándonos en este análisis, establecimos una meta de reducción del 7% en comparación con la cantidad de siniestros mortales del año previo.  
![imagen dashboard5](/Imagenes/imagen%205.PNG)  

### KPI Siniestros Comuna 1
En este tercer indicador clave de rendimiento (KPI), nos proponemos reducir en un 10% la cantidad de accidentes en la Comuna 1. Para ilustrar nuestro progreso, presentamos una gráfica que compara la cantidad de accidentes ocurridos en los años 2021 y 2020. Además, en la misma visualización, destacamos la reducción porcentual lograda entre ambos años.  
Esta representación gráfica nos proporciona una visión clara y concisa del impacto de nuestras acciones para mejorar la seguridad vial en la Comuna 1. Nos ayuda a monitorear nuestro avance hacia el objetivo de reducir la cantidad de accidentes y a identificar cualquier área que requiera atención adicional para alcanzar nuestra meta del 10% de reducción.  
![imagen dashboard6](/Imagenes/kpicomuna.PNG)   

## Conclusiones
![imagen dashboard7](/Imagenes/imagen%207.PNG)  
Los siniestros fatales son un problema grave que afecta a todos. Según la Organización Mundial de la Salud (OMS), cada año mueren en las carreteras alrededor de 1,35 millones de personas y otras 50 millones resultan heridas. Los siniestros viales son la principal causa de muerte entre los niños y jóvenes de 5 a 29 años, y la segunda causa de muerte entre los adultos de 30 a 44 años.   

Para reducir el número de siniestros fatales, es necesario tomar medidas en todos los niveles de la sociedad. Los gobiernos deben invertir en infraestructura vial segura, mejorar la aplicación de las leyes de tránsito y promover campañas de educación vial. Las empresas deben implementar políticas de seguridad vial para sus empleados. Y los conductores deben ser responsables y respetar las normas de tránsito.  


# Contacto
**Linkendin:** Luis Mary Gaince  
**GitHub:** Luismary27




