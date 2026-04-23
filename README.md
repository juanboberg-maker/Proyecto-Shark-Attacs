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

Objetivo del proyecto → El objetivo de este proyecto es analizar los ataques de tiburón a nivel global para identificar qué actividades acuáticas están más asociadas a los incidentes y en qué países se concentran más.
Se hace especial énfasis en los ataques no provocados (unprovoked), ya que representan mejor el riesgo real para las personas.

# Dataset → 

El dataset utilizado contiene registros históricos de ataques de tiburón, incluyendo variables como:

País (Country)
Actividad realizada (Activity)
Tipo de ataque (Type: Provoked / Unprovoked)
Año (Year)
Especie (Species)
Fatal Y/N

Durante el análisis se realizó una limpieza y estandarización de los datos, especialmente en la variable "Activity", para agrupar actividades similares (por ejemplo: surfing, swimming, diving).


# Proceso de análisis → 

El análisis se desarrolló en varias fases:
Limpieza de datos
Filtrado de datos
Número de ataques por país
número de ataques por actividad
Cruce entre país y actividad
calculo de metricas
Visualización


# Resultados / Insights → Los hallazgos más importantes, claros y accionables.

El análisis muestra que el riesgo no depende solo del número de ataques, sino del tipo de actividad y la interacción con el entorno.

# Próximos pasos → Qué extenderías si tuvieras más datos o más tiempo.
# Cómo replicar el proyecto → Enlace al notebook, queries SQL o dashboard.