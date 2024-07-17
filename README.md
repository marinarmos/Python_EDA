# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📬 Contacto
Si tienes alguna pregunta o comentario, no dudes en contactarme a través de [tu_email@example.com](mailto:tu_email@example.com).

## 📝 Licencia
Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
# 📊 Análisis Exploratorio de Datos de Supermercados

## 📝 Resumen Ejecutivo

### Objetivo
- Se propuso analizar la empresa de Mercadona para identificar una fuga detectada de clientes. 
- El objetivo principal fue identificar patrones y tendencias comparando los datos obtenidos a través de la API de Mercadona frente a los de empresas competidoras como Carrefour y Dia.
- Se elaboró un Júpiter Notebook en el cual se emplearon técnicas de extracción y análisis estadístico para explorar y modelar los datos. 
- La metodología incluyó la recolección, limpieza, transformación, modelado y evaluación de los resultados obtenidos.

### Metodología
- **Recopilación de datos:** El primer paso fue la recopilación de datos desde la API de Mercadona, creando peticiones mediante llamadas a funciones en la documentación de la API. Se obtuvieron los datos necesarios para su estudio y comparación frente a Carrefour y Dia.
- **Web Scraping:** Debido a la inexistencia de API de los competidores, se realizó la obtención de datos a través del web scraping de las páginas de Carrefour y Dia. Se utilizaron las librerías de BeautifulSoup, Selenium, Pandas y Requests para realizar la petición de servicio, automatizar acciones en el navegador y leer y parsear el código.
- **Tratamiento de datos:** Los datos obtenidos fueron plasmados en un Júpiter Notebook en la aplicación de Google Colaboratory para su posterior tratamiento.
- **Preparación de datos:** Se organizaron y prepararon los datos para que fueran procesados y legibles. Se realizó un análisis preliminar para detectar posibles errores, descartando información repetitiva e incompleta y dejando limpios los datos relevantes para la investigación.
- **Análisis Exploratorio de Datos (EDA):** Se procedió al análisis de los datos utilizando EDA. Durante el EDA se exploraron visualmente los datos y se aplicaron técnicas estadísticas para identificar patrones, tendencias, valores atípicos y cualquier otra información relevante que pudiera ser útil para comprender la naturaleza de los datos. Este análisis inicial ayudó a formular preguntas más específicas, guiar la elección de métodos analíticos y proporcionar información valiosa para la toma de decisiones.

## 🛠️ Herramientas Utilizadas
- **Python:** Lenguaje principal de programación.
- **Jupyter Notebook:** Plataforma utilizada para el análisis interactivo.
- **Librerías:**
  - `pandas` para la manipulación de datos.
  - `numpy` para operaciones numéricas.
  - `matplotlib` y `seaborn` para visualización de datos.
  - `BeautifulSoup` y `Selenium` para web scraping.

## 📊 Visualizaciones
Se generaron diversas visualizaciones para entender mejor los datos. Aquí hay un ejemplo de una visualización utilizada:

![Ejemplo de Visualización](images/ejemplo_visualizacion.png)

## 🔍 Descripción del Conjunto de Datos
El conjunto de datos incluye registros de ventas, precios y categorías de productos de Mercadona, Carrefour y Dia.

### Atributos Principales
1. **ID:** Identificador único del producto.
2. **Nombre del Producto:** Nombre del producto tal como aparece en el supermercado.
3. **Categoría:** Categoría del producto.
4. **Precio:** Precio del producto.
5. **Supermercado:** Supermercado del cual se obtuvieron los datos.

## 📥 Descarga
Puedes descargar el notebook desde [aquí](Analisis_EDA.ipynb).
