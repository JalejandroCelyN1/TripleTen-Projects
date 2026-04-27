# TripleTen-Projects

Compilacion de proyectos de TripleTen.

## Proyectos

Este repositorio reune los proyectos desarrollados en el marco de mi formacion en TripleTen. Cada carpeta contiene el material correspondiente (principalmente notebooks en Jupyter) con el desarrollo, analisis y conclusiones de cada entrega.

### Proyecto 2 — Data Wrangling
**Enfoque:** Preparacion y depuracion de datos para su analisis.  
**Alcance general:** Revision de calidad, limpieza y transformacion de datasets para garantizar consistencia y usabilidad.  
**Actividades principales:**
- Inspeccion inicial de datos (estructura, tipos, consistencia).
- Tratamiento de valores ausentes, duplicados y formatos inconsistentes.
- Normalizacion y transformacion de variables segun el objetivo del analisis.
- Validaciones finales y generacion de un dataset listo para analisis posterior.  
**Carpeta:** `Proyecto 2`

---

### Proyecto 3 — Data Wrangling (Parte 2)
**Enfoque:** Profundizacion en tecnicas de preparacion de datos y estandarizacion avanzada.  
**Alcance general:** Aplicacion de un flujo de limpieza mas robusto, con enfasis en reglas de negocio, consistencia y trazabilidad del proceso.  
**Actividades principales:**
- Refinamiento de la limpieza y transformacion realizada en etapas previas.
- Estandarizacion de variables y criterios de validacion.
- Preparacion de datos orientada a analisis o modelado (segun aplique).
- Documentacion de decisiones y criterios de tratamiento de datos.  
**Carpeta:** `Proyecto 3`

---

### Proyecto 4 — Analisis Estadistico de Datos
**Enfoque:** Analisis estadistico aplicado para extraer conclusiones y sustentar decisiones con evidencia.  
**Alcance general:** Exploracion cuantitativa, formulacion de hipotesis y evaluacion estadistica de los resultados.  
**Actividades principales:**
- Analisis exploratorio con metricas y visualizaciones.
- Definicion de hipotesis y seleccion de pruebas estadisticas apropiadas.
- Calculo e interpretacion de resultados (p-valores, intervalos de confianza u otros).
- Conclusiones y recomendaciones basadas en evidencia estadistica.  
**Carpeta:** `Proyecto 4`

---

### Proyecto 5 — Proyecto Integrado
**Enfoque:** Desarrollo integral de un caso practico, combinando preparacion de datos, analisis y sintesis de resultados.  
**Alcance general:** Implementacion de un flujo completo de trabajo, desde el entendimiento del problema hasta conclusiones accionables.  
**Actividades principales:**
- Definicion del objetivo y criterios de evaluacion.
- Preparacion de datos (limpieza, transformacion y validacion).
- Analisis y/o modelado (segun el alcance del proyecto).
- Comunicacion de hallazgos: conclusiones, limitaciones y recomendaciones.  
**Carpeta:** `Proyecto 5`

---

### Proyecto 7
**Enfoque:** Ver documentacion y notebook en la carpeta del proyecto.  
**Carpeta:** `Proyecto 7`

---

### Proyecto 8 — Clasificacion de Planes Smart vs Ultra
**Enfoque:** Machine Learning supervisado para recomendacion de planes moviles a partir del comportamiento de usuarios.  
**Objetivo:** Desarrollar un modelo que recomiende correctamente el plan `Smart` o `Ultra` y alcance una exactitud minima de 0.75.  
**Actividades principales:**
- Exploracion y validacion de calidad de datos.
- Segmentacion estratificada en entrenamiento, validacion y prueba.
- Entrenamiento y ajuste de hiperparametros en Arbol de Decision, Random Forest y Regresion Logistica.
- Seleccion del mejor modelo por desempeno en validacion.
- Evaluacion final en prueba con matriz de confusion y prueba de cordura frente a baseline.  
**Resultados clave:**
- Mejor modelo: `RandomForestClassifier`.
- Accuracy en validacion: **0.8180**.
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
**Detalles:** ver [Proyecto 9/README.md](Proyecto 9/README.md)
