# Proyecto: 
Diferencias Biométricas entre Especies
## Descripción: 
Análisis estadístico para determinar si existen diferencias significativas en la masa corporal de los pingüinos según su especie.

## 1. Fase de Exploración (Descriptiva)Limpieza: 
Se verificaron valores perdidos y se eliminaron 2 filas incompletas.

## Estadísticos: 
La masa promedio general es de 4201g con una desviación estándar de 801g.

## Visualización: 
Se generó un histograma para observar la distribución inicial.
## 2. Verificación de Supuestos (El Corazón del Análisis)
Para decidir la prueba inferencial, apliqué los siguientes filtros:
Normalidad: Se utilizó la prueba de Shapiro-Wilk ($n < 50$ por grupo). El resultado fue $p = 0.021$, por lo cual se rechaza la hipótesis de normalidad.
Homocedasticidad: La prueba de Levene mostró un $p = 0.45$, indicando varianzas homogéneas.
Decisión: Debido a la falta de normalidad, se optó por una prueba No Paramétrica.

## 3. Fase Inferencial (Resultados)
Prueba utilizada: Kruskal-Wallis (para comparar 3 grupos independientes).Resultado (Sig.): $p < 0.001$.
Interpretación: Existen diferencias estadísticamente significativas en la masa corporal entre al menos dos especies de pingüinos.
## 4. Conclusión
Se evidencia que la especie Gentoo tiene una masa corporal significativamente mayor que las especies Adelie y Chinstrap.
