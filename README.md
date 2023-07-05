# TDA_Stocks_Spain

Este proyecto evalúa el impacto de la Covid-19 en el mercado de valores de España mediante el Análisis Topológico de Datos (TDA) y Redes complejas. Los datos usados han sido los precios bursátiles diarios de las principales empresas cotizadas en España para el periodo 2018-2023, considerándose los periodos temporales anterior y durante la pandemia de la Covid-19.

El Análisis TDA permite determinar el nivel de riesgo del mercado para cada día del periodo analizado. Además, se genera un grafo, mediante la técnica Plannar Maximally Filtered Graph (PMFG) que permite visualizar el estado del mercado en base a las correlaciones entre compañías.

Hay 4 ficheros para las distintas tareas:
1. 'Collect_files.ipynb' - Recolección de datos de las principales compañías cotizadas en España. 
2. 'EDA.ipynb' - Análisis exploratorio de los datos donde se comprueba si la información recolectada está completa y se pre-procesa para su posterior análisis. 
3. 'TDA.ipynb' - Análisis Topológico de Datos (TDA), en este fichero se obtiene una nube de puntos a partir de las series temporales. El objetivo principal es usar TDA para determinar las Lp-norms de los paisajes de persistencia generados por la nube de puntos. Con esto se obtiene un conjunto de fechas críticas.
4. 'Grafos.ipynb' - Análisis basado en redes complejas donde se muestra el grado de interconexión e interdependencia de las compañías en un instante determinado.

