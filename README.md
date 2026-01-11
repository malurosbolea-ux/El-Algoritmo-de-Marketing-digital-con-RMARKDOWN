# Resumen Ejecutivo: El Algoritmo del Marketing Digital

**Autora:** María Luisa Ros Bolea  
**Enfoque:** Análisis Estadístico Avanzado para la Optimización de Inversión Publicitaria

---

### 1. Motivación: Del "Olfato" al Dato
En el sector de la comunicación digital, demasiadas decisiones se toman basándose en la intuición ("creo que esto funcionará"). [cite_start]Mi objetivo con este proyecto es profesionalizar este proceso, utilizando la estadística para responder con certeza matemática a una pregunta de negocio crítica: **¿Dónde debo invertir el próximo euro para maximizar el retorno?**[cite: 19, 23].

### 2. Metodología Científica: Simulación de Monte Carlo
[cite_start]Para garantizar la robustez del estudio y evitar los problemas de calidad de los datos públicos, he generado mi propio dataset mediante **Simulación de Monte Carlo**[cite: 30, 50].
* [cite_start]**Diseño:** 1.000 campañas simuladas bajo parámetros controlados[cite: 52].
* [cite_start]**Variables:** He replicado el comportamiento real de plataformas como **Instagram, TikTok y LinkedIn** basándome en métricas de la industria (CTR, CPC)[cite: 32, 54].
* [cite_start]**Reproducibilidad:** El uso de una semilla (`set.seed(2025)`) asegura que este estudio es científicamente reproducible[cite: 35].

### 3. Hallazgos del Análisis Exploratorio (EDA)
[cite_start]El análisis visual revela tres perfiles de comportamiento claros[cite: 103, 106, 176]:
* **LinkedIn (Eficiencia):** Es el canal con mayor rendimiento medio y menor riesgo.
* **TikTok (Volatilidad):** Muestra una gran dispersión. Su éxito depende de "outliers" (viralidad) y no garantiza ventas directas de forma lineal.
* **Instagram (Estabilidad):** Funciona como un canal intermedio de cobertura.

### 4. Evidencia Estadística (Inferencia)
He validado estas observaciones mediante contrastes de hipótesis rigurosos:
* **ANOVA:** Con un **p-valor < 2e-16**, rechazo la hipótesis nula rotundamente. [cite_start]Las diferencias de rendimiento entre plataformas son estadísticamente significativas, no fruto del azar[cite: 143, 144].
* [cite_start]**Regresión Lineal:** He construido un modelo capaz de explicar el **75% de la variabilidad** de las ventas ($R^2 \approx 0.75$), lo que me permite predecir resultados futuros con alta precisión[cite: 164].

### 5. Conclusión Estratégica
Los datos dictan una reasignación del presupuesto. [cite_start]La estrategia óptima para maximizar el ROI es priorizar **LinkedIn** (mayor pendiente de crecimiento) y utilizar **TikTok** únicamente para objetivos de *branding*, ya que el presupuesto no escala linealmente con las ventas en esta última plataforma[cite: 172, 175].

---
