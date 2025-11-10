# 🏥 Hospital Beds Management – Hospital San Juan de Dios Rionegro

Este proyecto corresponde a un análisis académico basado en el dataset **Hospital Beds Management**, que simula la operación de un hospital de tamaño medio, incluyendo información sobre pacientes, personal médico, servicios hospitalarios y programación semanal del personal.

El análisis fue desarrollado en **Databricks**, utilizando **PySpark** para la carga, exploración y modelado de los datos, con el objetivo de **comprender la relación entre la demanda de camas, el flujo de pacientes y la disponibilidad de personal** en los distintos servicios del hospital.

---

## 📊 Contenido del Proyecto

- `patients.csv`: Registros de pacientes con información demográfica, fechas de ingreso y egreso, y nivel de satisfacción.
- `services_weekly.csv`: Datos semanales de capacidad de camas, pacientes admitidos y rechazados, satisfacción promedio y eventos especiales.
- `staff.csv`: Información del personal hospitalario, incluyendo nombre, rol y servicio asignado.
- `staff_schedule.csv`: Programación semanal del personal con su presencia o ausencia.

---

## 🧱 Arquitectura y Procesamiento

El proyecto fue implementado en **Databricks (Community Edition)** con la siguiente estructura:
- Creación de un esquema: `hospital_beds_db`
- Carga de los datos desde archivos CSV al volumen `/Volumes/workspace/hospital_beds_db/hospital_beds_volume/`
- Creación de tablas gestionadas (`tbl_patients`, `tbl_services`, `tbl_staff`, `tbl_schedule`)
- Consultas SQL exploratorias para validación y análisis descriptivo

---

## 🗺️ Modelo Entidad–Relación (ERD)

El modelo fue diseñado a partir de las relaciones entre pacientes, servicios, personal y horarios:

![Modelo ERD](https://github.com/usuario/repositorio/raw/main/images/ERD.png)

---

## 🎯 Objetivo del Proyecto

Simular y analizar la gestión de camas hospitalarias del **Hospital San Juan de Dios de Rionegro**, identificando patrones de ocupación, carga laboral y niveles de satisfacción, como base para futuras estrategias de **optimización de recursos hospitalarios**.

---

## 📚 Licencia

Este proyecto utiliza el dataset **Hospital Beds Management** disponible en [Kaggle](https://www.kaggle.com/), bajo la licencia **CC0: Public Domain**, destinado exclusivamente a fines **educativos y analíticos**.
