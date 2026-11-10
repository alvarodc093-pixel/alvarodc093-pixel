<h1 align="center">Álvaro Domingo Cordón</h1>

<p align="center"><b>Data Analyst Junior · SQL · Python · Power BI</b></p>

<p align="center">
  Convierto datos en decisiones de negocio con SQL, Power BI y estadística: análisis de e-commerce, dashboards de ventas, A/B tests y segmentación de clientes, siempre con datos reales y tests.
</p>

<p align="center">
  <a href="https://alvarodc093-pixel.github.io/alvarodc093.github.io/"><img src="https://img.shields.io/badge/Portafolio-1a56db?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portafolio"></a>
  <a href="https://www.linkedin.com/in/alvaro-domingo/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://alvarodc093-pixel.github.io/alvarodc093.github.io/CV_Alvaro_Domingo.pdf"><img src="https://img.shields.io/badge/CV_(ES)-444444?style=for-the-badge&logo=readdotcv&logoColor=white" alt="CV en español"></a>
  <a href="https://alvarodc093-pixel.github.io/alvarodc093.github.io/CV_Alvaro_Domingo_EN.pdf"><img src="https://img.shields.io/badge/CV_(EN)-444444?style=for-the-badge&logo=readdotcv&logoColor=white" alt="CV in English"></a>
  <a href="mailto:alvarodc093@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p align="center">
  <b>Buscando mi primer puesto como Data Analyst</b> · Remoto o híbrido · Cádiz / Sevilla (España) · Español e inglés
</p>

---

## Sobre mí

Data Analyst formado en el bootcamp de Data Analyst e IA de **Upgrade Hub**. Vengo del sector dental (higiene bucodental, laboratorio y diseño CAD/CAM), donde aprendí a trabajar con precisión, control de calidad y trato con el cliente. Hoy aplico ese rigor a los datos: cada proyecto que publico usa datos reales, documenta sus limitaciones y se puede probar en vivo.

## Qué aporto

- **SQL:** CTEs, funciones de ventana (`LAG`, `RANK`, `NTILE`), análisis de cohortes y controles de calidad de datos, en DuckDB y SQLite.
- **Python para análisis:** Pandas y NumPy para limpieza, transformación y análisis exploratorio (EDA).
- **Business Intelligence:** Power BI con modelo en estrella, DAX (año anterior, acumulados, objetivos) y Power Query, con las cifras validadas contra SQL.
- **Estadística y experimentación:** A/B testing con intervalos de confianza, bootstrap y enfoque bayesiano; segmentación RFM y valor de vida del cliente (CLV).
- **Visualización y storytelling:** dashboards interactivos en Streamlit y gráficos que responden a una pregunta de negocio concreta.
- **Machine learning aplicado:** modelos de clasificación y de previsión con scikit-learn, siempre comparados con un baseline y validados por fecha.
- **Ingeniería analítica (dbt):** modelos por capas (staging → marts), modelo en estrella, cargas incrementales, contratos de datos, tests y documentación con linaje.
- **Pipelines de datos (ETL):** ingesta desde APIs REST con caché y reintentos, y actualizaciones automáticas con GitHub Actions.
- **Buenas prácticas:** Git, tests con pytest, integración continua con GitHub Actions, documentación clara y resultados reproducibles.

## Proyectos destacados

### Análisis de negocio (SQL, Power BI y estadística)

