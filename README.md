# SVM-y-multiple-testing-


*OBJETIVO*

Aplicar pruebas de hipótesis univariadas con control por pruebas múltiples y comparar el desempeño de SVM con distintos kernels sobre el dataset de microarreglos (Khan). La actividad cubre:

1. Importación, limpieza mínima y revisión de datos

2. Comparación 2 vs 4 por gen (Δmedias y t-tests) con Bonferroni, Holm, BH/FDR

3. ANOVA entre 4 clases por gen

4. Entrenamiento y evaluación de SVM (lineal, polinomial g=3, RBF)

5. Visualizaciones de apoyo y guardado de resultados


DATOS

Archivo: A3.1 Khan.csv

Muestras: 83

Genes (variables): ≈ 2308

Etiqueta: columna y con clases {1, 2, 3, 4}

Faltantes: 0


Mapeo de celdas

- Celda 1: Importación, detección de y, forma del dataset, faltantes (0).

- Celdas 2–3: Δmedias (clase 2 vs 4) + gráfica Top-10 por |Δmedia|.

- Celda 4: Conteo de genes significativos por ajuste múltiple (Bonferroni/Holm/BH).

- Celda 5: Histograma de p-values (t-test 2 vs 4).

- Celdas 6–8: t-tests con Bonferroni, Holm y Benjamini–Hochberg (FDR) (tablas con p_adj y reject).

- Celdas 9–10: ANOVA (Top-10 por F) + gráfica de barras.

- Celdas 11–12: SVM (lineal, poly-3, RBF): métricas (Accuracy, F1-macro) y (opcional) PCA 2D.

- Celda 13: Guardado de resultados en a31_outputs/.

La actividad va de 3 archivos:

[reporte html](A3.1_652911.html)

[reporte ipynb](A3.1_652911.ipynb)

[reporte A3.1_Khan.cvs](A3.1_Khan.csv)

