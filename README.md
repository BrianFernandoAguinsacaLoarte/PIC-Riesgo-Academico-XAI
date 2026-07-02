# PIC-Riesgo-Academico-XAI

## Descripción

Proyecto de Integración Curricular orientado al análisis comparativo de los modelos **Random Forest** y **XGBoost** para la predicción del riesgo académico en estudiantes de educación superior utilizando el **Open University Learning Analytics Dataset (OULAD)** e incorporando técnicas de **Inteligencia Artificial Explicable (XAI)** mediante **SHAP** y **LIME**.

## Objetivo General

Analizar cuál modelo de clasificación, **Random Forest** o **XGBoost**, presenta el mejor equilibrio entre capacidad predictiva e interpretabilidad para la predicción del riesgo académico mediante métricas estándar de clasificación y técnicas de IA Explicable.

---

# Dataset

Este proyecto utiliza el **Open University Learning Analytics Dataset (OULAD)**.

Debido a las restricciones de tamaño de GitHub, el dataset **no se incluye en este repositorio**.

Puede descargarse desde el sitio oficial del proyecto:

https://analyse.kmi.open.ac.uk/open_dataset

Una vez descargados los archivos CSV, deben colocarse dentro de la siguiente carpeta:

```text
data/
└── raw/
    ├── assessments.csv
    ├── courses.csv
    ├── studentAssessment.csv
    ├── studentInfo.csv
    ├── studentRegistration.csv
    ├── studentVle.csv
    └── vle.csv
```

---

# Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SHAP
- LIME
- Matplotlib
- Seaborn
- Statsmodels
- Imbalanced-learn
- Jupyter Notebook

---

# Estructura del proyecto

```text
PIC-Riesgo-Academico-XAI/
│
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
│
├── notebooks/
│
├── outputs/
│   ├── figures/
│   ├── tables/
│   ├── reports/
│   └── models/
│
├── docs/
│
├── environment/
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

---

# Instalación

Clonar el repositorio:

```bash
git clone https://github.com/BrianFernandoAguinsacaLoarte/PIC-Riesgo-Academico-XAI.git
```

Ingresar al proyecto:

```bash
cd PIC-Riesgo-Academico-XAI
```

Instalar las dependencias:

```bash
pip install -r requirements.txt
```

---

# Ejecución del proyecto

1. Descargar el dataset OULAD.
2. Copiar los siete archivos CSV en la carpeta:

```text
data/raw/
```

3. Abrir Jupyter Notebook o Visual Studio Code.

4. Ejecutar los notebooks siguiendo el orden numérico:

```text
01_data_understanding.ipynb

02_data_preparation.ipynb

03_feature_engineering.ipynb

04_data_preprocessing.ipynb

05_model_training.ipynb

06_model_evaluation.ipynb

07_model_interpretability.ipynb
```

Cada notebook genera los archivos necesarios para la siguiente etapa del proyecto.

---

# Estado del proyecto

🚧 En desarrollo

Actualmente el proyecto se encuentra en fase de construcción siguiendo la metodología **CRISP-ML(Q)**, complementada con **CRISP-DM**, buenas prácticas de **MLOps** y técnicas de **Inteligencia Artificial Explicable (XAI)**.

---

# Autor

**Brian Fernando Aguinsaca Loarte**

Proyecto de Integración Curricular

Universidad Nacional de Loja