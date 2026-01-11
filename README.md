<div align="center">

# 📊 El Algoritmo del Marketing Digital
### Análisis Estadístico Avanzado para la Optimización de Inversión Publicitaria

![R](https://img.shields.io/badge/Language-R-276DC3?style=for-the-badge&logo=r)
![Statistics](https://img.shields.io/badge/Focus-Statistical_Inference-success?style=for-the-badge)
![Data Viz](https://img.shields.io/badge/Library-ggplot2-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

<br>

<p align="center">
  <b>¿Intuición o Certeza?</b> Este proyecto transforma la toma de decisiones en marketing digital utilizando 
  <b>Simulación de Monte Carlo</b> y <b>Modelado Predictivo</b> para maximizar el ROI.
</p>

[![](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/maría-luisa-ros-bolea-400780160)
[![](https://img.shields.io/badge/Portfolio-Visit_Site-228B22?style=flat-square&logo=github&logoColor=white)](https://malurosbolea-ux.github.io/digital-strategy-portfolio)
[![](https://img.shields.io/badge/Email-Contact_Me-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:malurosbolea@gmail.com)

</div>

---

## 🧐 Sobre el Proyecto

En la industria de la comunicación digital, a menudo se invierten miles de euros basándose en "sensaciones". [cite_start]Como profesional que aspira a liderar con datos, he desarrollado este estudio para responder científicamente a la pregunta: **¿Dónde es más rentable invertir el próximo euro?**[cite: 19, 23].

Este repositorio contiene el código y el análisis completo para demostrar matemáticamente qué plataformas (Instagram, TikTok o LinkedIn) ofrecen el mejor retorno de inversión.

## ⚙️ Metodología e Ingeniería de Datos

Para asegurar el **rigor científico** y evitar la "suciedad" de los datasets públicos, generé mi propio conjunto de datos:

* [cite_start]**Simulación de Monte Carlo:** Generación de 1.000 campañas sintéticas[cite: 52].
* [cite_start]**Parámetros Reales:** Variables basadas en métricas de mercado 2025 (CPC, CTR y tasas de viralidad)[cite: 31, 279].
* [cite_start]**Datos Limpios:** 0 valores nulos y control total de distribuciones (Normal, Poisson)[cite: 34].

## 📈 Hallazgos Clave (Insights)

| Métrica | Resultado | Interpretación Estratégica |
| :--- | :--- | :--- |
| **Consistencia** | `LinkedIn` | [cite_start]El canal más seguro y con mayor rendimiento medio[cite: 103]. |
| **Viralidad** | `TikTok` | Alta volatilidad. [cite_start]Muestra *outliers* extremos pero bajo rendimiento medio[cite: 106]. |
| **ROI Marginal** | `Pendiente Alta` | En LinkedIn, la inversión escala linealmente con las ventas. [cite_start]En TikTok, la curva es plana[cite: 119, 121]. |

## 🧠 Análisis Estadístico

Este proyecto va más allá de la descripción visual, aplicando inferencia estadística rigurosa:

### 1. ANOVA de un Factor
* **Hipótesis:** ¿Son iguales las medias de ventas entre plataformas?
* [cite_start]**Resultado:** `p-valor < 2e-16`[cite: 143].
* **Conclusión:** Rechazo rotundo de la hipótesis nula. Las diferencias de rendimiento son estadísticamente significativas.

### 2. Regresión Lineal Simple
* **Modelo:** $Ventas = \beta_0 + \beta_1 \cdot Presupuesto$
* [cite_start]**Precisión:** `R-squared ≈ 0.75`[cite: 164].
* **Impacto:** El modelo explica el 75% de la variabilidad, permitiendo predicciones de ventas con alto grado de confianza.

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** R
* **Librerías:** `tidyverse`, `ggplot2`, `knitr`
* **Entorno:** RStudio

---

<div align="center">
  
**¿Te interesa ver el código completo?** Revisa el archivo `.Rmd` en este repositorio para ver el paso a paso del análisis.

Made with 💚 by **María Luisa Ros Bolea**

</div>
