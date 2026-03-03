# Analísis dataset "Palmer Penguins"
**Autor:** Amilcar Ramírez Alvarado
**Fecha:** 24 de febrero de 2026

---

## Introducción 
El presente análisis busca determinar si existen diferencias morfométricas significativas entre las tres especies de pingüinos (Adeliae, Gentoo y Chinstrap) que habitan el Archipiélago de Palmer. Para ello, se evaluarán cuatro rasgos físicos clave: **masa corporal, longitud de las aletas, y las dimensiones del culmen (largo y ancho)**. A través de una serie de análisis de varianza (ANOVA), buscaremos responder si estas especies han desarrollado adaptaciones físicas distintas. 
### Preguntas de investigación
1. ¿Es diferente la masa corporal entre las especies?
2. ¿Existe diferencia en el largo de las aletas de las especies?
3. ¿El largo del pico presenta diferencias entre las especies?
4. ¿El ancho del pico tiene alguna diferencia entre las especies?

## Validacion de supuestos
Antes de proceder con la comparación de medias, se evaluó el supuesto de normalidad para cada variable segmentada por especie mediante la prueba de Shapiro-Wilk. Este paso es fundamental para decidir entre el uso de pruebas paramétricas (ANOVA) o no paramétricas (Kruskal-Wallis).

### Prueba de normalidad body_mass_g por Especie
| Especie | Estadistico | gl | Sig. |
| :--- | :--- | :--- | :--- |
| Adelie | 0.981 | 151 | 0.032 |
| Gentoo | 0.986 | 123 | 0.234 |
| Chinstrap | 0.984 | 68 | 0.561 |

Se observó que la variable body_mass_g presenta una desviación significativa de la normalidad solo en la especie Adelie ($W = 0.981, p = 0.032$).

### Prueba de normalidad flipper_length_mm por Especie
| Especie | Estadistico | gl | Sig. |
| :--- | :--- | :--- | :--- |
| Adelie | 0.993 | 151 | 0.720 |
| Gentoo | 0.962 | 123 | 0.002 |
| Chinstrap | 0.989 | 68 | 0.811 |

### Prueba de normalidad bill_depth_mm por Especie
| Especie | Estadistico | gl | Sig. |
| :--- | :--- | :--- | :--- |
| Adelie | 0.985 | 151 | 0.092 |
| Gentoo | 0.976 | 123 | 0.028 |
| Chinstrap | 0.973 | 68 | 0.142 |

### Prueba de normalidad bill_lenth_mm por Especie
| Especie | Estadistico | gl | Sig. |
| :--- | :--- | :--- | :--- |
| Adelie | 0.993 | 151 | 0.717 |
| Gentoo | 0.973 | 123 | 0.013 |
| Chinstrap | 0.975 | 68 | 0.194|

En las variables flipper_length_mm, bill_depth_mm y bill_length_mm, la especie Gentoo mostró valores de p inferiores a 0.05, lo que sugiere una distribución no normal en este grupo específico.

## ¿Es diferente la masa corporal entre las especies?
Para poder responer a esta pregunta se plantean las siguientes hipotesis
* **$H_0$:** No existe diferencia significativa en la masa corporal promedio entre las especies de pinguinos ($\mu_1 = \mu_2 = \mu_3$).

* **$H_1$:** Al menos una de especies presenta una masa corporal significativamente distinta a las demas.

### Anova (masa corporal)
Tras la ejecución del analisis de varianzas para la variable **body_mass_g** por especie, se obtuvieron los siguientes estadisticos:


---

## 2. Metodología y Preparación de Datos
Para garantizar la calidad de la inferencia, se realizaron los siguientes pasos previos:

* **Limpieza de Datos:** Se realizó una revisión de la base de datos, identificando y gestionando **[11] valores perdidos**.
* **Visualización Inicial:** Se emplearon **histogramas y boxplots** para identificar la distribución y la presencia de *outliers*.

### Resumen Descriptivo General
| Variable | Media | Desv. Estándar | N |
| :--- | :--- | :--- | :--- |
| Masa Corporal (g) | $[Valor]$ | [$Valor]$ | $[Valor]$ |

---


