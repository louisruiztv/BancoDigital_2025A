## 🏦 Proyecto Big Data – Gestión de Datos Bancarios con Python, MongoDB y GitHub
## 📘 Descripción General

Este proyecto tiene como objetivo enseñar a los estudiantes los conceptos fundamentales de Big Data, integrando herramientas modernas de desarrollo como Python, MongoDB, Git, y Visual Studio Code.

El proyecto simula un caso real del sector bancario, desde la creación y depuración de datos, hasta su almacenamiento en una base de datos NoSQL y visualización analítica, aplicando buenas prácticas de versionamiento con GitHub.

## 🚀 Fases del Proyecto

### 🧩 1. Preparación del entorno
### 📁 2. Generación y limpieza de datos
### 🍃 3. Almacenamiento en MongoDB
### 📊 4. Visualización de datos

## 🧠 Competencias a Desarrollar

- Dominio básico de Big Data y NoSQL.
- Manejo de Git y GitHub en proyectos colaborativos.
- Uso de Visual Studio Code como entorno profesional.
- Creación, limpieza y análisis de datos con Python, Pandas y Numpy.
- Conexión y manipulación de bases de datos MongoDB.
- Visualización de datos usando Matplotlib.

## 🗂️ Estructura del Proyecto

```bash
proyecto_bigdata/
│
├── data/
│   └── bancos.csv
│   └── base.csv
│
├── database/
│   └── bancos_clean.csv
│
├── docs/
│   └── cuentas_por_tipo.png
│   └── distribucion_saldos.png
│   └── promedio_saldo_sucursal.png
│
├── scripts/
│   └── 1_Create_files.ipynb
│   └── 2_Create_base_files.ipynb
│   └── 3_Random_data_banco.ipynb
│   └── 4_ETL_bank.ipynb
│   └── 5_Integrated_NoSQL.ipynb
│   └── 6_Visualization_report.ipynb
│
├── main.ipynb
├── README.md
```

## 🧰 Requisitos

1. Python 3.10+
2. MongoDB local (instalado y ejecutando en mongodb://localhost:27017/)
3. Visual Studio Code con extensiones:
- Python
- MongoDB for VS Code
- GitLens

## 🌐 Versionamiento

El control de versiones se realiza con Git.
Ejemplo de flujo de trabajo:

```bash
git checkout -b dev/data_cleaning
git add .
git commit -m "Limpieza de datos bancarios"
git merge dev/data_cleaning
git remote add origin url
git remote -v
git push origin main
```
## 👨‍🏫 Autor

Proyecto desarrollado aplicando conceptos de Big Data, Python y bases de datos NoSQL.
Luis Manuel Ruiz
Fecha: 15.10.2025
