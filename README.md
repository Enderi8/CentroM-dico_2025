 CASO BIG DATA PARA ANÁLISIS DE PACIENTES Y SERVICIOS EN UN CENTRO MÉDICO 2025

 🎯 Contexto del Caso
El Centro Médico Bienestar 2025 busca implementar un sistema de análisis de información para conocer mejor el comportamiento de sus pacientes y los servicios que más utilizan.
Actualmente, la información se encuentra dispersa en diferentes archivos CSV con errores, valores nulos y duplicados.
El equipo de analistas de datos ha sido asignado para desarrollar un prototipo funcional usando:

    •	Python (para procesamiento y análisis de datos)
    •	MongoDB (para almacenamiento NoSQL)
    •	Visual Studio Code
    •	Git y GitHub (para control de versiones)
    •	Pandas, NumPy y Matplotlib (para análisis y visualización)
    •	Jenkins (CI - Integración Continua)

🧭 Objetivo General
Desarrollar un proyecto de análisis de datos en el área de salud que integre herramientas de programación, bases de datos NoSQL, control de versiones y visualización de información, aplicando un flujo completo tipo Big Data (recolección, limpieza, almacenamiento, consulta y visualización de datos).

🧩 Objetivos Específicos
    1.	Simular la creación de archivos de datos pacientes (.csv) con información.
    2.	Implementar un proceso ETL (Extracción, Transformación y Carga) para limpiar datos nulos, duplicados o inconsistentes. 
    3.	Cargar los datos limpios en una base de datos MongoDB.
    4.	Generar visualizaciones interactivas sobre:
        o	Gráfico de barras: número de pacientes atendidos por servicio.
        o	Gráfico circular: distribución por sexo.
        o	Histograma: distribución de edades.
        o	Reporte tabular: promedio de montos por distrito.
        5.	Versionar el proyecto completo en GitHub.
    6.	Realizar la validación de integración continua con Jenkins

⚙️ Arquitectura del Proyecto
# 🏦 Proyecto Big Data – Análisis de Pacientes, MongoDB y GitHub
## 📘 Descripción General

El proyecto simula un caso real del sector Salud, desde la creación y depuración de datos, hasta su almacenamiento en una base de datos NoSQL y visualización analítica, aplicando buenas prácticas de versionamiento con GitHub e integración continua con Jenkins.

## 🗂️ Estructura del Proyecto

```bash
SaludDigitalB_E1/
│
├── data/
│   └── pacientes.csv
│   └── base.csv
│
├── database/
│   └── pacientes_clean.csv
│
├── reports/
│   └── pacientes_atendidos_por_servicio.png
│   └── distribución_por_sexo.png
│   └── distribución_de_edades.png
│   └── promedio_de_montos_por_distrito.png
│
├── ci/
│   └── job_jenkins1.png
│   └── job_jenkins2.png
│   └── job_jenkins3.png
│   └── job_jenkins4.png
│   └── job_jenkins5.png
│
├── git/
│   └── 1er_commit.png
│   └── 2do_commit.png
│   └── 3er_commit.png
│   └── 4to_commit.png
│   └── 5to_commit.png
│   └── 6to_commit.png
│
├── scripts/
│   └── 1_Crear_Carpetas.ipynb
│   └── 2_Crear_Estructura.ipynb
│   └── 3_Generar_Data_Turismo.ipynb
│   └── 4_Proceso_ETL.ipynb
│   └── 5_Loading_MongoDB.ipynb
│   └── 6_Reportes.ipynb
│
├── README.md
```

🧱 Estructura de Datos Simulada

Archivo: pacientes.csv

Crear un archivo pacientes.csv en la carpeta /data con la siguiente estructura:

id_paciente	nombre	edad	sexo	distrito	servicio	fecha_atencion	monto
P001	Ana Torres	34	F	Miraflores	Odontología	2024-11-15	150
P002	Luis Pérez	42	M	Surco	Pediatría	2024-10-21	250

🔍 Fases del Proyecto

🧩 Fase 1 – Creación de Archivos

Crear carpetas data, database, reports, ci, git y scripts y estructura base del proyecto usando os y pathlib en tiempo de ejecución

🧩 Fase 2 – Definición de Esquema

Generar un archivo base CSV (base.csv) con la estructura indicada.

🧩 Fase 3 – Generación de Datos Aleatorios
Generar un archivo CSV (pacientes.csv) con 3000 registros simulados, que incluya campos nulos, NA, entre otros

🧩 Fase 4 – ETL (Limpieza de Datos)
•	Eliminar duplicados
•	Rellenar valores nulos en campos de transporte o destino
•	Formatear fechas
•	Validar tipos de datos
Guardar como pacientes_clean.csv.

🧩 Fase 5 – Carga en MongoDB

Crear base de datos SaludDigital_2025 y colección pacientes
Insertar los registros limpios desde CSV.

🧩 Fase 6 – Visualización de Datos

Usar matplotlib y pandas para mostrar:  
    1.	Gráfico de barras: número de pacientes atendidos por servicio.
    2.	Gráfico circular: distribución por sexo.
    3.	Histograma: distribución de edades.
    4.	Reporte tabular: promedio de montos por distrito.



## 👨‍🏫 Autor
```bash
Proyecto desarrollado aplicando conceptos de Big Data, Vs Code, Python, MongoDB y Jenkins.
Ispilco Quispe Jhon Enderson
Fecha: 17.10.2025
```




