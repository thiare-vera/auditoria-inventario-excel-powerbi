# Auditoría de Inventario, Demanda y Control de Reposición (Excel + Power BI)

## 🎯 Objetivo del Proyecto
Evaluar el consumo, valorización presupuestaria y riesgo de quiebre de stock de 15 líneas de insumos clínicos y equipamiento distribuidos en tres sedes operativas (Sur, Centro y Norte), integrando análisis en Excel, visualización interactiva en Power BI Desktop, informe técnico y presentación ejecutiva.

## 🛠️ Herramientas Utilizadas
* **Microsoft Excel / Google Sheets:** Cálculo de gasto valorizado, reglas condicionales de alerta (`SI`), tablas dinámicas y gráficos comparativos.
* **Power BI Desktop (`.pbix`):** Dashboard interactivo con segmentador dinámico por sede, tarjeta KPI, gasto por categoría y distribución de alertas.
* **Presentación Ejecutiva & Informe Técnico (`.pptx` / `.pdf`):** Síntesis gerencial con métricas de cobertura y plan de reposición priorizado.

## 💡 Principales Hallazgos
* **Riesgo de Abastecimiento:** El **66,7% de los registros (`10` de `15`)** se encuentra en estado crítico (`≤15` unidades), incluyendo el **100% del equipamiento** auditado.
* **Concentración Presupuestaria:** El gasto total ascendió a **$1.717.000 CLP**, liderado por la categoría **Insumos ($1.021.600 CLP — 59,5%)** y la sede **Sur ($726.350 CLP — 42,3%)**.
* **Optimización de Regla de Control:** Se detectó que el umbral fijo de 15 unidades subestima el riesgo en artículos de alta rotación (ej. Paracetamol con stock 20 frente a 150 salidas), proponiendo migrar hacia indicadores de **cobertura (`Stock ÷ Salidas`)**.