| Proyecto | Problema de negocio y resultado | |
|---|---|---|
| **[Olist en SQL](https://github.com/alvarodc093-pixel/Olist-SQL-Analysis)**<br><sub>SQL · DuckDB · window functions</sub> | ¿De dónde sale el crecimiento de un e-commerce y qué lo frena? 11 consultas SQL sobre 97.905 pedidos reales (cohortes, recompra, Pareto, logística): solo el **3 %** de los clientes repite y un retraso de más de una semana hunde la nota de 4,3 a **1,7**. | [Hallazgos](https://github.com/alvarodc093-pixel/Olist-SQL-Analysis#hallazgos-principales) |
| **[Contoso Retail en Power BI](https://github.com/alvarodc093-pixel/Contoso-Retail-PowerBI)**<br><sub>Power BI · DAX · Power Query · SQL</sub> | ¿Cómo van las ventas de una cadena de tiendas frente al año anterior y al presupuesto? Informe de 5 páginas con 28 medidas DAX sobre 224.000 ventas: 2025 cae un **7,5 %**, se queda en el **85,7 %** del objetivo y el ticket medio baja un 35 % desde 2018. | [Capturas](https://github.com/alvarodc093-pixel/Contoso-Retail-PowerBI#las-5-páginas) |
| **[A/B test de marketing](https://github.com/alvarodc093-pixel/Marketing-AB-Test)**<br><sub>Python · SciPy · statsmodels · estadística</sub> | ¿Funcionan los anuncios? Experimento con 588.101 usuarios: +43 % de conversión (IC 95 % +30 % a +58 %), confirmado con bootstrap, enfoque bayesiano y regresión logística. Solo el **30 %** de las compras se deben a los anuncios y el 72 % de los usuarios no responde a la campaña. | [Análisis](https://github.com/alvarodc093-pixel/Marketing-AB-Test/blob/main/analisis.ipynb) |
| **[Segmentación RFM y CLV](https://github.com/alvarodc093-pixel/Customer-Segmentation-RFM)**<br><sub>Python · Pandas · SciPy · modelos de CLV</sub> | ¿A qué clientes cuidar, recuperar o dejar? 10 segmentos RFM sobre 5.852 clientes reales y valor de vida con BG/NBD + Gamma-Gamma programados desde cero y validados en 6 meses no vistos (compras con un **2 %** de error). Lista priorizada de 713 clientes en riesgo. | [Análisis](https://github.com/alvarodc093-pixel/Customer-Segmentation-RFM/blob/main/analisis.ipynb) |
| **[Citi Bike con dbt](https://github.com/alvarodc093-pixel/CitiBike-dbt-Analytics)**<br><sub>dbt · DuckDB · SQL · GitHub Actions</sub> | ¿Dónde se acumulan las bicis de un sistema de bici compartida y qué frena la demanda? Pipeline dbt de 14 modelos sobre 972.000 viajes reales con hecho incremental, contrato de datos y 61 tests: 9 estaciones acumulan **~240 bicis** cada mañana laborable y la lluvia fuerte resta un **35 %** de los viajes. | [Docs y linaje](https://alvarodc093-pixel.github.io/CitiBike-dbt-Analytics/) |

### Machine learning y productos de datos

| Proyecto | Problema de negocio y resultado | |
|---|---|---|
| **[Steam Launch Radar](https://github.com/alvarodc093-pixel/steam-launch-radar)**<br><sub>Python · scikit-learn · Next.js</sub> | ¿Va bien el lanzamiento de un juego? Estima las reseñas a 30 días con las de los primeros días, a partir de 3.019 lanzamientos reales y modelos validados por fecha. | [Demo](https://steam-launch-radar.vercel.app) |
| **[Solar España](https://github.com/alvarodc093-pixel/Energia-Solar)**<br><sub>Python · scikit-learn · Streamlit · GitHub Actions</sub> | ¿Cuánta energía solar producirá España mañana? Previsión con datos de REE y Open-Meteo que acierta el **84,5 %**, mejora a los 3 baselines y se actualiza sola cada semana. | [Demo](https://solar-espana.vercel.app) |
| **[ChurnGuard](https://github.com/alvarodc093-pixel/Churnguard-Player-Retention)**<br><sub>Python · scikit-learn · Pandas</sub> | ¿Qué jugadores van a abandonar un juego free-to-play? Modelo de churn entrenado con 41.560 reseñas de Steam (**ROC-AUC 0,93**) que propone una acción para cada jugador. | [Demo](https://no-pain-no-game.vercel.app) |

**Más proyectos con demo:** [GameScope](https://github.com/alvarodc093-pixel/GameScope) (comparador de competidores, 61 tests) · [Órbita](https://github.com/alvarodc093-pixel/Orbita) (8.120 lanzamientos espaciales, ingesta semanal) · [DataJobs Radar](https://github.com/alvarodc093-pixel/Datajob) (1.202 ofertas de Data Analyst) · [Twitch Game Pulse](https://github.com/alvarodc093-pixel/Twitch-Audience-Analytics) (audiencia diaria en Twitch). Todo está en el [portafolio](https://alvarodc093-pixel.github.io/alvarodc093.github.io/).

## Herramientas

| Área | Herramientas |
|---|---|
| Análisis y programación | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white) |
| Bases de datos | ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Azure SQL](https://img.shields.io/badge/Azure_SQL-0078D4?style=flat-square&logo=microsoftazure&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) |
| Business Intelligence | ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat-square) ![Power Query](https://img.shields.io/badge/Power_Query-F2C811?style=flat-square) ![Microsoft Fabric](https://img.shields.io/badge/Fabric-0078D4?style=flat-square&logo=microsoft&logoColor=white) |
| Visualización y apps | ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square) ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square) |
| Estadística | ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![statsmodels](https://img.shields.io/badge/statsmodels-4B8BBE?style=flat-square) ![A/B testing](https://img.shields.io/badge/A%2FB_testing-5A5A5A?style=flat-square) |
| Machine learning e IA | ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![RAG](https://img.shields.io/badge/RAG_y_LLMs-412991?style=flat-square) ![ChromaDB](https://img.shields.io/badge/ChromaDB-5A3FC0?style=flat-square) |
| Automatización y herramientas | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![APIs REST](https://img.shields.io/badge/APIs_REST-5A5A5A?style=flat-square) ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white) |

## Formación

- **Bootcamp de Data Analyst e IA** · Upgrade Hub · mayo–octubre de 2026
- **Técnico Superior en Prótesis Dentales** · Escuela Esprohident · 2018–2020
- **Técnico Superior en Higiene Bucodental** · Cesur · 2013–2014

## Qué busco

Mi primer puesto como **Data Analyst Junior**, en remoto o híbrido desde España, preferiblemente en tecnología, e-commerce o videojuegos.

## In English

Junior Data Analyst (SQL · Python · Power BI) open to remote roles. Highlights: [an e-commerce analysis in SQL](https://github.com/alvarodc093-pixel/Olist-SQL-Analysis), [a Power BI sales dashboard with 28 DAX measures](https://github.com/alvarodc093-pixel/Contoso-Retail-PowerBI), [an A/B test of 588k users](https://github.com/alvarodc093-pixel/Marketing-AB-Test) and [RFM segmentation with a lifetime-value model](https://github.com/alvarodc093-pixel/Customer-Segmentation-RFM) and [a dbt pipeline on 972k bike-share trips](https://github.com/alvarodc093-pixel/CitiBike-dbt-Analytics). These five use real data, have tests and CI, and end with an English summary. [CV in English](https://alvarodc093-pixel.github.io/alvarodc093.github.io/CV_Alvaro_Domingo_EN.pdf).

<p align="center">
  <a href="mailto:alvarodc093@gmail.com"><b>alvarodc093@gmail.com</b></a> · <a href="https://www.linkedin.com/in/alvaro-domingo/"><b>linkedin.com/in/alvaro-domingo</b></a>
</p>
