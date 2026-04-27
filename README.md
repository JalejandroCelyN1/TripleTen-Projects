## Proyectos

Este repositorio reúne los proyectos desarrollados en el marco de mi formación en TripleTen. Cada carpeta contiene el material correspondiente (principalmente notebooks en Jupyter) con el desarrollo, análisis y conclusiones de cada entrega.

### Proyecto 2 — Data Wrangling
**Enfoque:** Preparación y depuración de datos para su análisis.  
**Alcance general:** Revisión de calidad, limpieza y transformación de datasets para garantizar consistencia y usabilidad.  
**Actividades principales:**
- Inspección inicial de datos (estructura, tipos, consistencia).
- Tratamiento de valores ausentes, duplicados y formatos inconsistentes.
- Normalización y transformación de variables según el objetivo del análisis.
- Validaciones finales y generación de un dataset listo para análisis posterior.  
**Carpeta:** `Proyecto 2`

---

### Proyecto 3 — Data Wrangling (Parte 2)
**Enfoque:** Profundización en técnicas de preparación de datos y estandarización avanzada.  
**Alcance general:** Aplicación de un flujo de limpieza más robusto, con énfasis en reglas de negocio, consistencia y trazabilidad del proceso.  
**Actividades principales:**
- Refinamiento de la limpieza y transformación realizada en etapas previas.
- Estandarización de variables y criterios de validación.
- Preparación de datos orientada a análisis o modelado (según aplique).
- Documentación de decisiones y criterios de tratamiento de datos.  
**Carpeta:** `Proyecto 3`

---

### Proyecto 4 — Análisis Estadístico de Datos
**Enfoque:** Análisis estadístico aplicado para extraer conclusiones y sustentar decisiones con evidencia.  
**Alcance general:** Exploración cuantitativa, formulación de hipótesis y evaluación estadística de los resultados.  
**Actividades principales:**
- Análisis exploratorio con métricas y visualizaciones.
- Definición de hipótesis y selección de pruebas estadísticas apropiadas.
- Cálculo e interpretación de resultados (p-valores, intervalos de confianza u otros).
- Conclusiones y recomendaciones basadas en evidencia estadística.  
**Carpeta:** `Proyecto 4`

---

### Proyecto 5 — Proyecto Integrado
**Enfoque:** Desarrollo integral de un caso práctico, combinando preparación de datos, análisis y síntesis de resultados.  
**Alcance general:** Implementación de un flujo completo de trabajo, desde el entendimiento del problema hasta conclusiones accionables.  
**Actividades principales:**
- Definición del objetivo y criterios de evaluación.
- Preparación de datos (limpieza, transformación y validación).
- Análisis y/o modelado (según el alcance del proyecto).
- Comunicación de hallazgos: conclusiones, limitaciones y recomendaciones.  
**Carpeta:** `Proyecto 5`

---

### Proyecto 8 — Clasificación de Planes Smart vs Ultra
**Enfoque:** Machine Learning supervisado para recomendación de planes móviles a partir del comportamiento de usuarios.  
**Objetivo:** Desarrollar un modelo que recomiende correctamente el plan `Smart` o `Ultra` y alcance una exactitud mínima de 0.75.  
**Actividades principales:**
- Exploración y validación de calidad de datos.
- Segmentación estratificada en entrenamiento, validación y prueba.
- Entrenamiento y ajuste de hiperparámetros en Árbol de Decisión, Random Forest y Regresión Logística.
- Selección del mejor modelo por desempeño en validación.
- Evaluación final en prueba con matriz de confusión y prueba de cordura frente a baseline.  
**Resultados clave:**
- Mejor modelo: `RandomForestClassifier`.
- Accuracy en validación: **0.8180**.
- Accuracy en prueba: **0.8180**.
- Baseline (`DummyClassifier`): **0.6936**.
- Mejora absoluta sobre baseline: **0.1244** (17.94% relativa).  
**Carpeta:** `Proyecto 8`

---

### Proyecto 9 — Prediccion de churn (Beta Bank)
**Enfoque:** Modelado de churn con manejo de desbalance y priorizacion de retencion.  
**Objetivo:** Predecir si un cliente dejara el banco con F1 >= 0.59 en test.  
**Actividades principales:**
- Limpieza e imputacion de datos, one-hot encoding.
- Entrenamiento y ajuste de Logistic Regression y Random Forest.
- Estrategias para desbalance: `class_weight` y upsampling.
- Evaluacion con F1 y AUC-ROC.
**Resultados clave:**
- Mejor modelo: `RandomForestClassifier` con `class_weight='balanced'` (200 arboles, max_depth=10).
- F1 en test: **0.629**.
- AUC-ROC en test: **0.863**.
**Carpeta:** `Proyecto 9`
