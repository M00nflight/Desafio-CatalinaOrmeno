Desafío 1 – Modelamiento del Data Warehouse Se diseñó un modelo dimensional en estrella considerando las entidades: Productos, Tiendas, Proveedores, Promociones, Clientes, Tiempo y Medios de Pago. El modelo fue implementado en MySQL Workbench y exportado como script SQL. Se establecieron claves primarias y foráneas, relaciones 1:N y supuestos de negocio documentados. 
-Archivo: transacciones_dw (adjunto en el informe Word) 
-Evidencia: Diagrama EER (adjunto en el informe Word).

Desafío 2 – Documentación Técnica Se elaboró documentación técnica para al menos dos entidades del modelo, utilizando una plantilla estructurada (nombre, descripción, atributos, llaves y relaciones). Se dejó registro del owner del proyecto y control de versiones. 
-Archivo: Word Adjunto

Desafío 3 – Procesamiento y Carga de Datos Se realizó la transformación del archivo transacciones.txt mediante Python (Pandas). Se exportó un dataset limpio transacciones_clean.csv. Se cargaron los datos a BigQuery Sandbox, creando el dataset retail_dw_dataset y la tabla transacciones_limpias. Se ejecutó una consulta SQL para obtener: 
-Monto total de transacciones por mes 
-Promedio de artículos 
-Ticket promedio mensual

Archivos: 
-desafio3.ipynb (código Python Jupyter) 
-consulta_bigquery.sql (consulta SQL ejecutada) 
-resultados_bigquery.csv (exportación de resultados) 
-bigquery_evidencias/ (capturas del proceso en BigQuery)