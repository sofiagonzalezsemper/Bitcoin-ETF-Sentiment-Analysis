# Bitcoin ETF Sentiment Analysis

Análisis exploratorio de noticias sobre Bitcoin ETFs para estudiar la evolución del sentimiento, los eventos asociados a sus principales variaciones y los términos característicos de cada período.

## Objetivo de negocio

Convertir un conjunto de noticias no estructuradas en indicadores que permitan responder:

- ¿Cómo evolucionó el sentimiento del mercado?
- ¿Qué eventos coincidieron con los mayores cambios?
- ¿Qué temas caracterizaron las noticias positivas y negativas?
- ¿Cómo varió el tratamiento entre fuentes?

## Metodología

1. Recolección de noticias desde Google News.
2. Limpieza y normalización del texto.
3. Clasificación con VADER y TextBlob.
4. Construcción de un indicador combinado de sentimiento.
5. Análisis temporal y detección de picos.
6. Extracción de términos relevantes mediante TF-IDF.
7. Interpretación de resultados y limitaciones.

## Tecnologías

`Python` · `Pandas` · `VADER` · `TextBlob` · `TF-IDF` · `Matplotlib` · `WordCloud`

## Principales hallazgos

- Los mayores movimientos del indicador coincidieron con noticias regulatorias.
- Los períodos positivos estuvieron asociados con aprobaciones de ETFs y adopción institucional.
- La incertidumbre regulatoria y la volatilidad dominaron los períodos negativos.
- Las diferencias entre fuentes sugieren que el medio de publicación debe considerarse al interpretar el score.

> Los scores representan señales lingüísticas, no recomendaciones de inversión ni una medición causal del mercado.

## Contenido

- [Notebook completo](./Trabajo%20Final%20Obligatorio%20Data%20Science%20en%20Inversiones.ipynb)

El notebook contiene la preparación de datos, el análisis, las visualizaciones y las conclusiones. Actualmente el repositorio funciona como entrega analítica reproducible desde el notebook; una próxima mejora será separar dependencias, datos y código de extracción.

## Vista previa

![Evolución del sentimiento](https://github.com/user-attachments/assets/b3b5f92d-52cd-4ee0-b332-0023915acb94)

![Términos relevantes](https://github.com/user-attachments/assets/103a94d3-89cd-4f12-a3f4-167ff12be17f)

## Limitaciones

- Los modelos léxicos pueden fallar ante contexto, ironía y negaciones complejas.
- La cobertura depende de las noticias recuperadas y de sus fuentes.
- La coincidencia temporal entre una noticia y un cambio de sentimiento no implica causalidad.

## Autora

**Sofía González Semper** — Data Analytics, operaciones y mejora de procesos.
