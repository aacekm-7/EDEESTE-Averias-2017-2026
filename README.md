# ⚡ Análisis de Averías y Emergencias | Excel + Power BI

Análisis de datos de **averías y emergencias eléctricas por provincia en República Dominicana**, utilizando datos abiertos oficiales y un flujo de trabajo basado en **Excel, Power Query, Power BI y DAX**.

El proyecto transforma un dataset transaccional en un **modelo estrella** orientado al análisis de tendencias, distribución geográfica, tipos de averías y variaciones interanuales.

---

## 🎯 Objetivo del proyecto

Transformar datos públicos de averías y emergencias eléctricas en información útil para analizar el **comportamiento y distribución de los incidentes a través del tiempo y territorio**.

El análisis se enfoca principalmente en:

- 📈 Evolución de las averías a través de los años.
- 📅 Tendencias y variaciones interanuales.
- 🌎 Distribución de incidentes por provincia.
- ⚡ Tipos y categorías de averías.
- 🚨 Identificación de zonas con mayor volumen de incidentes.
- 📊 Comparación del comportamiento entre períodos.

---

## 🛠️ Herramientas utilizadas

| Herramienta | Uso |
|---|---|
| **Excel** | Exploración y preparación inicial |
| **Power Query** | Limpieza, transformación y normalización |
| **Power BI** | Modelado y visualización |
| **DAX** | Medidas, KPIs y análisis temporal |

---

## 📂 Dataset

Fuente oficial: [Estadísticas de Averías y Emergencias Atendidas](https://datos.gob.do/dataset/estadisticas-de-averias-y-emergencias-atendidas)

Dataset publicado en el **Portal de Datos Abiertos de la República Dominicana**.

El conjunto de datos contiene información sobre las averías y emergencias atendidas, permitiendo analizar variables como **año, provincia y tipo de avería**.

---

## 🔎 Preguntas de análisis

### 📈 Rendimiento y tendencias

- ¿Cómo evolucionan las averías a través del tiempo?
- ¿Qué años presentan mayores variaciones?
- ¿Existen patrones o períodos con incrementos relevantes?

### 🌎 Distribución geográfica

- ¿Qué provincias concentran mayor cantidad de incidentes?
- ¿Cómo se distribuyen las averías geográficamente?
- ¿Qué zonas presentan mayor volumen de incidencias?

### ⚡ Tipos de averías

- ¿Qué tipos de avería son más frecuentes?
- ¿Qué categorías representan mayor carga operativa?
- ¿Cómo cambia la distribución de averías según provincia y año?

### 🚨 Priorización operativa

- ¿Qué provincias concentran mayor volumen de incidentes?
- ¿Qué tipos de avería requieren mayor atención por frecuencia?
- ¿Qué categorías presentan comportamientos relevantes para la planificación operativa?

---

## 💡 Principales insights

- 📈 **El volumen de averías presenta variaciones importantes entre años**, permitiendo identificar períodos de mayor y menor incidencia.
- 🌎 **La distribución de incidentes no es uniforme entre provincias**, existiendo zonas con una concentración considerablemente mayor.
- ⚡ **Algunos tipos de avería concentran una parte importante de los incidentes**, representando una mayor carga operativa.
- 📊 El análisis **YoY permite identificar cambios significativos entre períodos** y facilita el seguimiento de la evolución de los incidentes.
- 🚨 La combinación de **provincia + tipo de avería + período** permite identificar dónde se concentra la mayor carga de atención.
- 📅 El análisis temporal permite detectar **patrones y variaciones que pueden ser utilizados para planificación y asignación de recursos**.

---

## 🧩 Modelado de datos

El proyecto utiliza un **modelo estrella** diseñado para facilitar el análisis en Power BI.

El proceso de transformación incluyó:

- Limpieza y normalización de datos.
- Corrección de problemas de codificación.
- Transformación mediante **Power Query**.
- Unpivot de columnas.
- Creación de columnas de fecha.
- Generación de claves sustitutas.
- Construcción de tablas de dimensiones.
- Creación de una tabla de hechos.
- Implementación de relaciones entre dimensiones y hechos.

<img width="1173" height="679" alt="Modelo de datos" src="https://github.com/user-attachments/assets/fc6754c7-3637-42e5-b030-a5fd8bd8786b" />

---

## 📊 Dashboard

El dashboard permite analizar de forma interactiva:

- 💎 KPIs generales.
- 📈 Evolución anual.
- 📊 Variación YoY.
- 🌎 Distribución por provincia.
- ⚡ Tipos de avería.
- 📅 Tendencias temporales.
- 🔎 Comparaciones entre períodos y categorías.

<img width="1405" height="790" alt="Dashboard" src="https://github.com/user-attachments/assets/a4dce352-86a0-48a7-a407-dc3edcdb441e" />

---

## ⚠️ Limitación del proyecto

El dashboard fue desarrollado utilizando **Power BI Desktop en su versión gratuita**.
Debido a las limitaciones de la versión utilizada, algunas opciones avanzadas de personalización visual no fueron incorporadas.

---

## 📌 Conclusión

Este proyecto demuestra el uso de **Excel + Power Query + Power BI + DAX** para transformar datos públicos en una solución de Business Intelligence.

El análisis permite estudiar la **evolución temporal, distribución geográfica y comportamiento por tipo de avería**, proporcionando una visión estructurada de los incidentes y facilitando la identificación de zonas y categorías con mayor volumen de atención.
