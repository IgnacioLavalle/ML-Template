# ML-Template

El objetivo de este repositorio no es reemplazar las etapas de EDA, Modelado o Feature Engineering, sino ofrecer una base de trabajo reutilizable y robusta para nuevos proyectos de Machine Learning.

La idea es evitar tener que empezar desde cero cada vez que comienza un proyecto. Para eso, estos templates proporcionan una estructura inicial para explorar datasets, construir modelos baseline, experimentar con transformaciones de variables y evaluar resultados.

Cada notebook está diseñado para ser flexible y adaptable a distintos datasets y tipos de problemas, incluyendo clasificación y regresión.

## Notebooks

### 01 - EDA Template (`01_EDA_Template.ipynb`)

Template reutilizable para realizar un Análisis Exploratorio de Datos (EDA) y obtener una primera comprensión del dataset.

Incluye:
- Exploración inicial y estadísticas descriptivas.
- Análisis de calidad de datos (valores faltantes, duplicados, cardinalidad, etc.).
- Análisis univariado y bivariado.
- Distribuciones de variables numéricas y categóricas.
- Análisis de correlaciones y relaciones con la variable objetivo.

### 02 - Baseline Modeling (`02_Baseline_Modeling_Template.ipynb`)

Template para construir modelos iniciales que permitan establecer una referencia de rendimiento antes de invertir tiempo en Feature Engineering u optimización.

Incluye:
- Pipelines de preprocesamiento automatizados.
- Modelos baseline y XGBoost.
- Validación cruzada y comparación de modelos.
- Métricas para problemas de clasificación y regresión.
- Feature Importance, Permutation Importance y valores SHAP.
- Análisis estadístico de variables mediante pruebas ANOVA y Chi-cuadrado.

### 03 - Feature Engineering (`03_Feature_Engineering_Template.ipynb`)

Template para experimentar con transformaciones y nuevas variables, y evaluar si contribuyen a mejorar el rendimiento de los modelos.

Incluye:
- Análisis de asimetría y transformaciones numéricas.
- Extracción de características de fechas y tiempos.
- Estrategias de codificación de variables categóricas.
- Interacciones entre variables y creación de variables derivadas.
- Análisis de redundancia y correlaciones.
- Comparación del rendimiento entre las variables originales y las transformadas.

## Instalación

```bash
pip install -r requirements.txt
```

## Flujo de trabajo

1. **EDA:** explorar el dataset, identificar problemas y comprender las variables.
2. **Baseline Modeling:** construir modelos iniciales y establecer una referencia de rendimiento.
3. **Feature Engineering:** experimentar con transformaciones y nuevas variables.
4. **Modelado específico del proyecto:** implementar y comparar modelos, optimizar hiperparámetros y realizar la evaluación final según los resultados obtenidos.

Estos templates están pensados como un punto de partida, no como un flujo de trabajo obligatorio. Cada proyecto puede requerir distintas técnicas de preprocesamiento, transformaciones, modelos y estrategias de evaluación.