# 📊 Zara Retail Data Analysis: Dashboard Interactivo

## 📝 Descripción del Proyecto
Este repositorio contiene un proyecto integral de análisis de datos de **Zara**, transformando un dataset de retail crudo en una herramienta de toma de decisiones visual y dinámica. El proyecto abarca desde la limpieza de datos (ETL) hasta la creación de KPIs estratégicos para el sector moda.

## 🎯 Objetivos del Análisis
* **Segmentación de Precios:** Clasificación del catálogo en categorías (*Low Cost*, *Standard*, *Premium*).
* **Distribución de Inventario:** Análisis comparativo de volumen de productos por género (Man/Woman).
* **KPIs de Rendimiento:** Monitoreo del precio promedio y peso porcentual de cada segmento.

---

## 🖼️ Vista Previa
![Dashboard Preview](dashboard_preview.png)
*(Asegúrate de que el nombre de tu imagen coincida con "dashboard_preview.png" en tu carpeta de archivos)*

---

## 🛠️ Metodología y Tecnologías
Para este proyecto se aplicó una estructura de **Tres Capas** en Excel:
1. **Capa de Datos (Data):** Limpieza, normalización y creación de nuevas columnas lógicas (segmentación de precios).
2. **Capa de Procesamiento (Analytics):** Tablas dinámicas conectadas para agrupar grandes volúmenes de datos de forma eficiente.
3. **Capa de Presentación (Dashboard):** Interfaz de usuario con segmentadores (Slicers) y gráficos interactivos.

### Funciones y Técnicas Clave:
* **Validación de Datos:** Uso de `SI.ERROR` para el manejo de valores nulos y divisiones por cero en filtros vacíos.
* **Fórmulas Dinámicas:** Implementación de `IMPORTARDATOSDINAMICOS` para asegurar que las tarjetas de KPI sigan al total de la tabla sin importar su tamaño.
* **Diseño UX/UI:** Aplicación de estética minimalista alineada a la marca Zara, eliminando ruido visual (cuadrículas, encabezados de Excel) para una experiencia tipo aplicación.

---

## 📂 Contenido del Repositorio
* `Zara_Analysis_Dashboard.xlsx`: Archivo principal con el Dashboard interactivo y las tablas de datos.
* `zara_raw_data.csv`: Dataset original utilizado para el análisis.
* `dashboard_preview.png`: Captura de pantalla de la interfaz final.

---

## 🚀 Cómo utilizar el archivo
1. Descarga el archivo `.xlsx`.
2. Abre el archivo en Excel (se recomienda la versión de escritorio para total interactividad).
3. Utiliza los **segmentadores de la parte superior** para filtrar por género o categoría de precio y observa cómo los KPIs se recalculan automáticamente.

---
**Desarrollado por Sebastian Mayorga** *Junior Data Analyst*
