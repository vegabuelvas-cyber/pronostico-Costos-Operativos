# Pronostico-Costos-Operativos:
Caso de negocio de Pronostico de Costos Operativos e IA

## Objetivo:

Pronostico de costos de dos equipos operacionales y diseñó de un agente de IA para responder preguntas sobre los resultados obtenidos e incorporar información externa de mercado.

## Alcance del caso:

- Análisis exploratorio de datos.
- Selección de variables.
- Modelos de forecasting (ARIMA).
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

- Google Colab (Pandas/Scikit-Learn/Statsmodels)
- Draw.io
- Make AI Agents
- ChatGPT (LLM)
- RAG (Retrieval-Augmented Generation)

## Estructura del repositorio:

- _Summary_Gestion_Costos_Operativos.pdf     --> Documento base de conocimiento para el agente.
- Gestion_Costos_Operativos.ipynb            --> Desarrollo del análisis y pronosticos.
- Arquitectura_Azure_Gestion_Costos.pdf      --> Arquitectura cloud propuesta.
- Arquitectura_Azure_Gestion_Costos.drawio   --> Arquitectura cloud propuesta (Archivo drawio).
- Agente_IA_Pronostico_Costos.pdf            --> Descripción del agente conversacional desarrollado.


## Autor:

Wilfredo Vega Buelvas
