# Movilidad-CDMX-Ecobici

# 🚲 spark-movilidad-ecobici-cdmx

Análisis de movilidad en el sistema ECOBICI de la Ciudad de México usando PySpark y visualizaciones en Python.

---
## Los archivos de codigo se encuentran en la rama master.
---

## 📘 Descripción general

Este proyecto realiza un análisis distribuido de datos reales del sistema ECOBICI en CDMX. Utiliza Apache Spark en un entorno local (VS Code con Jupyter) para explorar patrones de movilidad, identificar horarios de mayor uso, diferencias por edad y género, estaciones más utilizadas, y otros aspectos relevantes del uso de bicicletas públicas.

**Fuente de datos**: [Portal de Datos Abiertos CDMX](https://datos.cdmx.gob.mx/dataset/ecobici)  
**Archivo utilizado**: `Ecobicis.csv`  
**Tamaño**: ~107 MB  
**Formato**: CSV, con columnas como `Hora_Retiro`, `Hora_Arribo`, `Edad_Usuario`, `Genero_Usuario`, `Ciclo_Estacion_Retiro`, `Fecha_Retiro`.

---

## 📓 Notebook: `Practica Spark PPC.ipynb`

Este notebook contiene todo el procesamiento realizado con PySpark y visualización de datos con `matplotlib`. Fue desarrollado y ejecutado localmente desde Visual Studio Code.

### 🔍 Contenido:
- **Carga de datos** con Spark.
- **Transformación de tipos** (fechas y horas).
- **Consultas SQL con Spark** para:
  - Agrupar por hora de llegada y de retiro.
  - Días con mayor demanda.
  - Género y edad de los usuarios.
  - Estaciones de retiro más frecuentes.
- **Visualización de datos** con `matplotlib.pyplot`:
  - Gráficos de líneas, barras y pastel.
  - Estética personalizada: etiquetas, líneas guía, porcentajes, colores.

---

## ✅ Cómo ejecutar

Sigue estos pasos para ejecutar el proyecto en tu equipo local:

### 1. 📁 Clona el repositorio

```bash
git clone https://github.com/tuusuario/spark-movilidad-ecobici-cdmx.git
cd spark-movilidad-ecobici-cdmx
