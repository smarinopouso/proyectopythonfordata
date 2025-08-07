# Proyecto de Análisis de Datos de Campañas de Marketing

Este proyecto consiste en realizar un análisis exploratorio de los datos proporcionados por el banco portugués, que contienen información sobre campañas de marketing directo realizadas a clientes. Las campañas se basaron principalmente en llamadas telefónicas y se necesitaban varios contactos con los mismos clientes para determinar si un producto bancario (depósito a plazo) sería suscrito o no.

## Objetivo

El objetivo de este proyecto es realizar un **Análisis Exploratorio de los Datos (EDA)** de los conjuntos de datos disponibles, utilizando herramientas de Python, específicamente la librería **Pandas** para la manipulación de datos y **Matplotlib/Seaborn** para la visualización de los resultados.

## Datos

Se trabajaron con dos archivos de datos principales:

1. **bank-additional.csv**: Contiene información relacionada con campañas de marketing directo del banco. Las columnas relevantes son:
   - `age`: Edad del cliente.
   - `job`: Ocupación del cliente.
   - `marital`: Estado civil del cliente.
   - `education`: Nivel educativo del cliente.
   - `default`: Si el cliente tiene historial de incumplimiento de pagos.
   - `housing`: Si el cliente tiene un préstamo hipotecario.
   - `loan`: Si el cliente tiene otro tipo de préstamo.
   - `contact`: Método de contacto utilizado para comunicarse con el cliente.
   - `duration`: Duración de la última llamada.
   - `campaign`: Número de contactos realizados durante esta campaña.
   - `pdays`: Días desde el último contacto.
   - `previous`: Número de contactos previos.
   - `poutcome`: Resultado de la campaña anterior.
   - `emp.var.rate`: Tasa de variación del empleo.
   - `cons.price.idx`: Índice de precios al consumidor.
   - `cons.conf.idx`: Índice de confianza del consumidor.
   - `euribor3m`: Tasa de interés de referencia.
   - `nr.employed`: Número de empleados.
   - `y`: Si el cliente suscribió o no el producto.
   
2. **customer-details.xlsx**: Información adicional sobre los clientes, que incluye:
   - `Income`: Ingreso anual del cliente.
   - `Kidhome`: Número de niños en el hogar.
   - `Teenhome`: Número de adolescentes en el hogar.
   - `Dt_Customer`: Fecha en que el cliente se convirtió en cliente del banco.
   - `NumWebVisitsMonth`: Número de visitas mensuales al sitio web del banco.
   - `ID`: Identificador único del cliente.

## Análisis Realizado

A continuación se detallan las etapas principales de análisis realizadas:

### 1. Transformación y Limpieza de Datos

- Se eliminaron columnas innecesarias y se corrigieron posibles errores en los datos.
- Se gestionaron valores faltantes, específicamente en las columnas `euribor3m` y `nr.employed`.
- Se realizó un análisis de los tipos de datos y se hicieron las conversiones necesarias para asegurar que los datos fueran del tipo adecuado.

### 2. Análisis Descriptivo

- Se generaron estadísticas descriptivas para las columnas numéricas, como medias, medianas, y desviaciones estándar.
- Se exploraron las relaciones entre las variables mediante una matriz de correlación.
- Se analizaron las distribuciones de variables clave como la duración de las llamadas y la edad de los clientes.

### 3. Visualización de los Datos

- Se crearon diversos gráficos:
  - **Histogramas** para explorar la distribución de la edad, duración de las llamadas y otras variables.
  - **Boxplots** para identificar posibles valores atípicos.
  - **Heatmaps** para visualizar la matriz de correlación y las relaciones entre las variables.
  
### 4. Conclusiones

Tras el análisis, se concluyó lo siguiente:
- La mayoría de los clientes son de edad media, con pocos extremos en edades muy jóvenes o muy mayores.
- Las variables `duration` y `previous` son las que más se correlacionan con el hecho de que un cliente suscriba un producto.
- Se identificaron algunos valores atípicos en las columnas de duración de las llamadas y número de contactos previos.
  
## Instrucciones para Ejecutar el Proyecto

1. **Clonar el Repositorio**:
   - `git clone https://github.com/smarinopouso/proyectopythonfordata.git`
   
2. **Instalar Dependencias**:
   - Asegúrate de tener Python instalado en tu máquina.
   - Instala las dependencias necesarias con `pip`:
     ```bash
     pip install -r requirements.txt
     ```
   
3. **Ejecutar el Notebook**:
   - Puedes abrir el archivo `proyectopythonfordata.ipynb` en Jupyter Notebook o en Google Colab.
   
4. **Visualizar los Resultados**:
   - El notebook contiene todo el código para cargar los datos, procesarlos, hacer el análisis descriptivo, y visualizar los resultados.

## Archivos del Proyecto

- **`proyectopythonfordata.ipynb`**: Notebook con el análisis completo.
- **`README.md`**: Descripción detallada del proyecto y los pasos seguidos.
- **`requirements.txt`**: Listado de las dependencias necesarias para ejecutar el proyecto.

## Licencia

Este proyecto está bajo la licencia MIT.

---


