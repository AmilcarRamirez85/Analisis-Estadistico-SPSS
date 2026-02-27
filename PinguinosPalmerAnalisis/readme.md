# 📑 ¿Existen diferencias estadísticamente significativas en la masa corporal promedio entre las especies de pingüinos?
**Autor:** Amilcar Ramírez Alvarado
**Fecha:** 24 de febrero de 2026

---

## 1. Introducción y Objetivo
Para responder a la pregunta de investigación se utilizará el dataset Palmer Penguins, el cual es de acceso abierto bajo licencia Creative Commons. Este conjunto de datos contiene información recolectada en el archipiélago Palmer, conformado por tres islas, e incluye registros morfológicos de 344 pingüinos pertenecientes a tres especies.

> **Objetivo:** Determinar si existen diferencias estadisticamente significativas en la **masa corporal (g)** según la **especie** de pingüinos.

### Hipótesis del Análisis
* **$H_0$:** Las medias poblacionales de masa corporal son iguales entre las especies de pingüinos.
* **$H_1$:** Al menos una de las medias poblacionales de masa corporal difiere entre las especies.

---

## 2. Metodología y Preparación de Datos
Para garantizar la calidad de la inferencia, se realizaron los siguientes pasos previos:

* **Limpieza de Datos:** Se realizó una revisión de la base de datos, identificando y gestionando **[11] valores perdidos**.
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
