# Tarea 3 - Procesamiento de Datos con Apache Spark

Este repositorio contiene el desarrollo de la Tarea 3 del curso Big Data.

## Componentes desarrollados

1. Procesamiento batch con Apache Spark y PySpark.
2. Procesamiento en tiempo real con Apache Kafka y Spark Streaming.

## Procesamiento batch

Se generó un conjunto de datos propio de ventas con 10.000 registros. Posteriormente, se cargó el archivo en Spark, se realizó limpieza, transformación, análisis exploratorio y visualización de resultados.

## Procesamiento en tiempo real

Se configuró Kafka, se creó el topic `sensor_data`, se implementó un productor de datos simulados y un consumidor con Spark Streaming. El consumidor calculó el promedio de temperatura y humedad por sensor en ventanas de tiempo.

## Herramientas utilizadas

- Google Colab
- Python
- PySpark
- Apache Spark
- Apache Kafka
- Spark Streaming
- Pandas
- Matplotlib

## Archivo principal

- `Tarea3_Procesamiento_Batch_Spark.ipynb`

## Ejecución

Abrir el notebook en Google Colab y ejecutar las celdas en orden.
