# PIC-Riesgo-Academico-XAI

## Descripción

Proyecto de Integración Curricular orientado a la evaluación del desempeño predictivo e interpretabilidad de los modelos **Random Forest** y **XGBoost** para la predicción del riesgo académico en estudiantes de educación superior utilizando el **Open University Learning Analytics Dataset (OULAD)** e incorporando técnicas de **Inteligencia Artificial Explicable (XAI)** mediante **SHAP** y **LIME**.

El desarrollo del proyecto se fundamenta en las metodologías **CRISP-DM** y **CRISP-ML(Q)** para la gestión del ciclo de vida del proyecto de ciencia de datos, complementadas con prácticas de **MLOps** para garantizar la reproducibilidad del pipeline de Machine Learning.

---

# Objetivo General

Evaluar el desempeño predictivo e interpretabilidad de los modelos **Random Forest** y **XGBoost** para la predicción del riesgo académico mediante métricas estándar de clasificación y técnicas de Inteligencia Artificial Explicable.

---

# Metodología

El proyecto se desarrolla siguiendo un enfoque metodológico basado en:

- CRISP-DM
- CRISP-ML(Q)
- MLOps
- Explainable Artificial Intelligence (XAI)

Estas metodologías orientan las diferentes actividades del proyecto, desde la comprensión y preparación de los datos hasta el entrenamiento, evaluación e interpretación de los modelos de aprendizaje automático.

---

# Dataset

Este proyecto utiliza el **Open University Learning Analytics Dataset (OULAD)**.

Debido a las restricciones de tamaño de GitHub, el dataset **no se incluye en este repositorio**.

Puede descargarse desde el sitio oficial:

https://analyse.kmi.open.ac.uk/open_dataset

Una vez descargados los archivos CSV, deben colocarse en:

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
- Imbalanced-learn
- Jupyter Notebook

---

# Estructura del proyecto

```text
PIC-Riesgo-Academico-XAI/
│
├── data/
│   ├── raw/              # Datos originales
│   ├── interim/          # Datos integrados y depurados
│   └── processed/        # Datos preparados para modelado
│
├── notebooks/
│   ├── 01_actividad_1_ingesta_integracion_depuracion.ipynb
│   ├── 02_actividad_2_transformacion_ingenieria_caracteristicas.ipynb
│   ├── 03_actividad_3_preprocesamiento_datos.ipynb
│   ├── 04_actividad_4_entrenamiento_modelos.ipynb
│   ├── 05_actividad_5_evaluacion_modelos.ipynb
│   └── 06_actividad_6_interpretabilidad_xai.ipynb
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

# Flujo general del proyecto

El desarrollo del proyecto sigue las siguientes actividades:

| Actividad | Descripción |
|-----------|-------------|
| Actividad 1 | Ingesta, integración y depuración del dataset |
| Actividad 2 | Transformación e ingeniería de características |
| Actividad 3 | Preprocesamiento de datos |
| Actividad 4 | Entrenamiento de los modelos Random Forest y XGBoost |
| Actividad 5 | Evaluación del desempeño predictivo |
| Actividad 6 | Interpretabilidad mediante SHAP y LIME |

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
2. Copiar los siete archivos CSV dentro de:

```text
data/raw/
```

3. Abrir el proyecto en Jupyter Notebook o Visual Studio Code.

4. Ejecutar los notebooks en el siguiente orden:

```text
01_actividad_1_ingesta_integracion_depuracion.ipynb

02_actividad_2_transformacion_ingenieria_caracteristicas.ipynb

03_actividad_3_preprocesamiento_datos.ipynb

04_actividad_4_entrenamiento_modelos.ipynb

05_actividad_5_evaluacion_modelos.ipynb

06_actividad_6_interpretabilidad_xai.ipynb
```

Cada notebook genera los artefactos requeridos para la siguiente actividad del proyecto.

---

# Estado del proyecto

🚧 **En desarrollo**

Actualmente el proyecto se encuentra en la **Actividad 2: Transformación e Ingeniería de Características**, siguiendo las metodologías **CRISP-DM**, **CRISP-ML(Q)**, prácticas de **MLOps** y técnicas de **Inteligencia Artificial Explicable (XAI)**.

---

# Autor

**Brian Fernando Aguinsaca Loarte**

Proyecto de Integración Curricular

Universidad Nacional de Loja
