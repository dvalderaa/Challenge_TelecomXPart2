# 📡 Telecom X Parte 2 — Predicción de Churn

Proyecto de Machine Learning desarrollado como Challenge del curso de ML en la Especialización en Data Science.

## Objetivo
Identificar los factores que más influyen en la cancelación de clientes y construir modelos predictivos para anticipar el churn.

## Dataset
`datos_tratados.csv` — 7.267 registros de clientes con variables demográficas, de servicio y contractuales, estructuradas en columnas anidadas que fueron aplanadas durante el preprocesamiento.

## Estructura del notebook
1. Carga y exploración inicial
2. Preparación de datos (limpieza, encoding, balanceo)
3. Correlación y análisis de variables clave
4. Modelado predictivo (Regresión Logística y Random Forest)
5. Interpretación y conclusiones

## Modelos utilizados
| Modelo | Accuracy | F1-Score |
|---|---|---|
| Regresión Logística | ~77% | ~0.78 |
| Random Forest | ~90% | ~0.90 |

## Principales hallazgos
- **tenure**, **Charges.Total** y **Charges.Monthly** son los factores más predictivos del churn
- Los clientes con **fibra óptica** y contrato **mensual** presentan mayor riesgo de cancelación
- Los contratos de **dos años** y los servicios adicionales (seguridad, soporte técnico) actúan como factores de retención

## Tecnologías
- Python 3 · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn

## Autor
David Valdera Avellaneda