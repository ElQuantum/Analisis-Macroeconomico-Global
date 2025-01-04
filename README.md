# __Análisis Macroeconómico Global__
Este repositorio contiene el proyecto de análisis macroeconómico global basado en datos del Banco Mundial, explorando indicadores clave como el PIB, la tasa de pobreza, emisiones de CO₂, participación laboral, entre otros. Incluye un dashboard interactivo de Power Bi y el código de Python utilizado para la limpieza de datos, creación de base de datos para usar sentencias de SQL y visualizaciones para el análisis de datos.

## __Contenido del Repositorio__

* 📁 __Base de Datos__: Contiene la base de datos que se creó en SQLite, para poder usar sentencias de SQL en el código de Python.
  * `world_data.db`: Base de datos procesada después de la limpieza de datos.

* 📁 __Código__: Contiene el código de Python utilizado para todo el proceso de análisis.
  * `analisis_global.ipynb`: Script para la limpieza de datos, creación de la base de datos, sentencias de SQL y generación de visualizaciones. Cada bloque de Scripts contiene una explicación de qué podemos obetener del análisis específico y por qué lo realizamos.
  * `requiremente.txt`: Versión de bibliotecas necesarias para compilar el archivo de Python.

* 📁 __Dashboard__: Archivo `.pbix` del dashboard de Power Bi.
  * `Analisis macroeconomico.pbix`: Dsahboard interactivo con análisis visual de varias relaciones clave.

* 📁 __Datos__: Contiene los archivo sutilizados para el análisis.
  * `global_data.csv`: Datos crudos descargados de __World Development Indicators__.

* 📁 __Visualizaciones__: Capturas de los gráficos realizados en Python

* 📄 `Análisis_Macroeconómico_Global.pdf`: Contiene un reporte del proyecto con todo el análisis que se realizó tanto en Power Bi, como en Python.


## __Dashboard Interactivo__
El archivo de Power Bi incluye:

* __Análisis del PIB e Inflación__: Crecimiento a lo largo del tiempo y comparación entre economías.
* __Exportaciones e Importaciones__: Comparación de cómo influyen las exportaciones e importaciones de cada país al crecimiento del PIB.
* __Emisiones de CO₂__: Distribución y tendencias globales.
* __Indicadores clave__: Participación laboral, esperanza de vida, acceso a la educación, entre otros.

## __Cómo usar este Proyecto__

1. __Explorar el Dashboard__:
  * Descarga el archivo `Analisis macroeconomico.pbix` y ábrelo en Power Bi Desktop.
2.  __Reproducir el análisis con Python__:
  * Usa el archivo de Python `analisis_global.ipynb` para procesar los datos paso a paso y generar visualizaciones clave. Es necesario descargar también `global_data.csv` para poder usar en el script de Python.
3. __Leer el reporte__:
  * Descargar el archivo `Análisis_Macroeconómico_Global.pdf`, que contiene una síntesis de todo el análisis realizado, juntando resultado de Power Bi y Python.


## __Contribuciones__
Cualquier contribución es bienvenida. Si tienes sugerencias, mejoras o encuentras algún error, por favor envía un _pull request_.
