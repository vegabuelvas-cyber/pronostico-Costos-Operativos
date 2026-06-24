# Pronostico-Costos-Operativos:
Caso de negocio de Pronostico de Costos Operativos e IA

## Objetivo:

Desarrollar modelos predictivos para pronosticar los costos de dos equipos operacionales. Adicional se diseñó un agente de IA capaz de responder preguntas sobre los resultados obtenidos e incorporar información externa de mercado.

## Alcance del caso:

- Análisis exploratorio de datos.
- Selección de variables.
-  Modelos de forecasting (ARIMA).
- Modelos de regresión lineal multiple para estimación de costos.
- Arquitectura Cloud propuesta en Microsoft Azure.
- Agente de IA con capacidades RAG.
- Integración de información de mercado mediante HTTP.

## Arquitectura Propuesta:

1. Ingesta e integración de datos mediante Azure Data Factory.
2. Almacenamiento en Azure Data Lake Gen2 bajo arquitectura Medallion.
3. Procesamiento y preparación de datos con Databricks.
4. Entrenamiento y despliegue de modelos con Azure Machine Learning.
5. Consumo de resultados mediante: Power BI, aplicaciones web y Agente de IA.

## Tecnologías Utilizadas:

- Python
- Pandas
- Scikit-Learn
- Statsmodels
- Microsoft Azure
- Azure Machine Learning
- Make AI Agents
- ChatGPT (LLM)
- RAG (Retrieval-Augmented Generation)

## Autor:

Wilfredo Vega Buelvas
