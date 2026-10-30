# Tarea 3: Procesamiento de Datos con Apache Spark (Big Data)

## Descripción del Proyecto
Este repositorio contiene el desarrollo del componente práctico individual para la **Tarea 3** del curso de Big Data de la UNAD. El objetivo es procesar y analizar un volumen significativo de datos transaccionales utilizando **Python y PySpark** en un entorno de Google Colab.

## Dataset Utilizado
* **Nombre:** Supermarket Sales
* **Fuente:** Kaggle
* **Descripción:** Contiene registros históricos de transacciones de ventas de un supermercado (incluyendo ID de factura, sucursal, ciudad, tipo de cliente, líneas de productos, precios y totales).

## Estructura del Código (Procesamiento Batch)
El script desarrollado realiza los siguientes pasos:
1. **Configuración de la Sesión:** Inicialización de PySpark.
2. **Carga y Limpieza:** Lectura del archivo CSV y filtrado/eliminación de valores nulos.
3. **Análisis Exploratorio de Datos (EDA):**
   - Agrupación por línea de producto para calcular ingresos totales.
   - Evaluación del rendimiento por sucursal y ciudad (ventas totales y calificaciones promedio).
   - Análisis de ventas según el tipo de cliente.

## Instrucciones de Ejecución
1. Descargar el archivo `SuperMarket Analysis.csv`.
2. Abrir una nueva libreta en [Google Colab](https://colab.research.google.com/).
3. Subir el archivo CSV al panel izquierdo de Colab.
4. Ejecutar el código de PySpark provisto en el cuaderno para visualizar las métricas y resultados analíticos.
