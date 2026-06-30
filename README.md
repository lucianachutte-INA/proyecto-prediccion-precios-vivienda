# Predicción de precios de viviendas

## Descripción del proyecto

Este proyecto fue desarrollado como parte del Proyecto Integrador Final de la materia Prácticas Profesionalizantes I, correspondiente a la Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial.

El trabajo simula un proyecto profesional de Ciencia de Datos aplicado a la predicción de precios de viviendas. Para ello, se generó un conjunto de datos sintético con características habitacionales y se entrenó un modelo de Machine Learning para estimar el precio aproximado de una propiedad.

## Problema

La estimación del precio de una vivienda puede resultar compleja, ya que depende de múltiples factores como la superficie, la cantidad de habitaciones, la cantidad de baños, la antigüedad, la ubicación y la disponibilidad de cochera.

El problema abordado consiste en estimar el precio de una vivienda a partir de sus características principales, utilizando técnicas básicas de análisis de datos y Machine Learning.

## Objetivo general

Desarrollar un modelo predictivo que permita estimar el precio de una vivienda a partir de variables descriptivas de la propiedad.

## Objetivos específicos

- Generar un dataset sintético de viviendas.
- Realizar un análisis exploratorio de los datos.
- Preparar las variables para el entrenamiento del modelo.
- Entrenar un modelo de regresión.
- Evaluar el desempeño del modelo mediante métricas.
- Documentar el proceso de trabajo de forma clara y profesional.

## Dataset

El dataset utilizado fue generado de forma sintética con fines académicos. Contiene registros simulados de viviendas y las siguientes variables:

- `superficie_m2`: superficie de la vivienda en metros cuadrados.
- `habitaciones`: cantidad de habitaciones.
- `banios`: cantidad de baños.
- `antiguedad`: antigüedad de la vivienda en años.
- `cochera`: indica si la vivienda posee cochera.
- `zona`: zona geográfica simulada.
- `precio`: precio estimado de la vivienda.

## Metodología

El proyecto se desarrolló siguiendo las siguientes etapas:

1. Definición del problema.
2. Planificación del proyecto mediante Trello.
3. Generación del dataset sintético.
4. Análisis exploratorio de datos.
5. Preparación de variables.
6. Entrenamiento de un modelo de Regresión Lineal.
7. Evaluación del modelo.
8. Documentación en GitHub.
9. Análisis ético y presentación de resultados.

## Sprint Planning

Para la planificación del proyecto se utilizó una dinámica ágil basada en un sprint corto de trabajo. Durante el Sprint Planning se priorizaron las tareas necesarias para construir una primera versión funcional del proyecto.

### Objetivo del sprint

Construir una solución inicial capaz de generar un dataset sintético de viviendas, realizar un análisis exploratorio, entrenar un modelo predictivo, evaluar sus resultados y documentar el proceso.

### Duración estimada

6 días.

### Tareas priorizadas

- Definición funcional del proyecto.
- Diseño del dataset y variables.
- Preparación y exploración de datos.
- Desarrollo del modelo predictivo.
- Evaluación de resultados.
- Documentación técnica del proyecto.
- Análisis ético y limitaciones.

### Criterio de finalización

El sprint se considera finalizado cuando el proyecto cuenta con un notebook funcional, resultados evaluados, documentación en GitHub, informe ético y presentación final preparada.

## Modelo utilizado

Se utilizó un modelo de Regresión Lineal, ya que permite predecir una variable numérica continua, en este caso el precio de una vivienda.

## Métricas de evaluación

Para evaluar el desempeño del modelo se utilizaron las siguientes métricas:

- MAE: Error Absoluto Medio.
- RMSE: Raíz del Error Cuadrático Medio.
- R²: Coeficiente de determinación.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Trello
- GitHub
- Gamma

## Gestión del proyecto

Para la gestión del proyecto se utilizó Trello con una estructura tipo Kanban. El tablero fue organizado en cinco etapas: Backlog, Sprint actual, En desarrollo, En revisión / QA y Finalizado.

Esta organización permitió visualizar el avance del proyecto, priorizar tareas y registrar el flujo de trabajo desde la definición inicial hasta la documentación y presentación final.

## Resultados

El modelo permitió estimar precios de viviendas a partir de variables como superficie, cantidad de habitaciones, baños, antigüedad, cochera y zona.

Al tratarse de un dataset sintético, los resultados tienen un propósito académico y no deben ser utilizados para decisiones inmobiliarias reales.

## Limitaciones

- Los datos utilizados son simulados.
- El modelo no contempla variables económicas reales.
- No se consideran factores externos como inflación, demanda del mercado, cercanía a servicios o estado real de la propiedad.
- El modelo fue desarrollado con fines educativos.

## Conclusión

El proyecto permitió simular el desarrollo de una solución de Ciencia de Datos en un contexto profesional. A través del proceso se aplicaron etapas de planificación, preparación de datos, análisis exploratorio, modelado, evaluación, documentación y comunicación de resultados.

Además, se utilizaron herramientas colaborativas como Trello y GitHub, fortaleciendo habilidades técnicas y profesionales necesarias para participar en proyectos reales del ámbito tecnológico.
