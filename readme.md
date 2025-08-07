# Informe de Análisis Exploratorio de Datos (EDA) - Campañas de Marketing Bancario

## Objetivo
Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) sobre el dataset de campañas de marketing de un banco portugués. El análisis incluye limpieza de datos, estadísticas descriptivas y visualización de las distribuciones y relaciones entre las variables.

## Paso 1: Carga y Limpieza de Datos
- Se cargaron los datos desde el archivo CSV `bank-additional.csv` y se inspeccionaron las primeras filas para verificar la estructura.
- Se manejaron valores nulos y se transformaron las columnas necesarias para un análisis adecuado.

## Paso 2: Análisis Descriptivo
- Realizamos un análisis de las variables numéricas del dataset. Por ejemplo, observamos que la mayoría de los clientes tienen entre 30 y 50 años, y que el rango de valores de la variable `duration` es bastante amplio, con algunos valores atípicos.

## Paso 3: Visualización de los Datos
- **Histograma de la edad**: Mostró que el rango de edad más común entre los clientes del banco es entre los 30 y los 50 años.
- **Boxplot de la duración de las llamadas**: Indicó que la mayoría de las llamadas fueron de duración corta, pero también se observaron algunos valores atípicos que podrían indicar interacciones inusualmente largas.
- **Heatmap de la correlación**: Ayudó a visualizar las relaciones entre las variables numéricas, revelando que algunas variables tienen correlaciones débiles, pero **emp.var.rate** y **previous** están moderadamente correlacionadas.

## Paso 4: Conclusiones
- Las visualizaciones ayudaron a entender la distribución y posibles patrones en los datos. 
- Las relaciones entre las variables son generalmente débiles, pero algunas pueden ser relevantes para futuros análisis y modelos predictivos.

## Referencias
- Enlace al dataset utilizado: [Bank Dataset]