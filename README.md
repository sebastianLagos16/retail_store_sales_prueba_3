# Retail Store Sales - Evaluaciones 2 y 3

Proyecto académico de Programación para Ciencia de Datos orientado al análisis de ventas retail, segmentación de clientes y visualización interactiva de resultados.

## Objetivo

Construir una base de clientes a partir del dataset transaccional, clasificar niveles VIP, comparar modelos vistos en clases y presentar resultados de negocio mediante visualizaciones interactivas con Plotly y un mini dashboard.

## Dataset utilizado

- Archivo: `retail_store_sales.csv`
- Tipo de datos: ventas retail por transacción.
- Variables principales usadas: cliente, fecha de transacción, monto gastado, cantidad comprada, categoría, método de pago, canal de compra y descuento aplicado.

## Estructura del notebook

El desarrollo principal se encuentra en `Evaluacion_2.ipynb` e incluye:

- Carga del dataset CSV.
- Limpieza y preparación básica de datos.
- Construcción de una base agregada por cliente.
- Creación de variables de comportamiento y niveles VIP.
- Evaluación 2 con modelos y métricas vistas en clases.
- Evaluación 3 con visualizaciones Plotly y mini dashboard.

## Modelos usados en Evaluación 2

La Evaluación 2 se mantiene alineada con los contenidos revisados en clases:

- K-Means para segmentación de clientes.
- PCA para visualización bidimensional de clusters.
- Regresión Logística para clasificación de nivel VIP.
- Árbol de Decisión para clasificación de nivel VIP.
- Accuracy y matrices de confusión como métricas supervisadas.
- Descuento recomendado como regla de negocio asociada al nivel VIP.

## Visualizaciones Plotly de Evaluación 3

La Evaluación 3 incorpora al menos tres visualizaciones interactivas:

- Gráfico de barras: gasto promedio por nivel VIP.
- Gráfico de líneas: clientes por rangos de recencia o días desde la última compra.
- Gráfico de dispersión: relación entre frecuencia de compra y gasto total.

Cada visualización incluye una interpretación orientada a decisiones comerciales, fidelización y riesgo de inactividad o fuga.

## Mini dashboard

El notebook incluye una sección de mini dashboard con:

- Indicadores principales impresos en consola.
- Clientes analizados.
- Gasto total.
- Ticket promedio general.
- Compras totales.
- Modelo supervisado recomendado y accuracy, cuando las variables existen.
- Dashboard visual integrado con barras, líneas y dispersión usando Plotly.

## Uso de Git y GitHub

El repositorio incluye evidencia de trabajo con Git mediante commits asociados a la preparación de datos, visualizaciones interactivas y mini dashboard. En el notebook se documentan comandos de referencia como:

```bash
git status
git add Evaluacion_2.ipynb README.md
git commit -m "feat: refine plotly dashboard and documentation"
git push
```

## Instrucciones básicas para ejecutar

1. Abrir `Evaluacion_2.ipynb` en Jupyter Notebook, JupyterLab o Visual Studio Code.
2. Verificar que `retail_store_sales.csv` esté en la misma carpeta del notebook.
3. Ejecutar las celdas en orden desde el inicio.
4. Revisar la sección de Evaluación 3 para las visualizaciones interactivas y el mini dashboard.

## Alcance de esta entrega

La presentación breve se realizará directamente desde el notebook. El informe de esta evaluación se elaborará después, por lo que no se incluye un informe nuevo en esta etapa.
