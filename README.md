<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
<p align='center'>
<img src ="scr\HenryLogo.jpg" height=100>
</p>

<p>
 <h3 align='center'>
    Edgar Adrian Arriaga Ortiz
</h3>
</p>
</p>

# Análisis de Siniestros Viales en la Ciudad Autonoma de Buenos Aires (2016-2021)

<p align='center'>
<img src ="scr\Logotipo_de_la_Ciudad_de_Buenos_Aires.svg (1).png" height=80>
</p>


## Índice

- [Introducción](#introducción)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Datasets](#datasets)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Analisis EDA](#analisis-eda)
- [KPIs](#kpis)
- [Conclusiones](#conclusiones)

<p align='center'>
<img src ="scr\ROLADESARROLAR.png" height=100>
<p>


## Introducción

Este proyecto está diseñado para tomar el rol de analista de datos en la ciudad de Buenos Aires y se investigara a fondo los siniestros y accidentes viales en esta misma ciudad, con el objetivo de comprender los factores que contribuyen a estos eventos, los cuales tienen un impacto profundo en la seguridad y el bienestar de la población. Mediante un análisis detallado y meticuloso de los datos disponibles, la finalidad del proyecto es descubrir patrones y tendencias que permitan identificar los principales factores de riesgo. Esta información será fundamental para desarrollar y orientar políticas públicas y estrategias de prevención más efectivas, con el fin último de mejorar la seguridad vial y reducir la frecuencia y gravedad de estos incidentes.

<p align='center'>
<img src ="scr\Mapaconceptual.jpg">
<p>


## Estructura del Proyecto

El repositorio está organizado en las siguientes carpetas y archivos principales:

- `Data`: Contiene los datasets utilizados en el análisis.
- `EDAyKPI's`: Incluye el Jupyter Notebook que contiene los procesos de transformación de los datos (ETL) y el análisis exploratorio de datos (EDA). Ademas de los scripts de como se sacaron los indicadores claves de rendimiento para evaluar los siniestros viales
- `Scr`: Contiene las imagenes utilizadas en el readme.md.
- `PowerBI`: Contiene el dashboard de los datos analizados de los Siniestros Viales en la Ciudad Autonoma de Buenos Aires (2016-2021)
- `README.md`: Este archivo, proporciona una descripción general del proyecto.

## Datasets

Los datasets principales utilizados en este proyecto son:

- `homicidios_hechos.csv`: Información sobre los hechos de siniestros viales.
- `homicidios_victimas.csv`: Datos sobre las víctimas de siniestros viales.
- `flujo_vehicular.csv`: Datos sobre los flujos de vehiculos en la Ciudad Autonoma de Buenos Aires
- `lesiones_hechos.csv`: Información sobre los hechos de lesiones de siniestros viales.
- `lesiones_victimas.csv`: Datos sobre las lesiones de las víctimas de siniestros viales.

## Tecnologias Utilizadas

Python y Pandas se emplearon para la extracción, transformación y carga ETL de datos. Para el análisis exploratorio de datos EDA se utilizaron librerías como Seaborn, Matplotlib,scipy.stats, numpy y pandas. Por último, para la creación del dashboard se utilizó PowerBi.

## Analisis EDA

El análisis integral de los datos sobre siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA) revela patrones y tendencias significativas:

- Características Temporales:
Los accidentes parecen distribuirse de manera relativamente uniforme a lo largo de los años, meses y días, con un promedio de 1.06 víctimas por incidente.
Analizando cada año en particular, el 2020 fue un año donde disminuyó mucho la tasa de siniestros viales, esto devido a la pandemia.

- Ubicación y Horarios:
La mayoría de los accidentes ocurren en las franjas horarias de 6:00 a 12:00 y de 18:00 a 24:00 horas, y la Comuna 1 es la más afectada.
Las avenidas son escenarios comunes de accidentes, representando el 62% de las víctimas, con un pico los sábados.

- Género:
El 76.72% de las víctimas son masculinas, siendo este género predominante en todos los roles, ya sea conductor, pasajero o peatón.

- Edad:
La edad promedio de las víctimas es de aproximadamente 42 años.
La mayoría de las víctimas tienen edades comprendidas entre 21 y 30 años, destacando la importancia de dirigir estrategias de seguridad vial a este grupo.

- Roles y Responsabilidad:
El 48% de las víctimas desempeñaba el rol de conductor, principalmente en motos.
Los conductores de automóviles y transporte publico son responsables en el 75% de los casos donde se señala un vehículo como responsable o acusado. 

- Patrones Temporales:
Se observa un aumento en la cantidad de accidentes en diciembre.
Los picos de accidentes en diferentes meses varían en distintos años. Aunque se puede observar un patrón anual en la distribución de incidentes, destacando un pico significativo en diciembre, este mes experimentó la mayor cantidad de incidentes. Contrastando con esta tendencia, abril surge como el mes con la menor cantidad de incidentes registrados.

## KPIs

1.- Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.

La métrica de seguridad en accidentes vehiculares se configura como un indicador esencial, evaluando el número de víctimas fatales en incidentes de tráfico por cada 100,000 habitantes durante un semestre. La meta consiste en reducir esta métrica en un 10% en el segundo semestre de 2021 en comparación con el primer semestre. El análisis demuestra que al alcanzar una métrica de  1.35, se superó con éxito el objetivo de disminuir en un 10% la tasa de fatalidades, ya que la métrica previa era de 1.76, logrando así una reducción del 23.64%

2.- Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

El segundo KPI se encarga de supervisar la cantidad de incidentes mortales relacionados con motociclistas. El propósito es reducir en un 7% la cantidad de accidentes mortales de motociclistas durante el último año. No obstante, los resultados indican un aumento del 53.33% en la cifra de fallecimientos de motociclistas en 2021, señalando la necesidad de estrategias adicionales. Es importante tener en cuenta que el año 2020 estuvo marcado por una pandemia y restricciones de movimiento. 

3.- Reducir en un 25% la tasa de homicidios en siniestros viales de Hombres de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.

La métrica de seguridad en accidentes vehiculares, centrada exclusivamente en hombres, se establece como un indicador crucial, evaluando el número de víctimas fatales masculinas en incidentes de tráfico por cada 100,000 habitantes durante un semestre. La meta consiste en reducir esta métrica en un 25% en el segundo semestre de 2021 en comparación con el primer semestre. Sin embargo, los resultados superaron significativamente las expectativas, ya que se alcanzó una métrica de 2.08, lo que representa una reducción del 33.3%, comparado con la métrica inicial de 3.13. Esto demostró un éxito notable en la disminución de la tasa de fatalidades masculinas.

4.- Reducir en un 25% la tasa de homicidios en siniestros viales de Mujeres de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.

La métrica de seguridad en accidentes vehiculares, ahora enfocada exclusivamente en mujeres, se define como un indicador clave, midiendo el número de víctimas fatales femeninas en incidentes de tráfico por cada 100,000 habitantes durante un semestre. Contrariamente a las expectativas, esta métrica experimentó un incremento del 20% en el segundo semestre de 2021 en comparación con el primer semestre. La tasa inicial fue de 0.59 y aumentó a 0.71 en el segundo semestre, evidenciando un crecimiento considerable en la tasa de fatalidades femeninas en dicho periodo.


## Conclusiones


La investigación sobre los siniestros viales en la Ciudad Autónoma de Buenos Aires revela varias tendencias y patrones significativos que pueden orientar estrategias de prevención y políticas públicas futuras. Durante el año 2020, se observó una disminución notable en la cantidad de siniestros, principalmente atribuible a las restricciones de movilidad impuestas por la pandemia de COVID-19. Sin embargo, con la normalización de actividades, los datos indican ciertos patrones consistentes en la ocurrencia de accidentes.

En términos de temporalidad, los siniestros son más frecuentes durante las horas pico, específicamente en las mañanas, y muestran un aumento considerable en diciembre. Además, se detectó un ligero aumento en los siniestros los días lunes, aunque la distribución es bastante uniforme a lo largo de la semana.

Las víctimas de estos incidentes suelen ser predominantemente hombres y se concentran en el grupo de 20 a 40 años, subrayando la necesidad de enfocar medidas de seguridad vial hacia este segmento de la población. La mayoría de las víctimas son conductores, especialmente de motocicletas y automóviles, y los accidentes tienden a involucrar solo a una o pocas víctimas en comparación con incidentes masivos.

Geográficamente, las avenidas principales son los lugares más propensos para los accidentes, debido al alto tráfico y velocidades más elevadas, siendo las comunas 1, 4, 9 y 8 las zonas con mayor registro de víctimas. Esto destaca la importancia de reforzar la seguridad en estas áreas, particularmente en las avenidas donde ocurre el 62% de los siniestros.

Además, se resalta la vulnerabilidad de peatones y pasajeros, quienes frecuentemente se ven involucrados en estos siniestros. Estos hallazgos sugieren la necesidad de mejorar las infraestructuras viales, implementar campañas de concientización más efectivas y reforzar las regulaciones de tráfico para proteger a los usuarios más susceptibles de la vía pública.

En resumen, la investigación muestra una clara imagen de los factores de riesgo asociados con los siniestros viales en la ciudad, señalando áreas clave para la intervención gubernamental y comunitaria con el fin de reducir la tasa de siniestros mortales, accidentes y mejorar la seguridad vial general.

## Contacto
Para más información o conectar, sigueme en [LinkedIn](https://www.linkedin.com/in/edgar-adrian-arriaga-ortiz-b6289b225/).
