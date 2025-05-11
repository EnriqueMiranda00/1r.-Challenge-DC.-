
Explicacion general del desafio.

Carga y organización de datos

Importa los archivos CSV de cada tienda (tienda_1.csv, tienda_2.csv, etc.) que contienen registros de ventas, precios, costos de envío y calificaciones de clientes.

Agrupa estos archivos en una lista de DataFrames para procesarlos de forma iterativa.

Cálculo de métricas clave

Ingresos totales: suma de los precios de todos los productos vendidos en cada sucursal.

Productos vendidos: conteo del número total de transacciones por tienda.

Costo de envío promedio y total: promedio y suma de los valores de envío para cada sucursal.

Ganancia neta: diferencia entre ingresos y costos de envío, que refleja la rentabilidad real.

Ticket promedio: ingreso promedio por venta.

Calificación promedio: promedio de las reseñas (1 a 5 estrellas) para evaluar la satisfacción de los clientes.

Análisis por categoría y producto

Genera conteos y porcentajes de ventas por categoría de producto, identificando cuáles son las líneas más fuertes de cada tienda.

Extrae el top de productos más vendidos para comprender los artículos con mayor demanda.

Visualizaciones con Matplotlib

Barras comparativas de ingresos acumulados por tienda.

Gráficos circulares de distribución de ventas por categoría.

Histogramas de calificaciones para mostrar la dispersión de opiniones de clientes.

Diagramas de caja (boxplots) para comparar los costos y tiempos de envío entre sucursales.

Síntesis de resultados

Consolida todas las métricas en un único DataFrame resumen que permite comparar rápidamente cada tienda en aspectos de volumen de ventas, rentabilidad, satisfacción y costos logísticos.

A partir de este resumen, se identifica la sucursal con menor rendimiento: aquella con ingresos más bajos, menor ticket promedio y mayor proporción de reseñas negativas.
