# Experimento A/B – Validando Hipótesis de Negocio con Pruebas Estadísticas — Proyecto Sprint 9

Este repositorio contiene el análisis estadístico desarrollado para el equipo de Marketing Digital de una empresa de ecommerce, con el objetivo de evaluar un experimento A/B realizado en la página de inicio (landing page) y respaldar una **decisión de negocio basada en datos**.

El dataset `landing_experiment.csv` incluye **40,000 registros** de usuarios expuestos a dos versiones de la página de inicio (A y B), con variables de comportamiento, segmentación geográfica, canal de tráfico, tipo de usuario, conversión y gasto, correspondientes al período de experimentación 2026.

> ⚠️ Este es un análisis experimental controlado (A/B). Los resultados estadísticos indican asociación y diferencias significativas, pero deben complementarse con contexto de negocio antes de escalar decisiones.

---

## 📂 Contenido del repositorio

- `notebooks/S9_Version_Student_Proyecto_Landing_Experiment_F.ipynb` → Notebook principal con carga y validación de datos, pruebas estadísticas, visualizaciones, interpretación de hallazgos e insights ejecutivos para stakeholders.

---

## ▶️ Cómo abrir el notebook en Google Colab

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

O accede directamente desde el botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10FdpmZ6mkD2Rxktkx756XdgIblfBNGJx?usp=sharing)

---

## 📘 Cómo reproducir el análisis

1. Abre `notebooks/S9_Version_Student_Proyecto_Landing_Experiment_F.ipynb`
2. Conecta el entorno de ejecución en Colab o Jupyter
3. Asegúrate de que el dataset `landing_experiment.csv` esté disponible en la ruta `/datasets/` o actualiza la ruta de carga en la celda correspondiente
4. Ejecuta las celdas en orden siguiendo el flujo de 7 pasos documentado en el notebook

---

## 🧠 Objetivo del análisis

Responder las preguntas de negocio:

- ¿Existe una diferencia significativa en el **gasto promedio** por usuario convertido entre ambas versiones?
- ¿Qué versión de la página (A o B) genera mayor **tasa de conversión**?
- ¿La conversión depende de la **fuente de tráfico**?
- ¿El **tipo de usuario** (nuevo o recurrente) influye en la conversión?
- ¿Qué hallazgos permiten **optimizar la estrategia de marketing** y el diseño de la landing page?

Para ello, el proyecto construye un análisis estadístico estructurado que combina pruebas de hipótesis, segmentación por variables categóricas y visualizaciones, con el fin de generar conclusiones claras y recomendaciones accionables para el equipo de Marketing Digital.

---

## 🎯 Objetivos de aprendizaje

1. Explorar y validar un dataset proveniente de un experimento A/B real, verificando calidad, completitud y consistencia de los datos.
2. Comparar métricas de negocio mediante **pruebas estadísticas apropiadas** — Prueba t de Student, Z-test de proporciones y Chi-cuadrado de independencia — seleccionando el método adecuado según el tipo de variable.
3. Verificar supuestos estadísticos e interpretar correctamente el **p-value** desde una perspectiva de negocio.
4. Analizar el comportamiento de conversión por segmentos: **fuente de tráfico** y **tipo de usuario**.
5. Visualizar resultados mediante gráficos de conteo absoluto y proporciones para respaldar conclusiones.
6. Traducir hallazgos estadísticos en **insights ejecutivos y recomendaciones accionables** para stakeholders no técnicos.

---

## 🛠️ Herramientas utilizadas

- Python
- `pandas` · `numpy` · `matplotlib` · `seaborn` · `scipy`
- Jupyter Notebook / Google Colab

---

## 🔄 Flujo del proyecto

| Paso | Acción | Resultado para el negocio |
|------|--------|--------------------------|
| 1 | Cargar y validar los datos | Confianza en la calidad del experimento |
| 2 | Comparar gasto promedio (A vs B) | Identificar qué página genera más valor económico |
| 3 | Comparar tasa de conversión (A vs B) | Identificar la página más efectiva |
| 4 | Analizar fuente de tráfico y conversión | Optimizar inversión en canales |
| 5 | Analizar tipo de usuario y conversión | Evaluar si es necesario segmentar usuarios |
| 6 | Visualizar resultados | Respaldo visual de conclusiones |
| 7 | Insight ejecutivo para stakeholders | Decisión clara y recomendaciones accionables |

---

## 👤 Autor

Juan Castelblanco — Analista de Datos  
Sprint 9 – Validando Hipótesis de Negocio con Pruebas Estadísticas


## 📝 Licencia

Este proyecto es de uso educativo y forma parte del programa de análisis de datos.
