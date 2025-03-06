# Dashboard de Terremotos a Nivel Mundial

Crear un **dashboard interactivo utilizando Plotly y Dash**. 

Con esa información desarrollar un conjunto de visualizaciones interactivas que proporcionen una comprensión profunda de los patrones y tendencias de los terremotos. Este ejercicio te permitirá aplicar conocimientos adquiridos sobre visualización de datos y desarrollo de dashboards con herramientas de Python.

El dataset contiene información detallada sobre terremotos, incluyendo:
+ fecha y hora del evento
+ magnitud
+ profundidad
+ país en el que ocurrió.

Utilizar esta información para crear varios gráficos interactivos que ayudarán a explorar y presentar los datos de manera efectiva.

### Consigna

Desarrollar un dashboard interactivo utilizando **Plotly** y **Dash** para visualizar los datos de terremotos proporcionados en el archivo `earthquake data.csv`. 

Asegúrate de que el dashboard tenga un diseño limpio y organizado, con títulos claros y descripciones para cada gráfico.

1. **Cargar y Preparar los Datos**: Carga el archivo `earthquake data.csv` y realiza las transformaciones necesarias, como convertir la columna de fecha y hora al formato datetime.

2. **Creación de Gráficos**: Crea los siguientes gráficos usando plotly:
    + **Mapa Coroplético**: Un mapa coroplético que muestre la densidad de terremotos por región.
    + **Gráfico de Barras**: Un gráfico de barras que muestre el número de terremotos por magnitud.
    + **Gráfico de Líneas**: Un gráfico de líneas que muestre la tendencia de la magnitud de los terremotos a lo largo del tiempo.
    + **Gráfico de Dispersión**: Un gráfico de dispersión que muestre la relación entre la magnitud de los terremotos y su profundidad.
    + **Gráfico 3D**: Un gráfico 3D que visualice la relación entre magnitud, profundidad y tiempo.

3. **Diseño de la Aplicación**: Usando Dash, crea la aplicación con el Layout del Dashboard, en el que deben desplegarse todos los gráficos que has preparado. Finalmente ejecuta la aplicación.
