# 📑 Comparación de la masa corporal entre especies de pingüinos
**Autor:** [Tu Nombre]  
**Fecha:** 24 de febrero de 2026

---

## 1. Introducción y Objetivo
Breve contexto sobre la base de datos de Pingüinos de Palmer y la importancia de estudiar su masa corporal para entender la salud del ecosistema antártico.

> **Objetivo:** Determinar si existen diferencias significativas en la **masa corporal (g)** según la **especie** del pingüino.

### Hipótesis del Análisis
* **$H_0$:** No existen diferencias significativas entre los grupos ($\mu_1 = \mu_2 = \mu_3$).
* **$H_1$:** Existen diferencias significativas en al menos uno de los grupos.

---

## 2. Metodología y Preparación de Datos
Para garantizar la calidad de la inferencia, se realizaron los siguientes pasos previos:

* **Limpieza de Datos:** Se realizó una auditoría de la base de datos, identificando y gestionando **[X] valores perdidos**.
* **Visualización Inicial:** Se emplearon **histogramas y boxplots** para identificar la distribución y la presencia de *outliers*.

### Resumen Descriptivo General
| Variable | Media | Desv. Estándar | N |
| :--- | :--- | :--- | :--- |
| Masa Corporal (g) | [Valor] | [Valor] | [Valor] |

---

## 3. Validación de Supuestos
Esta etapa justifica la elección de la prueba estadística final.

### A. Prueba de Normalidad (Shapiro-Wilk)
Se segmentó la base de datos por especie para evaluar la distribución interna de cada grupo.
* **Grupos [A y B]:** $p > 0.05$ (Se asume normalidad).
* **Grupo [C]:** $p < 0.05$ (No presenta normalidad).

### B. Homocedasticidad (Prueba de Levene)
* **Resultado:** $p = [Valor]$.
* **Interpretación:** [Existe/No existe] igualdad de varianzas entre los grupos.

> **Selección de Prueba:** Dado el [incumplimiento de normalidad / varianza], se procedió a realizar una prueba **[Paramétrica/No Paramétrica]**.

---

## 4. Resultados e Interpretación
A continuación se detallan los hallazgos tras ejecutar el contraste de hipótesis en SPSS.

* **Estadístico de Contraste:** $[t, F \text{ o } H] = [Valor]$
* **p-valor (Sig.):** $[Valor]$
* **Decisión:** Al ser el $p < 0.05$, se **rechaza** la Hipótesis Nula ($H_0$).

### Análisis Post-Hoc (Comparaciones Múltiples)
Las comparaciones múltiples (Tukey/Bonferroni) indican que la diferencia principal radica entre el grupo **[Nombre]** y el grupo **[Nombre]**.

---

## 5. Conclusiones y Recomendaciones
1. **Conclusión:** Se confirma que la especie influye de manera significativa en el peso de los individuos.
2. **Recomendación:** Se sugiere enfocar esfuerzos de monitoreo en [Especie], dado su comportamiento observado.Analisis_Satisfaccion/README.md
