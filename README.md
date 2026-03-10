# Challenge Alura Store: Análisis de Rendimiento Comercial

## Descripción del Proyecto
Este repositorio contiene el código y la documentación del proyecto "Challenge Alura Store", enfocado en la aplicación práctica de Ciencia de Datos. El objetivo principal es realizar un Análisis Exploratorio de Datos (EDA) sobre las métricas comerciales y operativas de cuatro sucursales de una cadena de retail para fundamentar decisiones corporativas estratégicas, incluida la posible reestructuración o venta de alguna de las tiendas.

## Estructura del Repositorio
* `CHALLENGE_ALURA_STOREpynb.ipynb`: Notebook de Jupyter que contiene el código fuente, el análisis de datos mediante Pandas y las visualizaciones generadas con Matplotlib.
* Archivos de datos (`Tienda1.csv`, `Tienda2.csv`, `Tienda3.csv`, `Tienda4.csv`): Conjuntos de datos base con los registros de ventas, categorías de productos, costos de envío y calificaciones de satisfacción del cliente. *(Nota: Estos archivos deben ubicarse en el mismo directorio que el notebook para su correcta ejecución).*

## Tecnologías y Herramientas
* **Lenguaje:** Python 3
* **Manipulación y Análisis de Datos:** Pandas
* **Visualización de Datos:** Matplotlib
* **Entorno de Desarrollo:** Jupyter Notebook / Google Colab

## Metodología del Análisis
El flujo de trabajo documentado en el notebook sigue estas fases:
1. **Importación y Exploración Inicial:** Carga de los archivos CSV y revisión de las estructuras de los *DataFrames*.
2. **Análisis de Facturación:** Cálculo del volumen total de ingresos generados por cada sucursal.
3. **Ventas por Categoría:** Identificación de los volúmenes de rotación por tipo de producto (destacando el dominio de la categoría "Muebles").
4. **Calificación Promedio:** Evaluación del nivel de satisfacción del cliente en una escala de 0 a 5.
5. **Productos Extremos:** Extracción automatizada de los artículos con mayor y menor volumen de ventas por locación.
6. **Análisis Logístico:** Cálculo de los costos promedio de envío asumidos por cada sucursal.
7. **Visualización:** Representación gráfica de los hallazgos mediante gráficos de barras y líneas para facilitar la toma de decisiones.

## Principales Conclusiones (Insights)
* **Rendimiento Financiero:** La Tienda 1 es el activo de mayor recaudación (~$1.15 mil millones). En contraste, la Tienda 4 registra el menor volumen comercial (~$1.03 mil millones), posicionándose como la principal candidata a venta si el criterio corporativo es estrictamente financiero.
* **Paradoja Operativa (Riesgo en Tienda 1):** A pesar de su liderazgo en ingresos, la Tienda 1 refleja saturación operativa: asume los costos promedio de envío más altos ($26,018.61) y presenta el índice de satisfacción al cliente más bajo de la cadena (3.98/5). 
* **Patrón de Consumo:** La categoría "Muebles" es transversalmente el motor principal de ventas, sin embargo, la demanda específica varía demográficamente (ej. el producto estrella en la Tienda 2 es el curso "Iniciando en programación").

## Instrucciones de Ejecución (Setup)
Para reproducir este análisis en un entorno local, ejecuta los siguientes comandos en tu terminal:

1. Clona este repositorio:
   ```bash
   git clone <INSERTA_AQUI_LA_URL_DE_TU_REPOSITORIO>
