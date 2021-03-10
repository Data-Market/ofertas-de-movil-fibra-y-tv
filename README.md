# Datasets de Ofertas de Móvil, Fibra y TV

<a href="https://datamarket.es">
  <img src="https://datamarket.es/static/core/img/banners/ofertas-de-movil-fibra-y-tv-banner.png">
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

A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre | tipo | descripción | ejemplo |
|--------|------|-------------|---------|
| champions_league | bool | Incluye o no la Champions League. | False |
| children | bool | Incluye o no canales infantiles. | True |
| cinema_and_series | bool | Incluye o no promoción de cine y series. | True |
| company_name | str | Compañía de telecomunicaciones que oferta los productos. | masmovil |
| date | datetime | Fecha de publicación de la oferta. | 2021-02-08 |
| documentary | bool | Incluye o no canal de documentales. | True |
| fixed_to_fixed_calls_minutes | int | Minutos de fijo a fijo disponibles. | 999999999 |
| fixed_to_fixed_calls_text | str | Descripción de la oferta de llamadas fijo a fijo. | Llamadas ilimitadas a fijos y 60mins a móviles |
| fixed_to_mobile_calls_minutes | int | Minutos de fijo a móviles diponibles. | 60 |
| fixed_to_mobile_calls_text | str | Descripción de la oferta de llamada fijo a móviles. | Llamadas ilimitadas a fijos y 60mins a móviles |
| hbo | bool | Incluye o no HBO. | False |
| internet_4g | bool | Incluye o no línea 4G. | False | 
| internet_download_speed_mb | int | Velocidad de descarga en Mb. | 100 |
| internet_fiber | bool | Incluye o no fibra. | True |
| internet_text | str | Descripción de la velocidad de descargas para cada oferta. | 100Mb Fibra Óptica |
| internet_upload_speed_mb | int | Velocidad de subida en Mb. | 100 |
| liga | bool | Incluye o no La Liga. | False |
| lines_included | int | Número de líneas móviles incluidas. | 1 |
| mobile_additional_line | int | Número de líneas móviles adicionales. | 1 |
| mobile_additional_line_fee | int | Coste de la línea móvil adicional. | 0 |
| mobile_additional_line_text | str | Descripción de la oferta de las líneas móviles adicionales. | 2ª Línea Gratis para siempre con 3GB y llamadas ilimitadas. Además línea Extra de 3GB gratis dura... |
| mobile_download_capacity | int | Límite de descargas en móviles. | 5 |
| mobile_download_capacity_unit | str | Unidad de medida del límite de descarga. | GB |
| mobile_download_text | str | Descripción de la oferta del límite de descarga. | 5GB y llamadas ilimitadas |
| mobile_minutes | int | Cantidad de minutos de llamadas para móvil disponibles. | 999999999 |
| mobile_minutes_text | str | Descripción de la promoción de minutos para móviles disponibles. | 5GB y llamadas ilimitadas |
| movistar_tv | bool | Incluye o no el canal de movistar TV. | True |
| netflix | bool | Incluye o no Netflix. | False |
| network | str | Nombre del proveedor de red. | MásMóvil |
| offer_type | str | Tipo de oferta. | internet+fijo+móvil+tv |
| permanence_months | int | Número de meses de permanencia. | 3 |
| price_final_annual | float | Precio anual. | 514.80 |
| price_final_monthly | float | Precio mensual. | 42.90 |
| price_promotional | float | Precio de promoción. | None | 
| price_promotional_months | int | Número de meses que aplica la promoción. | 0 |
| price_text | str | Descripción detallada del precio. | None |
| product_name | str | Nombre de la oferta. | Fibra 100Mb, 5GB y 2ª linea gratis (3GB) + Agile TV |
| promo | str | Descripción de la promoción. | 2ª Linea Gratis para siempre con 3GB y llamadas ilimitadas. El resto de líneas adicionales 50% de... |
| rakuten_tv | bool | Incluye o no Rakuten TV. | False |
| roaming | str | Descripción de las características del roaming. | Roaming Incluido en la Unión Europea |
| tv_channel_number | int |  Número de canales de televisión disponibles. | 40 |
| tv_channel_text | str | Descripción detallada de los canales de televisión disponibles. | Rakuten TV (1500 pelis y series), ademas añade las mejores apps en tu tele, netfilx, primer video... |
