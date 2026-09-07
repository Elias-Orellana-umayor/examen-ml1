# examen-ml1
examen de machine learning 1
Examen de Machine Learning: Predicción de Precios de Viviendas (California Housing)

Este repositorio contiene la resolución del examen práctico correspondiente a la aplicación de modelos de Machine Learning, siguiendo estrictamente la estructura solicitada en el documento de evaluación.

Fases del Proyecto

*   Fase 1: Análisis Exploratorio de Datos (EDA) y Entorno:** Limpieza de datos, manejo de valores nulos, visualización de distribuciones y configuración del control de versiones.
*   Fase 2: Preprocesamiento y Clustering:** Implementación de pipelines de transformación, reducción de dimensionalidad mediante PCA y segmentación de datos utilizando el algoritmo K-Means (optimizado mediante el análisis del punto de inflexión y coeficiente de Silhouette).
*   Fase 3: Modelado Supervisado y Evaluación:** Entrenamiento y ajuste de hiperparámetros mediante `GridSearchCV` para modelos paramétricos (Ridge Regression) y de ensambles (Random Forest Regressor). Exportación de métricas de rendimiento (RMSE, MAE, R², MAPE).
*   Fase 4: Interpretación y Conclusiones:** Análisis comparativo del rendimiento de los modelos, justificación técnica del agrupamiento y presentación de hallazgos en el notebook.

Estructura del Repositorio

*   `Examen.ipynb`: Cuaderno principal de Jupyter que contiene todo el desarrollo lógico, el código en Python y las conclusiones técnicas.
*   `tabla_comparativa_modelos.csv`: Resultados de las métricas finales de los modelos de regresión.
*   `figures/`: Directorio que almacena los gráficos generados (dispersión PCA, métricas de clústeres y residuales).

Tecnologías Utilizadas

*   **Lenguaje y Entorno:** Python, Jupyter Notebook.
*   **Librerías de Datos:** Pandas, NumPy.
*   **Machine Learning:** Scikit-Learn.
*   **Visualización:** Matplotlib, Seaborn.
*   **Control de Versiones:** Git y GitHub.

Declaración de Uso de IA

Para la estructuración del flujo de trabajo, depuración de código y apoyo conceptual durante el desarrollo de las diferentes fases de este proyecto, se utilizó GEMENI como asistente de inteligencia artificial.
