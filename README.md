
## Análisis de Patrones de Movilidad Urbana: Sistema Ecobici CDMX

### 1. Descripción del Proyecto

Este proyecto consiste en un análisis exploratorio de datos (EDA) y procesamiento masivo de información del Sistema de Transporte Individual sobre Bicicletas (Ecobici) de la Ciudad de México. El objetivo es transformar datos crudos de viajes en **insigths accionables** sobre cómo se mueven los capitalinos, identificando cuellos de botella en la infraestructura, perfiles demográficos de los usuarios y la eficiencia operativa del sistema durante el periodo [Insertar Año/Meses].

Como  **Ingeniero TIC** , este proyecto demuestra mi capacidad para manejar grandes volúmenes de datos, realizar limpieza técnica (Data Wrangling) y aplicar estadística para entender sistemas complejos de redes urbanas.

---

### 2. Objetivos del Proyecto

#### **Objetivo General**

Analizar el comportamiento de movilidad de los usuarios de Ecobici para optimizar el entendimiento de la demanda de transporte no motorizado en las zonas de mayor actividad económica de la CDMX.

#### **Objetivos Específicos**

* **Limpieza y Curación de Datos:** Identificar y tratar valores atípicos (outliers), como viajes menores a 2 minutos o registros con errores de sistema, para garantizar la integridad estadística.
* **Perfilamiento Demográfico:** Caracterizar a los usuarios mediante medidas de tendencia central (media, mediana) y dispersión (desviación estándar) aplicadas a variables como edad y género.
* **Análisis Temporal de Demanda:** Determinar las "horas pico" y los días de mayor afluencia para entender la diferencia entre el uso recreativo y el uso como último tramo de transporte laboral.
* **Optimización de Red de Estaciones:** Identificar las estaciones con mayor flujo de salida y llegada (top 10) para sugerir áreas donde se requiera mayor disponibilidad de anclajes o mantenimiento.
* **Correlación de Variables:** Analizar la relación entre la duración de los viajes y la distancia estimada entre estaciones mediante coeficientes de correlación.

---

### 3. Alcance Técnico (Stack Sugerido)

* **Lenguaje:** Python.
* **Librerías:** * `Pandas`: Para manipulación y limpieza de los DataFrames.
  * `NumPy`: Para cálculos estadísticos avanzados.
  * `Matplotlib` / `Seaborn`: Para visualización descriptiva (Histogramas, Boxplots).
  * `Folium` o `Geopandas`: (Opcional) Para la creación de mapas de calor geoespaciales.

---

### 4. Preguntas de Negocio a Responder

* ¿Cuál es la estación "fuente" (de donde más salen) más importante de la red?
* ¿Existe una diferencia significativa en la duración del viaje entre hombres y mujeres?
* ¿Qué porcentaje de los viajes totales representan una anomalía (viajes de más de 1 hora)?
* ¿Cómo se comporta la desviación estándar del tiempo de viaje durante los fines de semana?
