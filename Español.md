# Proyectos
## 1 -  Alerta de Heladas - Sistema de Monitoreo y Tecnología Ambiental de Paraná (SIMEPAR)
<div style="text-align: justify">

Desarrollé la rutina operativa de la Alerta de Heladas en el estado de Paraná. Alerta Geada es un servicio mantenido entre SIMEPAR e IAPAR, con la participación de EMATER. La rutina genera pronósticos diarios de la ocurrencia e intensidad de las heladas que ocurrirán en el estado de Paraná en el horizonte de dos días. Los pronósticos se pueden consultar en el sitio web del [SIMEPAR](http://www.simepar.br/) entre los meses de mayo y septiembre.
</div>
<br>

<p align="center">
    <img src="assets\dia1.jpg" width="600">
</p>

## 2 -  Modelo de espacialización de datos mediante inteligencia artificial

<div style="text-align: justify">
En el contexto del proyecto del Instituto de Tecnología para el Desarrollo (LACTEC) en alianza con SIMEPAR para desarrollar un modelo de estimación de la ampacidad de la red de transmisión de la Companhia Paranaense de Energia (COPEL), desarrollé un modelo de espacialización operativa de las principales variables condiciones meteorológicas en el dominio estatal. El modelo utiliza inteligencia artificial para estimar variables a partir de datos de telemetría y topografía de simepar.
</div>

<br>

## 3 - IImplementación de procedimientos de calibración y verificación de índices estacionales y subestacionales de precipitación, temperatura y sequía.
<div style="text-align: justify">
Fui consultor del Sistema de Información sobre Sequías para el Sur de Sudamérica (SISSA) entre 2021 y 2022. Mi consultoría tuvo como objetivo desarrollar y validar rutinas operativas para la calibración y verificación de la habilidad de los pronósticos climáticos generados a partir del MNorth American Multi Model Ensamble (NMME) y el European Centre for Medium-Range Weather Forecasts (ECMWF).

<br>
</div>
<p align="center">
    <img src="assets\bs.jpg" width="400">
</p>

## 4 - API que sirve un modelo de espacialización de datos meteorológicos y un modelo hidrológico
<div style="text-align: justify">

Estoy desarrollando una API utilizando el marco FastAPI para servir dos modelos en formato de software como servicio (SaaS). El primer modelo estima variables meteorológicas para cualquier punto geográfico de Brasil a partir de la red telemétrica del INMET. El segundo modelo consiste en una implementación del modelo hidrológico lluvia-escorrentía SMAP. El primer modelo utiliza un método tradicional de geoestadística para generar espacialización. Sin embargo, este método pronto será reemplazado por un modelo más sofisticado de inteligencia artificial. Los resultados generados por el primer modelo se integrarán en el segundo para la calibración, estimación y predicción de caudales. Además, la API tendrá endpoints para obtener predicciones de los modelos globales GFS y CFS. Para acceder a la versión de desarrollo [haga clic aquí](https://weather-api-br.herokuapp.com/docs).
</div>

<br>
<p align="center">
    <img src="assets\weather-api.png" width="800">
</p>

## 5 - Modelo hidrológico lluvia - caudal en Python (SMAPy)
<div style="text-align: justify">
Desarrollé un conjunto de scripts en Python que permite calibrar el modelo SMAP (Procedimiento de Contabilidad de la Humedad del Suelo) y calcular el caudal diario y mensual de forma automatizada. El SMAP es el principal modelo hidrológico utilizado por el Operador del Sistema Eléctrico Brasileño (ONS).

<br>

Para obtener más detalles sobre el desarrollo de SMAPy, visite el [repositorio del proyecto](https://github.com/rrodrigojrr/SMAPy).
</div>

<br>

<p align="center">
    <img src="assets\comparacao.png" width="600">
</p>

<div style="text-align: justify">
Junto con los scripts de SMAPy, entrené un modelo de Inteligencia Artificial capaz de mejorar el cálculo de flujo utilizando datos de flujo previamente observados y estimados. <br>

<br>

Para obtener más detalles sobre el modelo de IA de corrección de sesgo de SMAPy, visite el [artículo](https://www.linkedin.com/pulse/utilizando-machine-learning-para-refinar-vaz%C3%A3o-calculada-j%C3%BAnior/) que escribí en Linkedin.
</div>

<p align="center">
    <img src="assets\smap_ia.jpg" width="700">
</p>


# Aportes Científicos
## Publicaciones más relevantes:

1 - [An Empirical Seasonal Rainfall Forecasting Model for the Northeast Region of Brazil](https://www.mdpi.com/2073-4441/13/12/1613), Water, 2021.

2 - [Bivariate Assessment of Drought Return Periods and Frequency in Brazilian Northeast Using Joint Distribution by Copula Method](https://www.mdpi.com/2076-3263/10/4/135), Geosciences, 2020.

3 - [Long-Term Change and Regionalization of Reference Evapotranspiration in the Brazilian Northeast](https://www.scielo.br/j/rbmet/a/DswtTWGM9MmmB8m6h5L7V7c/?lang=pt), Revista Brasileira de Meteorologia, 2020.

4 - [Analysis of climate extremes indices over northeast Brazil from 1961 to 2014](https://www.sciencedirect.com/science/article/pii/S2212094719300763?via%3Dihub), Weather and Climate Extremes, 2020.

5 - [Analysis of the Space–Temporal Trends of Wet Conditions in the Different Rainy Seasons of Brazilian Northeast by Quantile Regression and Bootstrap Test](https://www.mdpi.com/2076-3263/9/11/457), Geosciences, 2019.

## Reseña en revistas
- Meteorology and Atmospheric Physics;
- Natural Hazards;
- Revista Brasileira de Meteorologia.

Visita mi [ORCID](https://orcid.org/0000-0003-4654-8947) para ver más de mis producciones.