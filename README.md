# Detección de Fraude con Tarjetas de Crédito

## Descripción del Proyecto
Este proyecto consiste en la construcción de un modelo de detección de fraude en transacciones bancarias utilizando técnicas de ciencia de datos y machine learning. 
El objetivo principal es identificar transacciones fraudulentas, basándonos en un dataset con características ya anonimizadas para proteger la confidencialidad de la información.

El problema de detección de fraude es un desafío común en el ámbito financiero, ya que la detección rápida y precisa de actividades fraudulentas evita pérdidas. En este proyecto, utilizaré varios enfoques de machine learning para crear un modelo capaz de diferenciar entre transacciones legítimas y fraudulentas, evaluando su precisión y eficiencia en el proceso.

## Datos
El dataset utilizado para este proyecto proviene de una fuente de transacciones de tarjetas de crédito, donde las variables ya han sido transformadas (columnas V1 a V28) para preservar la privacidad de la información. La columna 'Class' indica si una transacción es fraudulenta (Class = 1) o no fraudulenta (Class = 0).

## Objetivos
- Construir un modelo de clasificación binaria para detectar transacciones fraudulentas.
- Evaluar el modelo en términos de métricas clave.
- Prevenir errores comunes, como la fuga de datos y problemas con el desbalanceo de clases.

## Stack Tecnológico
Este proyecto fue desarrollado utilizando las siguientes tecnologías y bibliotecas:
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- StandardScaler
- Streamlit