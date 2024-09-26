# Data Science Fundamentals

Ficha Técnica: Proyecto de Análisis de Datos

Título del Proyecto: Fundamentos de Ciencia de Datos con Python en google Colab

Objetivo:
aplicar conocimientos de python y sus librerías asociadas para la ciencia de datos

Equipo:
Trabajo Individual.

Herramientas y Tecnologías:
- Python
- Pandas
- Numpy
- Matplotlib
- Google Colab

Procesamiento y análisis:
- limpieza de datos
- exploración de datos
- Técnicas de Análisis de datos
  
Resultados y Conclusiones:
Se realizaron histogramas para ver la distribución de los datos y diagramas de dispersión junto o tro tipo de diagramas para analizar datos.


Segmentacion de Tipo de Cliente:

```python
import math
df_ROMGB = df[df['ROM_GB'] == 64]
num_observaciones = df_ROMGB.shape[0]
num_bins = int(math.sqrt(num_observaciones))
plt.figure(figsize=(8,4), dpi=100)
plt.hist(df['ROM_GB'],bins = num_bins,color = '#67c2d3',alpha = 0.7,edgecolor = '#3d3b65', label = 'Datos')
plt.grid(True)
plt.xlabel('Valores de GB en ROM')
plt.ylabel('Frecuencia')
plt.title('Histograma')
plt.legend()
plt.show()
```


Enlaces de interés:
[google colab](https://colab.research.google.com/drive/1AaEoG8x4nBSlNU8YXmHMloXB5S4SwrS1?usp=sharing)
