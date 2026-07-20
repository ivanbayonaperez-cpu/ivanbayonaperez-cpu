# Iván Bayona Pérez | Data Analyst & Ingeniero Industrial 📊

Ingeniero Industrial especializado en analítica de datos, con 7+ años combinando el rigor de la optimización de procesos con la construcción de ecosistemas de BI end-to-end. Transformo datos operativos complejos en dashboards y modelos que habilitan decisiones estratégicas — con un historial real: reduje la consolidación de indicadores de **5 días a tiempo real** sobre una red de **22 sedes**.

Egresado del bootcamp de Data Analytics de **TripleTen**, con práctica aplicada en SQL, Python, análisis estadístico y machine learning sobre casos de negocio reales (retail, ecommerce, telecomunicaciones, movilidad urbana).

---

## 🛠️ Arquitectura y Stack Técnico

- **Análisis y Modelado:** SQL (MySQL), Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **BI y Visualización:** Power BI (Desktop, Service, DAX avanzado, Power Query), Tableau
- **Ingeniería de Datos:** Pipelines ETL/ELT, Modelado de Datos & Data Warehousing
- **Metodologías:** Pruebas de Hipótesis (A/B Testing), Análisis de Cohortes y Funnel, Machine Learning aplicado, Data Storytelling
- **Herramientas:** Git/GitHub, Jupyter Notebooks, Agile/SCRUM

<p align="left">
  <img src="https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/-Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white" />
  <img src="https://img.shields.io/badge/-DAX-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" />
  <img src="https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

---

## ⚙️ Proyectos Destacados

### 🚀 [RappiPlus: De Datos a Decisiones de Negocio — Análisis End-to-End](enlace-a-tu-repo)
*Proyecto insignia — ciclo analítico completo: calidad de datos, rentabilidad, funnel, cohortes, test A/B y dashboard, en un solo caso.*

- **Auditoría de calidad de datos:** Sobre 25,100 pedidos, detecté y documenté devoluciones, valores inconsistentes y duplicados con SQL/Python, dejando el dataset validado con banderas de auditoría (no eliminando datos "sospechosos" sin evidencia).
- **Hallazgo crítico de rentabilidad:** Identifiqué que 10 pedidos (0.04% del dataset) con cantidades no plausibles (10,000–20,000 unidades) distorsionaban el margen reportado del negocio — **11.5% vs. el 30.5% real** una vez excluidos y validados. Recomendé confirmar estos registros con el equipo de operaciones antes de reportarlos como rentabilidad real.
- **Funnel de conversión (SQL):** Construí el embudo completo sobre 7,796 usuarios únicos usando SQL avanzado (CTEs, funciones de ventana), obteniendo una conversión total del 80% e identificando una anomalía en la etapa `add_to_cart` que documenté como hallazgo a validar con el equipo de producto.
- **Retención por cohortes:** Medí retención semanal (semana 1 a 3) por cohorte mensual de registro, encontrando estabilidad entre 40-44% sin señales de fuga crítica.
- **Test A/B con rigor estadístico:** Apliqué una prueba Z de dos proporciones sobre un rediseño de checkout; el resultado no fue estadísticamente significativo (p=0.4161), y lo reporté como tal en vez de forzar una conclusión positiva.
- **Comunicación ejecutiva:** Consolidé los hallazgos en un dashboard publicado en Power BI Service para la toma de decisiones del equipo de negocio.

### 🧪 [Validación de Experimento A/B — Optimización de Landing Page (Ecommerce)](enlace-a-tu-repo)
Evaluación estadística de un experimento A/B sobre 40,000 usuarios para decidir qué versión de página implementar.

- **Diseño estadístico:** Apliqué chi-cuadrado para comparar tasas de conversión y t-test de muestras independientes para comparar gasto promedio, validando significancia (p < 0.001) en ambas métricas antes de recomendar un cambio de producto.
- **Resultado cuantificado:** La versión ganadora mostró +27% en conversión y +12.5% en valor por conversión, con recomendaciones adicionales de rebalanceo de presupuesto por canal de tráfico.
- **Comunicación ejecutiva:** Traduje resultados estadísticos (p-values, intervalos) en una recomendación de negocio clara y accionable para stakeholders no técnicos.

