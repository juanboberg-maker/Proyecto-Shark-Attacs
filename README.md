# Proyecto-Shark-Attacs
Proyecto de limpieza y exploración de ataques de tiburón
soy la persona b 
# Objetivo del proyecto
Crear un mapa mundial de riesgo por actividad para analizar qué actividades acuáticas están más asociadas a los ataques de tiburón y en qué países se concentran más los incidentes.
# Preguntas inciales a responder 
¿Qué actividades concentran más incidentes?, ¿En qué países ocurren más ataques según la actividad?, ¿Hay actividades que parecen más peligrosas que otras?, ¿Cambian los patrones si miramos también la gravedad o si el ataque fue fatal?
# columnas que nos pueden servir para el proyecto 
activity, fatal Y/N, Type, Country, Year, Species
## Limpieza y preparación
Se limpiarán valores nulos, duplicados y textos inconsistentes para estandarizar las categorías principales.
## Análisis previsto
Se compararán actividades, países y gravedad de los ataques para detectar patrones de riesgo.


# Título del proyecto → Shark Attack Risk Analysis: Global Activity-Based Risk Map

Analizar los ataques de tiburón a nivel global para identificar qué actividades acuáticas presentan mayor riesgo y en qué países se concentran más los incidentes.

Se pone especial foco en diferenciar entre ataques provocados y no provocados, con el objetivo de evaluar el riesgo real asociado a cada actividad.

# Dataset → 

El dataset utilizado contiene registros históricos de ataques de tiburón a nivel mundial.

Variables principales utilizadas:

country → país donde ocurre el ataque
activity → actividad realizada
type → tipo de ataque (provoked / unprovoked)
year → año del incidente
species → especie del tiburón
fatal y/n → si el ataque fue fatal

Durante el análisis se realizó una selección de variables relevantes para simplificar el estudio.


# Proceso de análisis → 

El análisis se llevó a cabo en varias etapas:

1. Limpieza de datos

Conversión de nombres de columnas a minúsculas
Eliminación de valores nulos en variables clave (country, activity, type)
Revisión y eliminación de duplicados

2. Transformación de variables

Creación de una nueva variable activity_clean
Agrupación de actividades similares en categorías:
Surfing
Swimming
Diving
Fishing
Shallow water
Board sports
Snorkeling
Other

3. Filtrado

Selección de ataques no provocados (Unprovoked) para analizar el riesgo real

4. Análisis exploratorio

Conteo de ataques por país
Conteo de ataques por actividad
Análisis cruzado entre país y actividad
Cálculo de porcentajes por país

5. Análisis de riesgo

Comparación entre ataques provocados y no provocados por actividad
Clasificación de actividades según su peligrosidad


# Resultados / Insights → Los hallazgos más importantes, claros y accionables.

Los principales hallazgos del análisis son:

* Estados Unidos y Australia concentran la mayor cantidad de ataques de tiburón a nivel global.
* Swimming y Surfing son las actividades con más incidentes registrados.
* El surfing presenta un mayor riesgo real, ya que concentra una alta proporción de ataques no provocados.
* La pesca (fishing), aunque presenta muchos incidentes, está más asociada a ataques provocados, lo que reduce el riesgo en condiciones normales.
* Una parte significativa de los ataques ocurre en aguas poco profundas, lo que indica que el riesgo no se limita al mar abierto.
* El riesgo varía según el país, aunque existen patrones globales comunes.

# Próximos pasos → Qué extenderías si tuvieras más datos o más tiempo.

Posibles mejoras del proyecto:

Analizar evolución temporal de los ataques
Diferenciar entre ataques fatales y no fatales
Construir un modelo predictivo de riesgo

# Cómo replicar el proyecto → Enlace al notebook, queries SQL o dashboard.

Para replicar el análisis:

Clonar el repositorio
Ejecutar el notebook principal
Asegurarse de tener instaladas las librerías necesarias:
pandas

El código incluye todo el proceso de limpieza, transformación y análisis de los datos.