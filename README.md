# Airline Delay Prediction

## Proyecto Final Data Science - CoderHouse

---

## Descripción General

Este proyecto desarrolla un modelo de aprendizaje automático para predecir retrasos en vuelos comerciales. Utilizando datos históricos de vuelos, meteorología, información de aeropuertos y aerolíneas, construimos modelos que alcanzan una precisión del 85% en la predicción de retrasos.

## Objetivos

- Predecir retrasos de vuelos comerciales con precisión
- Identificar factores clave que influyen en los retrasos
- Mejorar la eficiencia operativa de las aerolíneas
- Optimizar la experiencia de viaje de los pasajeros

## Contenido del Repositorio

- `airline_delay_prediction.ipynb` - Análisis completo y modelado
- `airline_data.csv` - Conjunto de datos principal
- `README.md` - Este archivo

## Metodología

### 1. Exploración de Datos (EDA)
- Análisis de distribuciones y relaciones entre variables
- Identificación de valores faltantes y atípicos
- Visualización de patrones estacionales

### 2. Preparación de Datos
- Limpieza de datos y manejo de valores faltantes
- Ingeniería de características
- Escalado y normalización

### 3. Modelado

Se evaluaron múltiples algoritmos:
- Regresión Lineal
- Regresión de Bosque Aleatorio (Random Forest)
- Redes Neuronales

### 4. Evaluación

Métricas utilizadas:
- Precisión (Accuracy)
- Recall (Sensibilidad)
- F1-Score
- Validación Cruzada

## Resultados Principales

**Mejor Modelo:** Regresión de Bosque Aleatorio
- **Precisión:** 85%
- **Características Clave:** Hora del día, condiciones meteorológicas, aerolínea

## Variables Analizadas

- **Información del Pasajero:** ID, nombres, género, edad, nacionalidad
- **Datos de Aeropuertos:** Nombre, código de país, continente
- **Información de Vuelos:** Fecha de salida, aeropuerto de llegada, estado
- **Factores Operacionales:** Piloto, tiempo de espera en pista, congestión

## Preguntas de Investigación

1. ¿Cuáles son las principales causas de retrasos?
2. ¿Cómo varían los retrasos por aerolínea?
3. ¿Existe relación entre la hora de salida y la probabilidad de retraso?
4. ¿Cómo afecta la estación del año a los retrasos?
5. ¿Qué impacto tiene la congestión del aeropuerto?

## Requisitos

```
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow
```

## Instalación

```bash
pip install -r requirements.txt
```

## Uso

1. Abre el archivo `airline_delay_prediction.ipynb` en Jupyter Notebook
2. Ejecuta todas las celdas en orden
3. Visualiza los resultados y análisis

## Impacto Potencial

- Mejora de la puntualidad operativa
- Reducción de costos para aerolíneas
- Experiencia mejorada para pasajeros
- Optimización de recursos

## Autor

Luciano Benjamín Taddeo Córdoba

## Fecha Actualización

Febrero 2026

---

*Este proyecto fue desarrollado como parte del Programa de Data Science de CoderHouse (Comisión 46270)*
