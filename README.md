# Análisis de Datos para AluraStoreLatam con Python

Este proyecto contiene un análisis de datos realizado para el Sr. Juan, un comerciante y emprendedor, como parte de un reto propuesto por Alaura Latam. El análisis se llevó a cabo utilizando **Python** en un Jupyter Notebook llamado `AluraStoreLatam.ipynb`.

**Repositorio:** [Su repositorio -Challege1---Con-Python_AlauraLatam](https://github.com/SuUsuario/Challege1---Con-Python_AlauraLatam)
**(Reemplace 'SuUsuario' con su nombre de usuario de GitHub)**

## Librerías de Python Utilizadas

El análisis se realizó utilizando las siguientes librerías de Python:

```python
import matplotlib.pyplot as plt
import numpy as np
from adjustText import adjust_text
import matplotlib.ticker as mticker
import folium
from folium.plugins import HeatMap
import pandas as pd

Estas librerías fueron esenciales para:

matplotlib.pyplot: Creación de gráficos y visualizaciones estáticas.

numpy: Realización de operaciones numéricas eficientes.

adjustText: Ajuste automático de etiquetas de texto en gráficos para evitar superposiciones.

matplotlib.ticker: Personalización de las marcas y el formato de los ejes en los gráficos.

folium: Creación de mapas interactivos.

folium.plugins.HeatMap: Generación de mapas de calor para visualizar densidad geográfica.

pandas: Manipulación y análisis de datos estructurados con DataFrames.

Propósito del Análisis
El análisis tuvo como objetivo principal explorar los datos de ventas del Sr. Juan y brindar información útil sobre el rendimiento de sus tiendas. Los objetivos específicos fueron:

Analizar los ingresos totales por tienda.

Identificar categorías de productos más y menos vendidas por tienda.

Evaluar las calificaciones promedio por tienda.

Determinar los productos más y menos vendidos en general.

Calcular el costo de envío promedio por tienda.

La meta fue usar técnicas de Data Science con Python para generar recomendaciones basadas en datos.

Resumen del Análisis
El análisis reveló los siguientes hallazgos para las cuatro tiendas:

Ingresos Totales: La Tienda 1 lidera en facturación, seguida por las Tiendas 2, 3 y 4.

Ventas por Categorías: 'Muebles' y 'Electrónicos' son las más populares. Tienda 4 destaca en 'Juguetes'.

Calificaciones Promedio: Las calificaciones son similares, pero la Tienda 1, aunque factura más, tiene la calificación más baja.

Productos Más/Menos Vendidos: Se detectan patrones únicos por tienda.

Costo de Envío Promedio: Está relacionado con el volumen de ventas, siendo mayor en la Tienda 1.

Conclusión y Recomendación
Aunque inicialmente se consideró la venta de la Tienda 4 por sus menores ventas, el análisis reveló que esta tienda tiene mejor calificación de clientes y costos de envío más bajos. Por ello, se sugiere:

Evaluar y replicar sus buenas prácticas en otras tiendas.

Evitar decisiones apresuradas como cerrar o vender tiendas sin una reestructuración general.

Este análisis proporciona una base sólida para que el Sr. Juan tome decisiones informadas para optimizar su negocio.
