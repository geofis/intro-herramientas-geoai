Módulo: Introducción a la Inteligencia Artificial Geoespacial
================

# Diapositivas

[Módulo: Introducción a la Inteligencia Artificial Geoespacial. Nivel ·
Demo e integración de pipelines
reales](https://geofis.github.io/intro-herramientas-geoai/presentacion.html)

<img src="img/qr.jpg" width="25%" />

# 🧠 Introducción a la Inteligencia Artificial Geoespacial

- **Duración:** 3 horas  
- **Curso:**
- **Objetivo general:** Dar a conocer conceptos, herramientas y
  aplicaciones de la Inteligencia Artificial aplicada a datos y
  tecnologías geoespaciales (*GeoAI*).

------------------------------------------------------------------------

## 🎯 Objetivos Específicos

1.  Entender qué es *GeoAI* y por qué es relevante en geociencias, GIS y
    análisis espacial.  
2.  Explorar el ecosistema de herramientas y paquetes disponibles, con
    énfasis en QGIS, plugins relevantes y bibliotecas abiertas como
    *GeoAI* de Qiusheng Wu.  
3.  Identificar ejemplos de aplicaciones prácticas (detección de
    objetos, segmentación de imágenes, generación de descripciones
    geoespaciales, etc.).  
4.  Recorrer brevemente recursos educativos clave disponibles (cursos,
    libros, repositorios y materiales de apoyo).

------------------------------------------------------------------------

## 🧩 Agenda / Contenido

### ⌛ **Bloque 1 — Qué es GeoAI** (45 min)

**Temas:**

- Definición de *GeoAI* y relación con GIS, teledetección y análisis
  espacial.  
- Inteligencia Artificial vs. Aprendizaje automático vs. Aprendizaje
  profundo: conceptos básicos.  
- Aplicaciones generales de *AI* en geociencias: clasificación,
  segmentación, detección, predicción.
- El concepto de *GeoAI* integra inteligencia artificial con datos y
  métodos geoespaciales, facilitando tareas como clasificación y
  segmentación automatizada (Wu 2024a).

**Lecturas sugeridas:**

- *GeoAI: Artificial Intelligence for Geospatial Data*, Qiusheng Wu —
  visión general del paquete *GeoAI* y sus capacidades (clasificación,
  segmentación, visualización, preparación de datos) diseñado para
  conectar AI con análisis geoespacial. (Wu 2024a)

------------------------------------------------------------------------

### ⌛ **Bloque 2 — Herramientas y Ecosistema GeoAI** (1 h)

#### 🔹 *GeoAI* Python Package

- Introducción a la biblioteca *GeoAI* (Python) y sus principales
  módulos:
  - Descarga automática de datos geoespaciales.  
  - Automatización de preparación de datos y generación de datasets.  
  - Modelos de segmentación, clasificación e inferencia.  
  - Visualización integrada.  
- ¿Por qué es accesible para principiantes y educadores?  
- Ejemplos de flujos de trabajo (conceptuales).

**Conceptos clave:** - Integración con PyTorch y transformadores para
análisis avanzado.  
- Automatización de tareas de segmentación y clasificación (Wu 2024a) —

### 🔹 QGIS y los Plugins AI más relevantes

**Plataforma base:** QGIS (software GIS libre y extensible mediante
complementos) (QGIS Development Team 2024)

**Plugins destacados:**

1.  **GeoAI (Plugin QGIS)** – Modelo *Moondream* (vision-language):

    - *Caption* — genera descripciones de imágenes geoespaciales.  
    - *Query* — consulta usando lenguaje natural.  
    - Detección de objetos y segmentación.  
    - Entrenamiento e inferencia de modelos de segmentación. (Wu 2024a)

2.  **SamGeo** – Usa el *Segment Anything Model* para segmentación con
    prompts (texto, puntos, cajas) (Wu 2024b)

3.  **Earth Engine Data Catalogs, Maxar Open Data, NASA Earthdata,
    etc.** — acceso y visualización de datos de satélite desde QGIS
    (para uso en flujos de *AI*) (Wu and giswqs 2026a, 2026b)

4.  **Geo Knowledge AI** – asistente AI para guiar proyectos
    geoespaciales dentro de QGIS (ej. modelado de terreno, análisis
    hidrológico, generación de código PyQGIS) (Geo Knowledge AI
    Contributors 2024; QGIS Plugin Contributors 2024).

------------------------------------------------------------------------

### ⌛ **Bloque 3 — Aplicaciones prácticas demostradas** (1 h)

**Conceptos y ejemplos** *(Aquí se muestran con pantallas o mini-demos,
sin programación profunda)*

#### 🛰️ Detección y Segmentación

- Extracción automática de objetos en imágenes satelitales o ortofotos
  (edificios, carreteras, agua).  
- Casos de uso: catastro, monitoreo urbano, gestión de recursos
  naturales.

#### 🧠 Vision-Language

- Usar descripciones en lenguaje natural para analizar imágenes
  geoespaciales (por ejemplo: “¿Dónde están las zonas verdes?”). (Wu
  2024a)

------------------------------------------------------------------------

### 🧪 Bloque 4 — Recursos educativos y profundización (45 min)

**Libros y material de apoyo:**

Una introducción accesible a la programación aplicada a GIS se presenta
en (Wu 2023a).

📘 **“Introducción a la Programación GIS” – Qiusheng Wu**  
- Manual práctico con ejemplos en Python enfocado a geoespacial. Útil
para quienes quieran aprender a procesar datos espaciales de forma
programática.

**Materiales de curso relacionados:**

- *Curso: Introducción a R y QGIS para el análisis geoespacial con apoyo
  de inteligencia artificial*  
  → Contenidos y ejercicios que pueden conectar con conceptos de GeoAI
  (R + QGIS).  
  → Repositorio: <https://github.com/geofis/curso-r-qgis-2024-verano>

- *Análisis Espacial – Maestría en Geografía, Teledetección…*  
  → Algunos conceptos se apoyan en materiales docentes desarrollados
  previamente Martínez, José et al. (2019). → Ejercicios clásicos de
  análisis espacial que pueden ampliarse con métodos AI.

**Recomendaciones de aprendizaje continuo:**

- Explorar tutoriales y workshop de *GeoAI* en Python disponibles en la
  página oficial.
- Probar los plugins en QGIS paso a paso (instalación y uso básico).
- Una introducción accesible a la programación aplicada a GIS se
  presenta en (Wu 2023a).

------------------------------------------------------------------------

## 🧠 Actividades sugeridas (sin programar)

1.  **Instalar QGIS y explorar los plugins**:
    - En QGIS existen complementos recientes que incorporan modelos de
      visión artificial y lenguaje natural, como el plugin GeoAI (QGIS
      Plugin Contributors 2024) y SamGeo (Wu 2024b).
    - Buscar e instalar el plugin *GeoAI* desde el repositorio de QGIS.
    - Explorar *SamGeo* y *Geo Knowledge AI*.
2.  **Ejercicio guiado (grupal):**
    - Cargar una ortofoto y usar el plugin *GeoAI* para etiquetar o
      segmentar características (ej. edificaciones).
3.  **Discusión:**
    - ¿Qué limitaciones observaste en las herramientas de GeoAI?
    - ¿Cómo crees que AI puede transformar análisis espacial en tu área
      de trabajo?

------------------------------------------------------------------------

## 📚 Bibliografía y Lecturas

- Wu, Qiusheng. *GeoAI: Artificial Intelligence for Geospatial Data* —
  documentación principal del paquete GeoAI. (Wu 2024a)
- QGIS Plugin: GeoAI — capacidades de visión por lenguaje y segmentación
  en QGIS. (QGIS Plugin Contributors 2024)
- Leanpub: *Introducción a la Programación GIS* (Qiusheng Wu) (Wu 2023b,
  2023a)
- QGIS Plugins (general) — plataforma desde la cual se instalan
  complementos. (QGIS Plugin Contributors 2024)
- Repositorios y materiales del curso R + QGIS y Análisis espacial
  (enlaces provistos).

------------------------------------------------------------------------

## 🏁 Cierre y próximos pasos

Al terminar este módulo, los y las participantes deberán:

✔ Comprender el rol de IA en el análisis geoespacial.  
✔ Saber identificar y usar herramientas de *GeoAI* dentro de QGIS.  
✔ Estar listos para explorar iniciativas más avanzadas (modelos,
pipelines y aplicaciones específicas).

------------------------------------------------------------------------

<div id="refs" class="references csl-bib-body hanging-indent"
entry-spacing="0">

<div id="ref-qgis_geoknowledge_ai" class="csl-entry">

Geo Knowledge AI Contributors. 2024. “Geo Knowledge AI Plugin for QGIS.”
<https://plugins.qgis.org/plugins/geo_knowledge_ai/>.

</div>

<div id="ref-analisis_espacial_maestria" class="csl-entry">

Martínez, José et al. 2019. “Maestría En Geografía, Teledetección y SIG.
Material de Apoyo: Análisis Espacial.”
<https://github.com/maestria-geotel-master/material-de-apoyo>.

</div>

<div id="ref-curso_r_qgis_geoai" class="csl-entry">

———. 2024. “Introducción a r y QGIS Para El Análisis Geoespacial Con
Apoyo de Inteligencia Artificial.”
<https://github.com/geofis/curso-r-qgis-2024-verano>.

</div>

<div id="ref-qgis_software" class="csl-entry">

QGIS Development Team. 2024. “QGIS Geographic Information System.” Open
Source Geospatial Foundation. <https://qgis.org>.

</div>

<div id="ref-qgis_geoai_plugin" class="csl-entry">

QGIS Plugin Contributors. 2024. “GeoAI QGIS Plugin.”
<https://plugins.qgis.org/plugins/geoai/>.

</div>

<div id="ref-wu_gispro_es_2023" class="csl-entry">

Wu, Qiusheng. 2023a. *Introducción a La Programación GIS*. Leanpub.
<https://leanpub.com/gispro-es>.

</div>

<div id="ref-wu_gispro_2023" class="csl-entry">

———. 2023b. *Introduction to GIS Programming*. Leanpub.
<https://leanpub.com/gispro>.

</div>

<div id="ref-wu_geoai_website" class="csl-entry">

———. 2024a. “GeoAI: Artificial Intelligence for Geospatial Data.”
<https://opengeoai.org/>.

</div>

<div id="ref-qgis_samgeo_plugin" class="csl-entry">

———. 2024b. “SamGeo QGIS Plugin.”
<https://plugins.qgis.org/plugins/samgeo/>.

</div>

<div id="ref-qgis_maxar_open_data" class="csl-entry">

Wu, Qiusheng, and giswqs. 2026a. “Maxar Open Data Plugin for QGIS.” Open
Geospatial Solutions / QGIS Plugin Repository.
<https://github.com/opengeos/qgis-maxar-plugin>.

</div>

<div id="ref-qgis_nasa_earthdata_plugin" class="csl-entry">

———. 2026b. “NASA Earthdata Plugin for QGIS.” Open Geospatial Solutions
/ QGIS Plugin Repository.
<https://github.com/opengeos/qgis-nasa-earthdata-plugin>.

</div>

</div>
