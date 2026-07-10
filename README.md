# Procesamiento de ECG y Detección de Arritmias (MIT-BIH)

Traducir / Translate / Traduzir:
[🇪🇸 Español](#-español) | [🇺🇸 English](#-english) | [🇧🇷 Português](#-português)

---

## 🇪🇸 Español

Este proyecto está enfocado en el desarrollo de un pipeline en Python para el preprocesamiento, filtrado y reconstrucción de señales electrocardiográficas (ECG) utilizando la base de datos pública MIT-BIH, con el objetivo de limpiar la señal biomédica y dejarla óptima para el entrenamiento de modelos de Machine Learning.

### 🛠️ Fases del Desarrollo
1. **Adquisición y Lectura de Señales:** Conexión y extracción de registros clínicos desde la base de datos fisiológica MIT-BIH.
2. **Filtrado Digital (Preprocesamiento):** Implementación de filtros en Python (filtros pasa-banda, muesca/notch) para la eliminación de artefactos comunes en entornos médicos, como el ruido por línea de base, interferencia de la red eléctrica (50/60 Hz) y artefactos musculares.
3. **Reconstrucción de la Señal:** Análisis temporal y frecuencial para asegurar la preservación de los complejos QRS y ondas críticas (P, T) esenciales para el diagnóstico.
4. **Diseño Orientado a ML:** Estructuración y extracción de segmentos de la señal limpia, preparando la matriz de datos para futuros modelos de classificação automática de arritmias.

### 💻 Tecnologías Utilizadas
* **Python** (SciPy para procesamiento de señales, NumPy, Pandas, Matplotlib)
* **WFDB library** (Waveform Database para manejo de registros MIT-BIH)
* **Google Colab**

---

## 🇺🇸 English

This project focuses on developing a Python pipeline for the preprocessing, filtering, and reconstruction of electrocardiogram (ECG) signals using the public MIT-BIH database. The main objective is to clean the biomedical signal, making it optimal for training Machine Learning models.

### 🛠️ Development Phases
1. **Signal Acquisition & Reading:** Connecting and extracting clinical records from the MIT-BIH physiologic database.
2. **Digital Filtering (Preprocessing):** Implementation of digital filters in Python (band-pass, notch) to remove common artifacts in medical environments, such as baseline wander, powerline interference (50/60 Hz), and muscle artifacts.
3. **Signal Reconstruction:** Time and frequency domain analysis to guarantee the preservation of QRS complexes and critical waves (P, T) essential for clinical diagnosis.
4. **ML-Oriented Design:** Structuring and extracting clean signal segments, preparing the data matrix for future automated arrhythmia classification models.

### 💻 Technologies Used
* **Python** (SciPy for signal processing, NumPy, Pandas, Matplotlib)
* **WFDB library** (Waveform Database for MIT-BIH record management)
* **Google Colab**

---

## 🇧🇷 Português

Este projeto está focado no desenvolvimento de um pipeline em Python para o pré-processamento, filtragem e reconstrução de sinais eletrocardiográficos (ECG) utilizando o banco de dados público MIT-BIH, com o objetivo de limpar o sinal biomédico e deixá-lo ideal para o treinamento de modelos de Machine Learning.

### 🛠️ Fases do Desenvolvimento
1. **Aquisição e Leitura de Sinais:** Conexão e extração de registros clínicos do banco de dados fisiológico MIT-BIH.
2. **Filtragem Digital (Pré-processamento):** Implementação de filtros em Python (filtros passa-faixa, rejeita-faixa/notch) para a eliminação de artefatos comuns em ambientes médicos, como a oscilação da linha de base, interferência da rede elétrica (50/60 Hz) e artefatos musculares.
3. **Reconstrução do Sinal:** Análise temporal e frequencial para garantir a preservação dos complexos QRS e ondas críticas (P, T) essenciais para o diagnóstico.
4. **Design Orientado a ML:** Estruturação e extração de segmentos do sinal limpo, preparando a matriz de dados para futuros modelos de classificação automática de arritmias.

### 💻 Tecnologías Utilizadas
* **Python** (SciPy para processamento de sinais, NumPy, Pandas, Matplotlib)
* **WFDB library** (Waveform Database para gerenciamento de registros MIT-BIH)
* **Google Colab**

---

## 📂 Contenido del Repositorio / Repository Content
* `procesamiento_ecg.ipynb`
* `README.md`
