📊 Análisis de Diferentes Tipos de Datos con Pandas y Numpy
Este proyecto tiene como objetivo demostrar la capacidad de análisis y manipulación de datos en Python utilizando librerías como Pandas y Numpy. A través de diferentes fuentes de datos (CSV, JSON, Excel, diccionarios, listas, etc.), se realizan múltiples transformaciones, análisis y visualizaciones, resolviendo desafíos que comúnmente se presentan en ciencia de datos.

🚀 Tecnologías Utilizadas
🐍 Python 3

📦 Pandas

📐 Numpy

📊 Matplotlib (menor medida)

💻 Jupyter Notebook / Google Colab

📁 Archivos en formatos .csv, .json, .xlsx, .txt

🧠 Objetivos del Proyecto
Dominar la lectura y escritura de datos en distintos formatos.

Explorar métodos de manipulación, limpieza y análisis de datos con Pandas.

Familiarizarse con estructuras de datos básicas y avanzadas.

Aprender a resolver problemas comunes al tratar diferentes fuentes y tipos de datos.

🧱 Estructura del Proyecto
Manejo_Dif_Datos_con_Pandas_I_O.ipynb: contiene la lógica principal del proyecto, lectura y escritura de datos.

Numpy_(1).ipynb: implementación y repaso de funcionalidades clave de la librería Numpy.

🔄 Etapas del Desarrollo
Carga y Exploración de Datos
Se trabajó con archivos .csv, .json, .xlsx y datos generados manualmente desde diccionarios y listas.
✅ Solución aplicada: uso de pd.read_*() y manejo de errores al cargar fuentes mal estructuradas.

Transformaciones y Limpieza
Se aplicaron filtros, cambios de tipos de datos, renombramientos de columnas y se eliminaron registros nulos o redundantes.
✅ Solución aplicada: uso intensivo de .dropna(), .astype(), .rename().

Manipulación de Estructuras Numéricas con Numpy
Se realizaron operaciones con arrays, estadísticas básicas y funciones matemáticas.
✅ Solución aplicada: reemplazo de bucles por operaciones vectorizadas.

Documentación y Automatización del Flujo
El código fue comentado en cada sección para facilitar su lectura y aprendizaje.

🛠️ Problemas y Soluciones
Problema	Solución
Formato inconsistente entre archivos	Conversión previa con encoding, sep, y engine
Datos nulos o corruptos	Uso de dropna(), fillna(), y validaciones previas
Estructuras anidadas (JSON complejos)	Normalización con json_normalize()
Tipos de datos incorrectos	Cast automático o explícito con astype()