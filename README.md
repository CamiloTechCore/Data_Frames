# Data Viz & Analytics Hub 📊

Este repositorio es un ecosistema dedicado al **almacenamiento, procesamiento y visualización de datos**. Aquí documento el ciclo de vida completo del dato: desde su captura en bases de datos relacionales y almacenes en la nube, hasta la narrativa visual y el análisis crítico final.

## 🛠 Stack Tecnológico

El proyecto se divide en cuatro capas principales:

### 1. Almacenamiento y Cloud
* **BigQuery:** Data Warehouse principal para el manejo de grandes volúmenes de datos y consultas SQL complejas.
* **Supabase:** Backend as a Service (BaaS) utilizado para la gestión de bases de datos relacionales (PostgreSQL) y autenticación rápida.

### 2. Procesamiento y Scripting
* **Python:** Limpieza de datos (Pandas/NumPy), automatización y análisis estadístico.
* **Google Colab:** Entorno de experimentación y cuadernos interactivos para el pre-procesamiento de datos.
* **JavaScript:** Manipulación de datos en el lado del cliente y personalización de componentes visuales.

### 3. Visualización y Front-end
* **Looker Studio:** Dashboards empresariales dinámicos conectados directamente a BigQuery.
* **Power BI:** Modelado de datos avanzado (DAX) y reportes interactivos de alto impacto.
* **HTML:** Estructuración de reportes web personalizados y portafolios de visualización.

### 4. Metodología
* **Análisis Crítico:** No solo mostramos números; aplicamos un pensamiento analítico para identificar sesgos, tendencias reales y responder al "por qué" detrás de los datos.

---

## 📂 Estructura del Repositorio

```bash
├── datasets/             # Archivos CSV/JSON procesados
├── notebooks/            # Cuadernos de Google Colab (.ipynb)
├── sql/                  # Scripts de creación y consulta (BigQuery/Supabase)
├── scripts/              # Automatizaciones en Python y JS
└── dashboards/           # Enlaces y documentación de Power BI y Looker Studio
```

---

## 🚀 Cómo Explorar este Proyecto

1.  **Consulta de Datos:** Revisa la carpeta `/sql` para entender cómo se estructuraron las tablas en **Supabase** y **BigQuery**.
2.  **Procesamiento:** En `/notebooks` encontrarás el paso a paso de la limpieza de datos realizada en **Python**.
3.  **Resultados:** Los enlaces a los dashboards interactivos de **Power BI** y **Looker Studio** se encuentran detallados en el archivo `dashboards/README.md` de esa carpeta.

---

## 💡 Filosofía de Trabajo

Este repositorio se rige bajo el principio de que **un dato sin contexto es solo ruido**. Cada visualización aquí presente incluye una sección de **Análisis Crítico**, donde se evalúa la calidad de la fuente, las posibles correlaciones y las recomendaciones accionables para la toma de decisiones.
