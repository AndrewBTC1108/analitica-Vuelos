# analitica-Vuelos

# Proyecto de Minería de Datos — Satisfacción de Pasajeros

## Problema
¿Qué factores específicos del servicio (como el WiFi, el espacio para las piernas o el check-in) y características sociodemográficas (como el nivel de ingresos estimado por edad y género) determinan que un pasajero califique su experiencia como "insatisfecha", para que el Director de Experiencia del Cliente decida en qué áreas exactas priorizar el presupuesto de mejoras según el segmento del viajero?

## Estado del Proyecto: Fase de Adquisición de Datos
Se ha completado el primer hito técnico del proyecto:
1. **Recolección:** Se almacenaron las dos fuentes principales en la carpeta `/data` (Kaggle: *Airline Passenger Satisfaction* y *Adult Census Income*).
2. **Cruce (Merge):** Dentro de `/notebooks/01_adquisicion_datos.ipynb` se realizó la ingesta mediante Pandas. Se solucionó el reto de integrar fuentes de distinta granularidad calculando una probabilidad de altos ingresos estadísticos (basado en edad y género del censo) y fusionándola (`left join`) con los pasajeros reales.
3. **Validación:** Se comprobó mediante `.shape` que el cruce fue existoso sin pérdida ni duplicación de encuestas. El Diccionario de Datos actualizado se encuentra documentado en el propio notebook.

## Integrantes
Diego Fernando Giraldo Salazar
Jhon Fredy Morales Palacio
Carlos Andres Toro Cabrera