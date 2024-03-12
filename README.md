<h1 align=center> PROYECTO INDIVIDUAL N°02 - DA SINIESTROS VIALES </h1>

# **Data Analytics**
![image](https://github.com/Kipros21/PI02-DA-SINIESTROS-VIALES/assets/142346448/ca6316df-bdef-4900-8b6b-070d29b4bfac)

## **Contexto**
![image](https://github.com/Kipros21/PI02-DA-SINIESTROS-VIALES/assets/142346448/f725c5c5-aa59-4be8-b7a5-a237a298fc8d)


En Argentina, la alarmante cifra de aproximadamente 4,000 muertes anuales por siniestros viales demanda medidas urgentes y coordinadas. Aunque se han logrado avances en la reducción de accidentes en algunas regiones, los informes del Sistema Nacional de Información Criminal revelan que entre 2018 y 2022 hubo 19,630 víctimas fatales en todo el país, equivalente a 11 personas por día.

La magnitud del problema se destaca aún más al comparar la probabilidad de morir en un siniestro vial, dos o tres veces mayor que en situaciones delictivas. En un contexto como Buenos Aires, con alto tráfico y densidad poblacional, los siniestros viales afectan la seguridad de residentes, visitantes, y ponen a prueba la infraestructura y servicios de emergencia.

Para abordar este desafío, es esencial implementar una estrategia integral:

- **Educación Vial**: Desarrollar programas educativos desde la infancia, enfocados en la importancia del respeto a las normas de tráfico y la responsabilidad individual.

- **Concientización Nacional**: Lanzar campañas de concientización a nivel nacional, destacando las consecuencias de los siniestros viales y promoviendo conductas seguras.

- **Control y Sanciones**: Reforzar los controles de tráfico con tecnologías modernas y aplicar sanciones más severas para disuadir comportamientos riesgosos.

- **Infraestructura Segura**: Invertir en mejoras de señalización, mantenimiento vial y diseño seguro de calles y cruces peatonales.

- **Vehículos Seguros**: Fomentar la adopción de vehículos más seguros mediante incentivos y promover tecnologías avanzadas.

- **Recopilación y Análisis de Datos**: Mantener una base de datos actualizada para identificar tendencias y evaluar la efectividad de las medidas implementadas.

- **Colaboración Interinstitucional**: Facilitar la colaboración entre agencias gubernamentales, ONG y la sociedad civil para abordar el problema de manera integral.

- **Incentivos para Conductores Responsables**: Establecer recompensas para conductores responsables, fomentando un cambio cultural hacia la seguridad vial.

- **Transporte Público**: Mejorar y promover el transporte público como alternativa, reduciendo la congestión vial y los riesgos asociados.

- **Investigación y Desarrollo**: Invertir en investigaciones que impulsen el desarrollo de nuevas tecnologías y enfoques para mejorar continuamente la seguridad vial.

Esta combinación de acciones busca no solo reducir la estadística de muertes viales, sino también fomentar una cultura de seguridad en las calles argentinas. La colaboración y el compromiso de la sociedad son cruciales para lograr un cambio positivo y sostenible en este ámbito.

## **Contenido**

- [Descripción del Proyecto](#Descripción-del-Proyecto)
- [Objetivo](#Objetivo)
- [Esquema de Proyecto](#Esquema-de-Proyecto)
- [Analitica de Información de Proyecto](#Analitica-de-Información-de-Proyecto)
- [Problematica de Proyectos](#Problematica-del-Proyecto)
- [Desarrollo de Proyecto](#Desarrollo-de-Proyecto)
- [Conclusiones](#Conclusiones)

## **Descripción del Proyecto: Data Analytics de Siniestros Viales**
En este proyecto, se simula el papel de un Analista de Datos que integra el equipo de una empresa consultora. Este equipo ha sido contratado por el Observatorio de Movilidad y Seguridad Vial (OMSV), un centro de estudios bajo la jurisdicción de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires (CABA), para llevar a cabo un análisis de datos detallado.

## **Objetivo**
Proporcionar insights significativos y recomendaciones basadas en datos para mejorar la comprensión de la movilidad y la seguridad vial en la ciudad. A través de la recopilación, procesamiento y análisis de datos relevantes, nuestro equipo buscará identificar patrones, tendencias y áreas de mejora en el contexto del tráfico y la seguridad vial.

## **Esquema de Proyecto**
![image](https://github.com/Kipros21/PI02-DA-SINIESTROS-VIALES/assets/142346448/df3b0a4f-51cd-45d8-a6af-610c8605fd64)


Siguiendo el esquema como referencia se solicito elaborar ETL, EDA y dashboard siguiendo una estructura lógica que abarca la compresión del problema hasta la presentación de los hallazgos y recomendaciones para este.

## **Analitica de Información de Proyecto**
En esta ocasión, se dispone de Datasets importantes para nuestro proyecto. Hemos empleado un conjunto de datos que detalla información sobre víctimas fatales y lesionados por parte del Observatorio de Movilidad y Seguridad Vial (OMSV) de la Ciudad Autónoma de Buenos Aires (CABA). Los dos conjuntos de datos asociados se encuentran almacenados en la carpeta Dataset, la cual se presenta a continuación:

- **homicidios.xlsx**: Alberga información detallada sobre los accidentes fatales ocurridas en la Ciudad Autónoma de Buenos Aires . La información incluye aspectos clave como el dirección, fecha, victima, roles, vehiculos, gravedad, etc. 

- **lesiones.xlsx**: Alberga información detallada sobre las lesiones ocurridas a las víctimas en la Ciudad Autónoma de Buenos Aires . La información incluye aspectos clave como el dirección, fecha, victima, roles, vehiculos, gravedad, etc. 

## **Problematica del Proyecto**
Los siniestros viales, también conocidos como accidentes de tráfico, son eventos que ocurren en la vía pública y pueden involucrar uno o varios vehículos, resultando en daños materiales y, en casos más graves, heridos o pérdidas humanas. Estos incidentes pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, así como atropellos, choques con objetos fijos o caídas de vehículos.

La gravedad de un accidente puede agravarse si no se aborda adecuadamente. El uso correcto de medidas preventivas, como el ajuste del cinturón de seguridad o el uso de casco en motocicletas o bicicletas, puede ser crucial para reducir la gravedad de las consecuencias.

Las causas de los accidentes de tránsito suelen ser variadas, pero se destacan principalmente por factores humanos, como conducir bajo la influencia del alcohol o realizar maniobras imprudentes. El factor mecánico también desempeña un papel cuando los vehículos no reciben el mantenimiento adecuado.

Enfocándonos en nuestro proyecto, que se centra en la capital de Argentina, una ciudad densamente poblada, es esencial abordar estas problemáticas específicas. Se debe prestar especial atención a las condiciones climáticas, el mantenimiento de las vías y la educación vial para reducir la incidencia de siniestros viales y garantizar la seguridad de los residentes. Además, se buscará implementar medidas efectivas de prevención y concientización para mitigar los factores humanos y mecánicos que contribuyen a estos incidentes.

## **Herramientas de Proyecto**
![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas)
![Numpy](https://img.shields.io/badge/-Numpy-333333?style=flat&logo=numpy)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-333333?style=flat&logo=matplotlib)
![Seaborn](https://img.shields.io/badge/-Seaborn-333333?style=flat&logo=seaborn)
![PowerBI](https://img.shields.io/badge/-PowerBI-333333?style=flat&logo=PowerBI)

## **Desarrollo de Proyecto**
## **Etapa ETL(Extract - Transform - Load)**
En esta fase, nos adentraremos en el preprocesamiento de los datos obtenidos. El objetivo es realizar transformaciones necesarias antes de cargarlos, preparando así el terreno para el Análisis Exploratorio de Datos (EDA) subsiguiente. Este paso es fundamental para garantizar la calidad y la utilidad de los datos durante el análisis.

- **Extracción (Extract):**
En esta fase, se recopilan los datos desde diversas fuentes. Pueden ser bases de datos, archivos CSV, API, o cualquier otro medio donde la información esté almacenada. El objetivo es obtener la información necesaria para el análisis posterior. La extracción de datos se realizo a traves del repositorio brindado [Datos Brutos](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales).

- **Transformación (Transform):**
Una vez que los datos se han extraído, la etapa de transformación entra en juego. Aquí, se llevan a cabo diversas operaciones para mejorar la calidad y la utilidad de los datos:
  1. Limpieza de Datos: Se identifican y corrigen posibles errores, valores nulos o duplicados.
  2. Estandarización: Se ajustan los formatos de datos para asegurar consistencia y comparabilidad.
  3. Enriquecimiento de Datos: Se pueden crear nuevas variables o combinarse datos para obtener información adicional.
  4. Filtrado: Se eliminan datos innecesarios o irrelevantes para el análisis.
  5. Normalización: Se ajustan los datos para mantener una escala consistente.

  El análisis ETL de los archivos brutos fueron realizados en estos Notebooks:
  - [ETL Homicidios y Lesiones](https://github.com/Kipros21/PI02-DA-SINIESTROS-VIALES/blob/main/ETL_homicidios_lesiones.ipynb)

- **Carga (Load):**
Después de transformar los datos, la etapa final es cargarlos en un repositorio destinado al análisis. Este puede ser un almacén de datos, una base de datos relacional, un data warehouse, o cualquier plataforma definida para el manejo de grandes volúmenes de información. La carga se realiza de manera eficiente para garantizar la disponibilidad y accesibilidad de los datos para su uso posterior.

Los Dataset limpios son los siguientes:
- [Data Limpia - Homicidios](https://github.com/Kipros21/PI02-DA-SINIESTROS-VIALES/blob/main/Dataset_Clean/homicidios_clean.parquet)
- [Data Limpia - Lesiones](https://github.com/Kipros21/PI02-DA-SINIESTROS-VIALES/blob/main/Dataset_Clean/lesiones_clean.parquet)

## **Etapa EDA (Exploratory Data Analysis)**
En esta fase se realiza el proceso de análisis de datos donde se exploran y examinan los datos de manera inicial y general. El objetivo principal del EDA es comprender la naturaleza de los datos, identificar patrones, detectar posibles anomalías y obtener percepciones preliminares antes de aplicar métodos analíticos más avanzados. Durante el EDA, se realizan diversas operaciones, como la visualización de datos mediante gráficos, la descripción estadística de variables clave, y la identificación de relaciones entre diferentes características del conjunto de datos. Este proceso es esencial para orientar el análisis de datos subsiguiente y para tomar decisiones informadas sobre el enfoque y las técnicas que se aplicarán en el análisis más detallado.

El Notebook donde se realizo el proceso EDA es el siguiente: [Analisis Exploratorio de Datos](https://github.com/Kipros21/PI02-DA-SINIESTROS-VIALES/blob/main/EDA_homicidios_lesiones.ipynb)

## **Etapa de Presentación de Resultados e Insights**

## **Resultados**
Compartimos los resultados específicos y descubrimientos obtenidos a lo largo del análisis de datos. Por ejemplo estadísticas significativas o información relevante identificada durante el proceso. La presentación de hallazgos implica proporcionar detalles específicos y evidencia respaldatoria para respaldar las conclusiones. Es crucial destacar la importancia de estos hallazgos y cómo se relacionan con los objetivos iniciales del análisis. Algunos de los hallazgos son:

  - Se observa que los días con mayor incidencia de homicidios y lesiones por accidentes de tránsito son los lunes, viernes, sábado y domingo. Los  fines de semana, especialmente, muestran un aumento significativo, atribuible a las actividades recreativas, compras y eventos sociales. Durante la mañana, la prisa por llegar al trabajo puede contribuir a esta tendencia y parte de la tarde regreso del trabajo, mientras que en las noches, las festividades y actividades sociales pueden incidir en el aumento de incidentes.

  - Se destaca que las víctimas de homicidios por accidentes de tránsito son predominantemente "MOTO" , "PEATÓN" y "CICLISTA". Este hallazgo resalta la vulnerabilidad inherente de estos grupos, ya que los peatones carecen de protección y los conductores de motocicletas o bicicletas enfrentan un riesgo significativo debido a la falta de protección estructural.

  - Las avenidas suelen caracterizarse por un tráfico más denso y velocidades más elevadas, factores que aumentan el riesgo de accidentes de tránsito. La combinación de vehículos en movimiento a altas velocidades puede contribuir a situaciones más propensas a incidentes mortales.


## **KPIs**
Presentamos y explicamos los Indicadores Clave de Rendimiento (KPIs) que se han identificado como relevantes para el éxito y el rendimiento del proyecto. Se debe comunicar de manera efectiva que los KPIs son significativos, cómo se miden y qué implicaciones tienen para la toma de decisiones. Es importante la comunicación de KPIs ya que es esencial que los interesados comprendan el rendimiento y los resultados derivados del análisis de datos.

  * *Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior*

    Las tasas de mortalidad relacionadas con siniestros viales suelen ser un indicador crítico de la seguridad vial en una región. Se define como **Tasa de homicidios en siniestros viales** al número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico, en este caso se toman 6 meses. Su fórmula es:

    $\text{Tasa de homicidios en siniestros viales} = \frac{\text{Número de homicidios en siniestros viales}}{\text{Población total}}·100,000$

        
    **Resultado**:La tasa de homicidios en siniestros viales en CABA, que registró **1.21** en el primer semestre de 2021, experimentó un aumento a **1.35** durante el segundo semestre, superando la meta del 10% de reducción. Este resultado indica que las medidas implementadas no lograron alcanzar la reducción esperada y sugiere la necesidad de una evaluación exhaustiva de las estrategias de seguridad vial.

  * *Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior*

    Como se vio en el análisis exploratorio, la mayor parte de las víctimas mortales se transportaban en moto al momento del hecho. Por lo que se consideró importante proponer el monitoreo de la cantidad de accidentes mortales en este tipo de conductor. Para ello se define a la **Cantidad de accidentes mortales de motociclistas** como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. La fórmula para medir la evolución de los accidentes mortales con víctimas en moto es:

    $\text{Cantidad de accidentes mortales de motociclistas} = -\frac{\text{Víctimas moto año anterior - Víctimas moto año actual}}{\text{Víctimas moto año anterior}}·100$

    Donde:
    - $\text{Víctimas moto año anterior}$: Número de accidentes mortales con víctimas en moto en el año anterior
    - $\text{Víctimas moto año actual}$: Número de accidentes mortales con víctimas en moto en el año actual 

    **Resultado**:El objetivo de reducir en un 7% la cantidad de accidentes mortales de motociclistas no se cumplió. La cantidad de muertes de conductores de motocicletas aumentó significativamente en un **64%** durante el año 2021 en comparación con el año anterior. Este resultado resalta la necesidad de revisar y fortalecer las medidas de seguridad para los motociclistas en la Ciudad Autónoma de Buenos Aires.

  * *Reducir en un 10% la tasa de homicidios en las avenidas en el último año, en CABA, respecto al año anterior*

    Como se vio en el análisis exploratorio, la mayoría de las víctimas mortales transitaban por avenidas al momento del hecho. Se define a la **Tasa de homicidios en las avenidas** al número de víctimas fatales en accidentes de tránsito en avenidas por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico, en este caso anual. Su fórmula es:

    $\text{Tasa de homicidios en las avenidas} = \frac{\text{Número de accidentes mortales con víctimas ocurridas en avenidas}}{\text{Total de la población}}·100000$

    **Resultado**:El objetivo de reducir en un 10% la tasa de homicidios en las avenidas no se cumplió. La tasa de homicidios aumentó en el año 2021, alcanzando **2.27**, lo que representa un aumento respecto al valor del año anterior. Este resultado destaca la importancia de revisar y fortalecer las medidas de seguridad específicas para las avenidas en la Ciudad Autónoma de Buenos Aires.
    
![image](https://github.com/Kipros21/PI02-DA-SINIESTROS-VIALES/assets/142346448/3ff7d591-928e-48a0-a25b-3682c13efb4d)

## **Insights**
Resaltamos las percepciones y conocimientos más profundos obtenidos durante el análisis de datos. Presentamos insights clave que proporcionan una comprensión más completa y valiosa de los patrones, tendencias o relaciones identificadas en los datos. Es importante comunicar estos insights de manera clara y concisa, enfocándote en cómo pueden influir en nuestra toma de decisiones. Algunos de los Insights son:

  - Se evidencia que el estrés vinculado a la rutina cotidiana tiene un impacto significativo en las actitudes de conducción, posiblemente llevando a un cambio de actitud defensiva a ofensiva. Esta transición, impulsada por la urgencia y la presión del tiempo, podría amplificar el riesgo de accidentes de tráfico, subrayando la importancia de abordar el bienestar emocional de los conductores como un componente clave para la seguridad vial.

  - La incidencia más alta de homicidios por accidentes y lesiones de tránsito se observa en grupos demográficos como "Adulto Joven", "Adulto de Mediana Edad", "Adulto Mayor" y "Adulto Maduro", destacando su mayor actividad social y uso frecuente de transporte. Sin embargo, el grupo de "Adultos Mayores" muestra una preocupante propensión a estos eventos, sugiriendo la necesidad de medidas específicas para proteger a este segmento vulnerable, dada la posible relación con la fragilidad física asociada a la edad avanzada.

  - La presencia frecuente de intersecciones y cruces en las avenidas se revela como un factor crítico que contribuye a la susceptibilidad de colisiones y accidentes. La complejidad inherente a estos puntos de encuentro subraya el riesgo potencial de situaciones peligrosas, destacando la necesidad urgente de mejorar la señalización y el control del tráfico en estas áreas para mitigar los riesgos asociados con la movilidad en avenidas.

  
Más detalle sobre los hallazgos, KPIs e Insights, puede encontrarlos aquí: [Analisis Exploratorio de Datos](https://github.com/Kipros21/PI02-DA-SINIESTROS-VIALES/blob/main/EDA_homicidios_lesiones.ipynb) o [Dashboard Accidentes Viales](https://github.com/Kipros21/PI02-DA-SINIESTROS-VIALES/blob/main/Accidentes_Viales.pbix)

## **Conclusiones**
En este proyecto de análisis de accidentes viales en la Ciudad de Buenos Aires, se ha obtenido una comprensión completa de los patrones y factores que afectan la seguridad vial, explorando variables como ubicación, factores humanos y demográficos. Se destaca la importancia de la educación vial y medidas preventivas para abordar áreas críticas, como intersecciones complejas y avenidas con tasas de accidentes elevadas. Aunque se logró el objetivo, se señala la necesidad de optimizar procesos para obtener resultados más eficientes. Este proyecto sienta las bases para futuras mejoras y el desarrollo continuo de capacidades de Data Analytics en entornos similares.

## Autor
* **HUANQUI Tapia, Cristhian**  
    