### 🏘️ [Estrategia Comercial — Andes Capital Real Estate](enlace-a-tu-repo)
Dashboard en Power BI con modelo de datos en esquema estrella, DAX avanzado y matriz de cohortes. *Aprobado por revisor externo del bootcamp.*

- **Modelado de datos:** Construí un esquema estrella (tabla de hechos + 3 dimensiones, incluyendo una tabla calendario `dim_fecha` generada con `CALENDAR`/`ADDCOLUMNS`), con medidas DAX que modifican contexto de filtro vía `CALCULATE`.
- **Insight cuantificado:** $6,012.5M en ingresos (+11.14% YoY), con una tasa de recompra del 77.13% y un patrón de churn concentrado en el primer mes (89-94%) — la ventana crítica de retención es inmediata.
- **Análisis de cohortes:** Matriz de recurrencia de clientes en el tiempo, identificando que las cohortes de Q1 2023 generan 3.24 compras promedio por cliente.

### 🛒 [Embudo de Conversión y Retención — MercadoLibre](enlace-a-tu-repo)
Análisis de producto sobre el journey completo de compra, usando SQL avanzado.

- **Ingeniería de consultas:** Construí el embudo multietapa completo (descubrimiento → conversión) usando CTEs en SQL para calcular tasas de conversión entre cada paso.
- **Análisis de cohortes:** Medí retención D7/D14/D21/D28 por país, identificando las etapas de mayor fuga de usuarios y su variación geográfica.

### 💹 [Rentabilidad de Mercado — Adventure Works](enlace-a-tu-repo)
Análisis financiero con SQL sobre 6 mercados, separando eficiencia de producto de eficiencia de inversión en marketing.

- **Hallazgo cuantificado:** El margen operativo es uniforme entre mercados (~43%), pero el ROI de marketing varía de 17% a 76% — aislando el problema real: eficiencia de inversión, no de producto.
- **Análisis de escenario:** Modelé el efecto de un incremento del 50% en gasto de campañas sobre el ROI proyectado por mercado, para soportar la recomendación de reasignación de presupuesto.

### 📱 [Segmentación de Clientes — Telecomunicaciones (ConnectaTel)](enlace-a-tu-repo)
Análisis de comportamiento de uso real (llamadas, mensajes) para una empresa de telecomunicaciones en LATAM.

- **Rigor de limpieza:** Apliqué verificación estadística MAR (Missing At Random) para justificar la conservación de nulos informativos, y detecté valores sentinel (`-999`) que distorsionaban las métricas antes de corregirlos.
- **Detección de valor:** Identifiqué el segmento de "power users" (15-20% de la base) mediante el método IQR, decidiendo conservar los outliers por justificación de negocio en vez de eliminarlos automáticamente.

### 🏥 [Automatización de Vigilancia Epidemiológica — Subred Centro Oriente](enlace-a-tu-repo)
*Proyecto real de mi rol profesional, no un caso de bootcamp.*

* **Arquitectura ETL:** Diseñé un flujo de extracción (OneDrive) y transformación (DAX en Power BI) para digitalizar el seguimiento de higiene de manos en 22 hospitales.
* **Impacto medido:** Eliminé el 100% de la transcripción manual de datos, reduciendo la disponibilidad de reportes de días a minutos, con adopción exitosa en toda la red.

---

## 📈 Estadísticas de GitHub

<p>
<img src="https://github-readme-stats.vercel.app/api?username=ivanbayonaperez-cpu&show_icons=true&theme=default" />
</p>


---

## 💼 Conéctanos

* **LinkedIn:** [linkedin.com/in/ivan-bayona-perez](https://www.linkedin.com/in/ivan-bayona-perez)
* **Portafolio:** [Notion — Ivan Bayona Portafolio](https://ivanbayona.notion.site)
* **Correo electrónico:** ivan.bayonaperez@gmail.com

💬 **Abierto a roles de Data Analyst (remoto/híbrido)** — conectemos si buscas convertir datos complejos en decisiones de negocio.
