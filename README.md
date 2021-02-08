# Datasets de Ofertas de Móvil, Fibra y TV

<a href="https://datamarket.es">
  <img src="https://datamarket.es/static/core/img/banners/noticias-economicas-banner.png">
</a>

## Descripción

Ofertas de fibra, móvil, televisión... de las __principales compañías telco de España__.

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: diariamente
* __Volumen estimado__: 
* __Histórico__: 

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#ofertas-de-movil,-fibra-y-tv-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/ofertas-de-movil-fibra-y-tv/blob/main/ofertas-telco-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset en el formato __nombre_columna__: __ejemplo_columna__, donde ejemplo_columna representa posibles valores que se pueden encontrar en dicha columna.

| nombre                  | tipo     | descripción                                                                                                                      | ejemplo                |
|-------------------------|----------|----------------------------------------------------------------------------------------------------------------------------------|------------------------|
| company                 | str      | Compañías de telecomunicaciones que ofertan los productos (encriptado). Este campo será visible tras la subscripción al dataset. | 2021-01-16 17:18:00    |
| service                 | str      | Tipo de servicios que promociona cada oferta de productos.                                                                       | False                  |
| offer_name              | str      | Nombre de la oferta.                                                                                                             | False                  |
| offer_duration_months   | int      | Duración de la oferta para cada producto telco.                                                                                  | False                  |
| price_with_promotion    | float    | Precio del producto con la promoción aplicada.                                                                                   | False                  |
| price_without_promotion | float    | Precio del producto sin la promoción aplicada.                                                                                   | False                  |
| n_mobile_lines          | int      | Número de líneas de móviles ofertadas en cada promoción.                                                                         | False                  |
| minutes_mobile_calls    | str      | Cantidad de minutos de llamadas para móviles según promoción.                                                                    | False                  |
| amount_mobile_gb        | str      | Cantidad de GB que ofrece la promoción en móviles.                                                                               | 600                    |
| amount_fiber_mb         | int      | Cantidad de Mb que ofrece la fibra de casa promoción.                                                                            | infinitas              |
| included_netflix        | bool     | Incluye o no Netflix a las promociones.                                                                                          | infinitas              |
| included_hbo            | bool     | Incluye o no HBO a las promociones.                                                                                              | 2                      |
| included_amazon_prime   | bool     | Incluye o no Amazon Prime Video en cada promoción.                                                                               | 72.0                   |
| included_disney_junior  | bool     | Incluye o no Disney Junior en cada promoción.                                                                                    | 62.0                   |
| included_foxnow         | bool     | Incluye o no FOXNOW en cada promoción.                                                                                           | 3                      |
| included_agiletv        | bool     | Incluye o no agiletv en cada promoción.                                                                                          | Tarifa preocúpate cero |
| included_dazn           | bool     | Incluye o no DAZN en cada promoción.                                                                                             | fibra y móvil          |
| insert_date             | datetime | Fecha de extracción de la información.                                                                                           | yoigo                  |
