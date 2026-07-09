# Procesamiento de ECG y Detección de Arritmias (MIT-BIH)

Este proyecto está enfocado en el desarrollo de un pipeline en Python para el preprocesamiento, filtrado y reconstrucción de señales electrocardiográficas (ECG) utilizando la base de datos pública MIT-BIH, con el objetivo de limpiar la señal biomédica y dejarla óptima para el entrenamiento de modelos de Machine Learning.

## 🛠️ Fases del Desarrollo

1. **Adquisición y Lectura de Señales:** Conexión y extracción de registros climáticos desde la base de datos fisiológica MIT-BIH.
2. **Filtrado Digital (Preprocesamiento):** Implementación de filtros en Python (filtros pasa-banda, muesca/notch) para la eliminación de artefactos comunes en entornos médicos, como el ruido por línea de base, interferencia de la red eléctrica (50/60 Hz) y artefactos musculares.
3. **Reconstrucción de la Señal:** Análisis temporal y frecuencial para asegurar la preservación de los complejos QRS y ondas críticas (P, T) esenciales para el diagnóstico.
4. **Diseño Orientado a ML:** Estructuración y extracción de segmentos de la señal limpia, preparando la matriz de datos para futuros modelos de clasificación automática de arritmias.

## 💻 Tecnologías Utilizadas
* **Python** (SciPy para procesamiento de señales, NumPy, Pandas, Matplotlib)
* **WFDB library** (Waveform Database para manejo de registros MIT-BIH)
* **Jupyter Notebook**

## 📂 Contenido del Repositorio
* `procesamiento_ecg.ipynb`: Código con la carga de datos, aplicación de filtros y visualización de señales antes/después del proceso de limpieza.
* `README.md`: Documentación del proyecto.
