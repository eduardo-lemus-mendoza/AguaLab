# AguaLab: Sistema de Inteligencia Hídrica y Riesgo para México (2014-2025)

### Arquitectura de Big Data Geoespacial para la Crisis Hídrica y Nearshoring

**Arquitecto:** Eduardo Lemus Mendoza
**Estado:** Producción (Datos Históricos 10 años)
**Stack:** Python, Google Earth Engine (GEE) API, JavaScript, HTML5

## 📋 Resumen Ejecutivo
En el contexto de la crisis hídrica de México y el auge del **Nearshoring**, la disponibilidad de agua es el dato más crítico para la inversión industrial. AguaLab no es solo un mapa; es un motor de auditoría histórica que procesó **2.5 millones de operaciones geoespaciales** en 6 horas para determinar la "Verdad Terrestre" de 11,000 cuerpos de agua.

Este sistema elimina la incertidumbre de los datos estáticos de INEGI, ofreciendo una serie de tiempo dinámica de 10 años para evaluar la resiliencia hídrica real.

## 🛠️ Arquitectura de la Solución (Proof of Work)

El valor de este proyecto reside en la orquestación masiva de datos satelitales (Landsat 8) mediante algoritmos serverless:

1.  **Ingesta de Datos:** Pipeline automatizado en **Python** conectado a la API de GEE.
2.  **Filtrado Topológico:** Algoritmo de limpieza geométrica para descartar falsos positivos y optimizar el rendimiento de renderizado.
3.  **Cálculo Masivo (High-Throughput):** * **Input:** 11,000 AOIs (Áreas de Interés).
    * **Proceso:** Cálculo de NDWI (Normalized Difference Water Index) con enmascaramiento de nubes (<10%).
    * **Volumen:** 2.5 Millones de geoprocesos ejecutados en < 6 horas.
4.  **Frontend:** Visualización ligera optimizada para decisores (no técnicos), enfocada en la tendencia histórica.

## 💡 Casos de Uso
* **Selección de Sitios Industriales:** Validación de disponibilidad de agua histórica para nuevos parques industriales.
* **Auditoría Ambiental:** Detección de desecación ilegal o estrés hídrico no reportado.
* **Seguros Agrícolas:** Verificación histórica de cuerpos de agua para ajuste de primas.

## 🔗 Contacto y Consultoría
Este proyecto demuestra la capacidad de escalar análisis geoespaciales a nivel nacional.
* **Perfil Profesional:** [Eduardo Lemus Mendoza en LinkedIn](https://www.linkedin.com/in/eduardo-lemus-mendoza)
* **Más Proyectos:** [Portafolio en Udemy](https://www.udemy.com/user/eduardo-lemus-mendoza/)
