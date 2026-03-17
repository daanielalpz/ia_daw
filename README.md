# ia_daw
# Práctica IA (RA4 · b+c) — Big Data, análisis, rentabilidad y valoración IA

## 1) Caso y objetivo de negocio
- Empresa/sector (real o ficticia): Comercio online de moda (similar a Zara o ASOS)
- Problema a resolver: Predicción de demanda de productos para optimizar inventario y reducir roturas de stock o exceso de stock.
- Objetivo de negocio (rentabilidad): Reducir costes de almacenamiento y aumentar ventas evitando faltantes.

## 2) Big Data: recogida masiva de datos
Describe por qué es Big Data (volumen, velocidad, variedad).
- Fuente 1: Historial de ventas online (volumen: millones de transacciones anuales)
- Fuente 2: Datos de navegación y clics de usuarios en la web/app (velocidad: flujo en tiempo real)
- Fuente 3: Datos de proveedores y logística (variedad: CSV, APIs, ERP)
- Volumen/velocidad (estimación): ~5 TB mensuales, actualización diaria y en tiempo real de clicks
- Formatos (texto, eventos, series temporales, imágenes, etc.): CSV, JSON, logs de eventos, series temporales de ventas

## 3) Tratamiento/análisis: pipeline de datos
Explica el flujo de forma ordenada:
- Ingesta (captura/eventos): Captura de transacciones y clicks mediante APIs y logs en tiempo real
- Limpieza/normalización: Eliminación de datos duplicados, imputación de faltantes, conversión de formatos
- Almacenamiento (data lake/warehouse): Data lake en la nube (AWS S3 + Redshift)
- Preparación de variables (features): Agregación por SKU, tendencia histórica, estacionalidad, promociones
- Análisis/BI (opcional): Visualizaciones de tendencias de demanda y correlación con campañas de marketing

## 4) IA aplicada: modelo y decisión
- Tipo de IA/técnica: Predicción (forecasting) mediante modelos de series temporales y XGBoost
- Entrada del modelo (qué datos usa): Historial de ventas, clics, promociones, stock disponible
- Salida del modelo (qué produce): Predicción de demanda futura por producto y región
- Decisión que habilita (qué hace la empresa con esa salida): Ajusta inventario y pedidos de proveedores para maximizar ventas y minimizar exceso de stock

## 5) Rentabilidad: KPIs antes/después (mínimo 3)
KPI 1 (ingresos/coste/eficiencia):
- Antes:
- Después:
- Por qué mejora la rentabilidad:

KPI 2:
- Antes:
- Después:
- Por qué mejora la rentabilidad:

KPI 3:
- Antes:
- Después:
- Por qué mejora la rentabilidad:

## 6) Diagrama del pipeline (ASCII o Mermaid)
(Pega aquí el diagrama)

## 7) Riesgos y mitigación
Riesgo 1:
- Mitigación 1:

Riesgo 2:
- Mitigación 2:

## 8) Valoración (criterio c): importancia presente y futura de la IA (10–15 líneas)
- Importancia actual (hoy):
- Importancia futura (3–5 años):
- Condiciones/limitaciones (datos, costes, regulación, ética, seguridad, empleo):
- Conclusión razonada:

## 9) Fuentes oficiales (mín. 2)
- Big Data/analítica (enlace oficial):
- IA/técnica/modelo (enlace oficial):
