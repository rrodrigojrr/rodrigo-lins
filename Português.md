# Projetos
## 1 -  Alerta Geada - Sistema de Tecnologia e Monitoramento Ambiental do Paraná (SIMEPAR)
<div style="text-align: justify">
Desenvolvi a rotina operacional do Alerta Geada do estado do Paraná. O Alerta Geada é serviço operacional mantido entre o SIMEPAR e IAPAR, com participação da EMATER. A rotina gera previsões diárias de ocorrência e intensidade das geadas que acontecerão no estado do Paraná no horizonte de dois dias. As previsões podem ser consultadas no site do [SIMEPAR](http://www.simepar.br/) entre os meses de maio a setembro.
</div>

<p align="center">
    <img src="assets\alerta.jpeg" width="600">
</p>

## 2 -  Modelo de Espacialização de Dados utilizando Inteligência Artificial

<div style="text-align: justify">
No contexto do projeto do Instituto de Tecnologia para o Desenvolvimento (LACTEC) em parceria com o SIMEPAR para desenvolvimento de um modelo de estimativa da ampacidade da rede de transmissão da Companhia Paranaense de Energia (COPEL), desenvolvi um modelo de espacialização operacional de dados da rede telemétrica do estado. O modelo utiliza inteligência artificial para estimar variáveis meteorológicas a partir de dados da telemetria do simepar e dados de topografia.  
</div>

  

## 3 - Implementação de procedimentos para calibração e verificação de prognósticos mensais/sazonais de precipitação, temperatura e índices de seca.
<div style="text-align: justify">
Prestei consultoria ao Sistema de Información sobre Squías para el Sur de Sudamérica (SISSA) com o objetivo de desenvolver rotinas para calibração e verificação da destreza das previsões climáticas geradas pelo CRC-SAS. 

Durante o projeto processei dados de previsão climática do projeto NMME (North American Multi Model Ensamble) e dados históricos do ERA5. 
</div>
<p align="center">
    <img src="assets\bs.jpg" width="400">
</p>


## 4 - API de modelo de espacialização de dados meteorológicos e modelo hidrológico
<div style="text-align: justify">
Estou desenvolvendo uma API utilizando o framework FastAPI com o objetivo de servir dois modelos no formato Software as a Service (SaaS). O primeiro modelo estima variáveis meteorológicas para qualquer ponto geográfico do Brasil a partir da rede telemétrica do INMET. O segundo modelo consiste numa implementação do modelo hidrológico chuva-vazão SMAP. O primeiro modelo utiliza um método tradicional de geoestatística para gerar a espacialização. Porém, este método será substituído em breve por um modelo mais sofisticado de inteligência artificial. Os resultados gerados pelo primeiro modelo serão integrados ao segundo para calibração, estimativas e previsão de vazão. Além disso, a API contará com endpoints para obtenção de previsões dos modelos globais GFS e CFS. Para acessar a versão em desenvolvimento [clique aqui](https://weather-api-br.herokuapp.com/docs).
</div>

<p align="center">
    <img src="assets\weather-api.png" width="800">
</p>

## 5 - Modelo chuva - vazão SMAP em Python (SMAPy)
<div style="text-align: justify">
Desenvolvi um conjunto de scripts em Python que torna possível a calibração do modelo SMAP (Soil Moisture Accounting Procedure) e cálculo da vazão diária e mensal de forma automatizada.O SMAP é o principal modelo regulatório utilizado pelo Operador Nacional do Sistema (ONS) elétrico brasileiro.


Para mais detalhes sobre o SMAPy, acesse o [repositório do projeto](https://github.com/rrodrigojrr/SMAPy).
</div>


<p align="center">
    <img src="assets\comparacao.png" width="600">
</p>

<div style="text-align: justify">
Em conjunto aos scripts do SMAPy, treinei um modelo de Inteligência Artificial capaz de melhorar o cálculo da vazão utilizando dados de vazão observados e estimados anteriormente. <br>

Para mais detalhes sobre o modelo de IA para correção de viés do SMAPy acesse o [artigo](https://www.linkedin.com/pulse/utilizando-machine-learning-para-refinar-vaz%C3%A3o-calculada-j%C3%BAnior/) que escrevi no linkedin.
</div>

<p align="center">
    <img src="assets\smap_ia.jpg" width="700">
</p>



# Contribuições Científicas
## Publicações mais relevantes:

1 - [An Empirical Seasonal Rainfall Forecasting Model for the Northeast Region of Brazil](https://www.mdpi.com/2073-4441/13/12/1613), Water, 2021.

2 - [Bivariate Assessment of Drought Return Periods and Frequency in Brazilian Northeast Using Joint Distribution by Copula Method](https://www.mdpi.com/2076-3263/10/4/135), Geosciences, 2020.

3 - [Analysis of the Space–Temporal Trends of Wet Conditions in the Different Rainy Seasons of Brazilian Northeast by Quantile Regression and Bootstrap Test](https://www.mdpi.com/2076-3263/9/11/457), Geosciences, 2019.

4 - [Long-Term Change and Regionalization of Reference Evapotranspiration in the Brazilian Northeast](https://www.scielo.br/j/rbmet/a/DswtTWGM9MmmB8m6h5L7V7c/?lang=pt), Revista Brasileira de Meteorologia, 2020.

5 - [Analysis of climate extremes indices over northeast Brazil from 1961 to 2014](https://www.sciencedirect.com/science/article/pii/S2212094719300763?via%3Dihub), Weather and Climate Extremes, 2020.

## Revisão em periódicos
- Meteorology and Atmospheric Physics;
- Natural Hazards;
 - Revista Brasileira de Meteorologia

### Para mais produções, acesse meu [ORCID](https://orcid.org/0000-0003-4654-8947)