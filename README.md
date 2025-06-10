# 📊 Análisis de Ventas y Rendimiento de Tiendas con Python

## Introducción

Este proyecto fue desarrollado con el objetivo de analizar el rendimiento comercial de **cuatro tiendas** diferentes utilizando Python y la biblioteca **Pandas**, junto con gráficos
simples para visualización. A partir de datos reales (productos, precios, calificaciones y costos), se realizó una evaluación integral para **ayudar al cliente a decidir qué tienda vender**.

---

## 🎯 Objetivos del Proyecto
Este proyecto de análisis de datos tiene como finalidad determinar el rendimiento de las tiendas de Don Juan para lo cual se analizaron los siguientes puntos puntos:
- **facturación total** por tienda.
- **categorías más populares** de productos.
- **promedio de calificación** de los productos vendidos.
- **productos más y menos vendidos** por tienda.
- **costo promedio de envío** por tienda.

Con estos datos se pudo emitir una **recomendación final fundamentada** para la toma de decisión estratégica.

---

## 🛠️ Herramientas y Tecnologías Utilizadas

- Python 3.10+
- Google Colab / Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn
---

## 🧑‍💻 Instrucciones de Uso

1. Abre el notebook en Google Colab o Jupyter Notebook.
2. Asegúrate de tener las siguientes bibliotecas instaladas:
   - import pandas as pd
   - import matplotlib.pyplot as plt
   - import seaborn as sns
    
3. Ejecuta las celdas en orden para realizar el análisis completo.
4. Revisar los resultados impresos y gráficos para cada tienda en Informe

---

## 🔍 Evaluación por criterio


### 1. Facturación Total por Tienda
   
*La Tienda 4 registra la facturación más baja, con una diferencia significativa respecto a Tienda 1.*


### 2. Categoría Más Vendida por Tienda
Resultados similares en todas las tiendas y las categorías más vendidas fueron Muebles y Electrónicos. No hay ventajas competitivas claras.


### 3. Calificación Promedio
**Tienda	  Calificación**
Tienda 1	 3.98
Tienda 2	 4.04
Tienda 3	 4.05
Tienda 4	 4.00

La Tienda 3 presenta la mejor valoración por parte de los clientes. *La Tienda 4 tiene calificación intermedia, pero no destaca frente a las otras.*


### 4. Producto Más y Menos Vendido ###
**Tienda	  Más vendido	              Cuotas	        Menos vendido	                        Cuotas**
Tienda 1	Microondas 	                 60             Auriculares con micrófono                33    
Tienda 2	Iniciando en programación	  65	           Juego de Mesa                            32
Tienda 3	Kit de bancas                57  	        Bloques de Construcción                  35
Tienda 4	Cama Box       	           62	           Guitarra eléctrica	                      33

*Tienda 4 tiene buenos números en productos más vendidos, pero sus ventas totales y facturación no acompañan o no presentan grandes desviaciones*


### 5. Costo Promedio de Envío ###
Tienda	Costo Promedio Envío (CLP)
Tienda 1	$26,018.61
Tienda 2	$25,216.24
Tienda 3	$24,805.68
Tienda 4	$23,459.46

*Tienda 4 tiene el envío más barato. Tienda 1 el más caro. Sin embargo, este factor por sí solo no compensa una baja facturación.*


## ✅ Conclusión y Recomendación Final ##

### **Resumen Consolidado de Tiendas**

 | Tienda   | Facturación Total   | Categoría Más Vendida  | Calificación Promedio | Producto Más Vendido (cuotas) | Producto Menos Vendido (cuotas) | Costo Envío Promedio  |
 |----------|---------------------|------------------------|-----------------------|-------------------------------|---------------------------------|-----------------------|
 | Tienda 1 | \$1.150.880.400     | Muebles                | 3.98                  | Microondas (60)               | Auriculares con micrófono (33)  | \$26.018,61           |
 | Tienda 2 | \$1.116.343.500     | Muebles                | 4.04                  | Iniciando en programación (65)| Juego de mesa (32)              | \$25.216,24           |
 | Tienda 3 | \$1.098.019.600     | Muebles                | 4.05                  | Kit de bancas (57)            | Bloques de construcción (35)    | \$24.805,68           |
 | Tienda 4 | \$1.038.375.700     | Muebles                | 4.00                  | Cama box (62)                 | Guitarra eléctrica (33)         | \$23.459,46           |


Al considerar de manera integral los cinco criterios vemos que:

1. La **Tienda 1** tiene la mejor facturación pero la peor calificación y el envío más caro.  
2. La **Tienda 2** tiene cifras equilibradas, sin sobresalir ni quedar rezagada.  
3. La **Tienda 3** ofrece el mejor balance general, con una muy buena calificación, buena facturación y costo de envío aceptable.  
4. La **Tienda 4**, a pesar de tener el mejor costo de envío, presenta **la menor facturación**, sin ventajas importantes en calificación o ventas por categoría.

---
## Recomendación: ##

**Se recomienda que el señor Juan cierre la Tienda 4**, ya que es la que presenta **menor rendimiento global** considerando los criterios estratégicos definidos.

---
Desarrollado en Python por Zaida Donoso, estudiante Alura Latam
