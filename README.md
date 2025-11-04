# 🦠 Proyecto Data Science COVID-19

Este proyecto simula un flujo de trabajo real de datos en una empresa, utilizando un pipeline ETL con Apache Airflow, PostgreSQL y Pandas para procesar y analizar datos relacionados con el COVID-19.

## 🎯 Objetivos

- Extraer datos públicos de COVID-19.
- Transformar y limpiar los datos.
- Cargar los datos a una base de datos PostgreSQL.
- Realizar análisis exploratorios y visualización.
- Automatizar el flujo completo con Airflow.
- Documentar y versionar el proyecto correctamente.

## 🛠️ Tecnologías

- Python 3.x
- Apache Airflow
- PostgreSQL
- Pandas, NumPy
- Docker (opcional)
- Git / GitHub

## 📁 Estructura del Proyecto

covid_project/
├── dags/
│ └── covid_etl_dag.py
├── data/
│ └── raw/
│ └── processed/
├── notebooks/
│ └── eda.ipynb
├── scripts/
│ └── transform.py
│ └── load.py
├── requirements.txt
├── README.md
└── .gitignore
