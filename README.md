# ANÁLISIS EXPLORATORIO DE DATOS DE SUPERMERCADOS

## OBJETIVO

- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como, por ejemplo, Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

## METODOLOGÍA

Para comenzar el estudio, el primer paso es la recopilación de los datos, se parte de las fuentes de datos principales, tan solo existe la API de Mercadona, la cuál es explorada, creando la petición mediante llamadas a funciones en la documentación de la API. Se obtienen los datos necesarios para su estudio y comparación frente a Carrefour y Dia.

Tras los inconvenientes por la inexistencia de API de los competidores, se ha valorado y realizado la obtención de datos a través del web scrapping de las páginas de Carrefour y Dia. Métodos explorados gracias a los conceptos de programación con Python. En este proceso se han utilizado las librerías de BeautifulSoup, Selenium, Pandas, Request, entre otras, para realizar la petición de servicio, automatizar acciones en el navegador y lectura y parseo de código.

Plasmando así, esta obtención de los datos, sobre: categorías, productos y precios, en un Júpiter Notebook en la aplicación de Google Colaboratory para posteriormente tratar los datos y trabajar sobre ellos.

Tras esto, se organizan y preparan los datos de manera que pueda ser procesado y legible para el tratamiento de datos. Por tanto, se realiza un análisis preliminar para la detección de posibles errores, se descarta la información repetitiva e incompleta, dejando limpios los datos relevantes para la investigación.

Por tanto, se procede al análisis de los datos utilizando el EDA (Exploratory Data Analysis) o análisis exploratorio. Es una fase crucial en el proceso de análisis de datos y se centra en el examen inicial y la comprensión de un conjunto de datos antes de realizar análisis más detallados o modelado.

Durante el EDA se explora visualmente los datos y se aplican técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pueda ser útil para comprender la naturaleza de los datos. Este análisis inicial ayuda a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.


# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo
- **Objetivo:** Analizar la empresa de Mercadona para identificar una fuga detectada de clientes comparando con datos de Carrefour y Dia.
- **Metodología:** Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

## 📚 Descripción del Proyecto
Este proyecto se centra en la recopilación, limpieza, transformación, modelado y análisis de datos para identificar patrones y tendencias en los precios y ventas de supermercados.


## 🛠️ Herramientas Utilizadas
**Python: Lenguaje principal de programación.
**Jupyter Notebook: Plataforma utilizada para el análisis interactivo.
**Librerías:
  - pandas para la manipulación de datos.
  - numpy para operaciones numéricas.
  - matplotlib y seaborn para visualización de datos.
  - BeautifulSoup y Selenium para web scraping.
