# Acerca de mí
Graduado de la Universidad Iberoamericana León como Ingeniero en Negocios y Sistemas, con mas de 4 años de experiencia en análisis de datos con herramientas como SQL y Excel. Me apasiona generar insights con datos, con los cuales las empresas pueden tomar mejores decisiones.

## Habilidades tecnológicas
- Análisis y gestión de datos utilizando Excel y SQL
- Visualización de datos con Excel y Power BI (Aprendiendo)

## Proyectos seleccionados
### Movilidad urbana y productividad económica en ciudades de LATAM

### 📌 Descripción del Proyecto

En este proyecto analizo la relación entre la movilidad urbana y la productividad económica en las principales ciudades de América Latina. El objetivo es comprender cómo factores como la congestión vial, los tiempos de viaje y los retrasos influyen en indicadores económicos como el PIB per cápita y el desempleo.

A partir de la integración de datos reales provenientes de TomTom Traffic Index y OECD Cities, busco generar insights que apoyen la toma de decisiones sobre inversión en infraestructura de transporte.

### 🎯 Objetivos del Proyecto

Los principales objetivos de este proyecto son:

- Construir un dataset limpio y unificado a partir de múltiples fuentes
- Aplicar técnicas de limpieza, estandarización y validación de datos
- Enfocar el análisis en ciudades de América Latina
- Calcular indicadores agregados por ciudad y año
- Realizar análisis exploratorio y visualización de datos
- Documentar todo el proceso en Jupyter Notebook
- Exportar un dataset final listo para análisis posteriores

### 💡 Preguntas de Negocio

Este análisis busca responder las siguientes preguntas clave:

- ¿Qué ciudades presentan alta congestión y baja productividad económica?
- ¿Cuáles muestran un mejor equilibrio entre movilidad eficiente y economía sólida?
- ¿Qué variables tienen una relación más fuerte con el desarrollo urbano?

### 🛠️ Herramientas y Tecnologías

- Jupyter Notebook
- Python (Pandas, NumPy, Seaborn, Matplotlib)

### 📂 Datasets Utilizados

Este proyecto utiliza dos fuentes principales de información:

### 1️⃣ tomtom_traffic.csv

Contiene datos en tiempo real sobre tráfico y congestión en distintas ciudades.

Principales variables:

- País (código ISO-3)
- Ciudad (nombre estandarizado)
- Fecha y hora de actualización (UTC)
- Índice de tráfico
- Retrasos por congestión
- Longitud de embotellamientos
- Tiempo promedio de viaje

### 2️⃣ oecd_city_economy.csv

Incluye indicadores económicos y ambientales por ciudad y año.

Principales variables:

- Año
- Ciudad
- País
- PIB per cápita
- Tasa de desempleo
- Contaminación PM2.5
- Población

### 🔄 Flujo de Trabajo del Proyecto

El desarrollo del proyecto siguió las siguientes etapas:

- Carga y exploración inicial de los datasets
- Limpieza y estandarización de columnas y tipos de datos
- Extracción del año y filtrado para 2024
- Cálculo de promedios de tráfico por ciudad
- Integración de datos de movilidad y economía
- Análisis visual de relaciones entre variables
- Elaboración de conclusiones e informe final
