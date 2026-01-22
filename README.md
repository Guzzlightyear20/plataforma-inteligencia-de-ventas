📊 Sales Intelligence Dashboard | Plataforma de Inteligencia de Ventas










🇬🇧 English
🚀 Project Overview

An interactive sales analytics dashboard built with Python, Streamlit, Pandas, and Plotly.
This project automates a complete end-to-end data pipeline that transforms raw CSV files into business insights and interactive visualizations.

Users can upload sales data and instantly explore KPIs, trends, top products, and customers—without writing a single line of code.

🧠 Key Features

📂 Upload multiple CSV files via UI

🧹 Automated data cleaning & validation

🔗 Data unification across multiple sources

🏷️ Rule-based product categorization

📊 Interactive KPIs & charts

📥 Export clean master dataset

⚡ Cached processing for performance

📁 Required Input Files
File	Description
clientes.csv	Customer data
productos.csv	Product catalog
ventas.csv	Sales transactions
detalle_ventas.csv	Sale line items

Files are uploaded directly from the sidebar.

⚙️ Data Pipeline

Load CSV files with Pandas

Clean and normalize data

Apply business rules (categorization, validation)

Merge datasets into a master table

Enrich data with time-based features

Generate KPIs and visualizations

Export unified dataset

📊 KPIs Included

💰 Total Revenue

🧾 Number of Transactions

🎟️ Average Ticket Value

📈 Visualizations

Revenue trend over time (line chart)

Top 10 products by revenue (bar chart)

Revenue by category (donut chart)

Top customers by city (table)

🛠️ Tech Stack

Python

Streamlit

Pandas

Plotly

▶️ Run Locally
pip install streamlit pandas plotly
streamlit run app.py

🎯 Use Cases

Data Analyst portfolios

Sales & business intelligence analysis

SMB reporting dashboards

Analytics proof-of-concept projects

📌 Why This Project Matters

Demonstrates real-world skills in:

Data pipelines

Business-oriented data cleaning

Data visualization & storytelling

Building data products, not just notebooks

🇪🇸 Español
🚀 Descripción del Proyecto

Dashboard interactivo de análisis de ventas desarrollado con Python, Streamlit, Pandas y Plotly.
El proyecto implementa un pipeline completo de datos, transformando archivos CSV crudos en información clara y accionable para el negocio.

Permite cargar datos comerciales y visualizar métricas clave, tendencias, productos y clientes destacados sin conocimientos técnicos avanzados.

🧠 Funcionalidades Principales

📂 Carga de múltiples archivos CSV

🧹 Limpieza automática de datos

🔗 Unificación de fuentes comerciales

🏷️ Categorización de productos por reglas de negocio

📊 KPIs y gráficos interactivos

📥 Exportación del dataset final

⚡ Optimización mediante cache

📁 Archivos Requeridos

Archivo	Descripción

- clientes.csv / Información de clientes

- productos.csv /	Catálogo de productos

- ventas.csv / Ventas generales

- detalle_ventas.csv / Detalle por producto

⚙️ Pipeline de Datos

Carga de datos

Limpieza y normalización

Aplicación de reglas de negocio

Cruce de tablas

Enriquecimiento temporal

Visualización y KPIs

Exportación del dataset maestro

📊 Métricas Incluidas

💰 Ingresos Totales

🧾 Cantidad de Ventas

🎟️ Ticket Promedio

📈 Visualizaciones

Evolución de ventas en el tiempo

Top productos por ingresos

Ingresos por categoría

Mejores clientes por ciudad

🛠️ Tecnologías

Python

Streamlit

Pandas

Plotly

▶️ Ejecución Local
pip install streamlit pandas plotly
streamlit run app.py

🎯 Casos de Uso

Portfolio de Analista de Datos

Inteligencia comercial

Reporting para PyMEs

Proyectos demostrativos de BI

🚧 Future Improvements | Próximas Mejoras

Filtros por fecha, ciudad y categoría

Integración con bases de datos

Autenticación de usuarios

Deploy en Streamlit Cloud
