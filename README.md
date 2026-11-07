# Tablero de Mando Ejecutivo: Mercado de Hospedaje Airbnb en Ciudad de México

Dashboard interactivo desarrollado en Power BI para el análisis exploratorio de precios, segmentación territorial y detección de los alojamientos turísticos de mayor cotización en Ciudad de México a partir de datos públicos de Airbnb.

---

## 🎯 Objetivo de Negocio

Proporcionar a inversores turísticos, operadores inmobiliarios y analistas de mercado una herramienta visual para identificar zonas de alto valor (*premium listings*), patrones de concentración de oferta y correlación entre tarifas, tipo de propiedad y disponibilidad territorial.

---

## 📊 Vista Previa del Dashboard

*(Las capturas se visualizan directamente a partir de las imágenes subidas al repositorio)*

[dashboard_view1.png]

---

## 💡 Preguntas Clave Respondidas

* **Distribución Territorial del Precio:** ¿Cuáles son las alcaldías y colonias con el valor promedio por noche más elevado? (ej. Cuauhtémoc, Miguel Hidalgo, Benito Juárez).
* **Top Hospedajes Premium:** ¿Cuáles son las propiedades con tarifas récord y qué características comparten (habitaciones completas, capacidad, amenidades)?
* **Oferta por Tipo de Alojamiento:** Distribución porcentual entre alojamientos enteros (*entire home*), habitaciones privadas y compartidas.
* **Disponibilidad vs. Precio:** Relación entre el nivel de ocupación anual y las estrategias de precios dinámicos.

---

## 🛠️ Stack y Capacidades Técnicas

* **Fuente de Datos:** Dataset público estructurado de Airbnb (Inside Airbnb / Kaggle).
* **ETL & Data Cleaning:** 
  * Normalización de variables de precio (remoción de símbolos monetarios, imputación y tratamiento de valores nulos o atípicos).
  * Geocodificación y validación de coordenadas territoriales.
* **Modelado en Power BI:**
  * Creación de modelo relacional estructurado.
  * Tablas de dimensiones (Calendario, Territorio, Tipo de Alojamiento) y tabla de hechos (Listings).
* **Cálculos en DAX:**
  * Métricas de precio promedio, mediana y percentiles de corte.
  * Rankings dinámicos (`RANKX`) para aislar los alojamientos más caros por zona.
  * KPIs acumulados y comparativas porcentuales de participación.

---

## 🚀 Cómo Explorar este Proyecto

1. **En línea / Capturas:** Puedes ver el diseño y distribución de KPIs en las imágenes adjuntas arriba.
2. **Archivo Power BI:** Descarga el archivo `airbnb_cdmx_dashboard.pbix` de este repositorio y ábrelo con **Power BI Desktop** para interactuar con los filtros cruzados, segmentadores y jerarquías territoriales.

---

## 👤 Autor

**Santiago Rodríguez Garay**  
*Lic. en Gestión Turística & Google Certified Advanced Data Analyst*  
* [LinkedIn](https://www.linkedin.com/in/santiago-rodriguez-garay-9b2a3034a)
* [Email](mailto:santiagomanuelrg@gmail.com)
