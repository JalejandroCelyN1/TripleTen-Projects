# Proyecto 9 - Prediccion de churn (Beta Bank)

## Resumen
Este proyecto construye un modelo para predecir la baja de clientes (churn) en Beta Bank y priorizar acciones de retencion.

- Mejor modelo: Random Forest con `class_weight='balanced'` (200 arboles, `max_depth=10`).
- Desempeno en test: F1 = 0.629, AUC-ROC = 0.863 (cumple el objetivo).
- Uso recomendado: ordenar clientes por riesgo de churn para enfocar la retencion.

## Datos
- Archivo: `data/Churn.csv`
- Tamano: 10,000 filas y 14 columnas
- Objetivo: `Exited` (1 = churn, 0 = no churn)
- Desbalance: ~20% de churn

## Enfoque
- Limpieza y preparacion:
  - Eliminacion de identificadores (`RowNumber`, `CustomerId`, `Surname`).
  - Imputacion de faltantes (mediana en numericas, mas frecuente en categoricas).
  - One-hot encoding para `Geography` y `Gender`.
- Division estratificada: 80% train / 10% valid / 10% test.
- Modelos evaluados:
  - Logistic Regression (baseline).
  - Random Forest (baseline).
- Manejo del desbalance:
  - `class_weight='balanced'`.
  - Upsampling de la clase minoritaria.

## Resultados
- Test: F1 = 0.629, AUC-ROC = 0.863.
- Matriz de confusion (test):
  - TN = 712, FP = 85, FN = 71, TP = 132.

## Estructura del proyecto
- `data/` - dataset (Churn.csv)
- `documentation/` - contexto del proyecto
- `execution/` - notebook principal con el analisis

## Como ejecutar
1. Abre `execution/project.ipynb` en Jupyter o VS Code.
2. Ejecuta todas las celdas en orden.

## Requisitos
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
