# 📊 Análisis de Ventas y Rendimiento de Tiendas con Python

## 🧾 Introducción

Este proyecto fue desarrollado con el objetivo de analizar el rendimiento comercial de **cuatro tiendas** diferentes utilizando Python y la biblioteca **Pandas**, junto con gráficos
simples para visualización. A partir de datos reales (productos, precios, calificaciones y costos), se realizó una evaluación integral para **ayudar al cliente a decidir qué tienda vender**.

---

## 🎯 Objetivos del Proyecto
Este proyecto de análisis de datos tiene como finalidad responder las siguientes preguntas clave relacionadas con el rendimiento de cuatro tiendas:

- Calcular la **facturación total** por tienda.
- Identificar las **categorías más populares** de productos.
- Calcular el **promedio de calificación** de los productos vendidos.
- Detectar los **productos más y menos vendidos** por tienda.
- Estimar el **costo promedio de envío** por tienda.
- Visualizar los resultados con **gráficos representativos**.
- Emitir una **recomendación final fundamentada** para la toma de decisión estratégica.

---

## 🛠️ Herramientas y Tecnologías Utilizadas

- Python 3.10+
- Google Colab / Jupyter Notebook
- Pandas
- Matplotlib

---

## 🧑‍💻 Instrucciones de Uso

1. Abre el notebook en Google Colab o Jupyter Notebook.
2. Asegúrate de tener las siguientes bibliotecas instaladas:
   ```bash
   pip install pandas matplotlib
Ejecuta las celdas en orden para realizar el análisis completo.

Revisar los resultados impresos y gráficos para cada tienda en Informe

---

## 🔍 Resultados Principales del Análisis

### 1. 💰 Facturación Total por Tienda
   
**Tienda	Facturación Total ($)**
Tienda 1	$3,422,717,700
Tienda 2	$3,337,189,200
Tienda 3	$3,243,816,900
Tienda 4	$3,098,827,200

*La Tienda 4 registra la facturación más baja, con una diferencia significativa respecto a Tienda 1.*

### 2. 📦 Categoría Más Vendida por Tienda

**Tienda	Categoría más vendida	Cuotas vendidas**
Tienda 1	Muebles	1.446
Tienda 2	Electrónicos	1.333
Tienda 3	Muebles	1.408
Tienda 4	Muebles	1.392

*La Tienda 4, aunque enfocada en muebles, no supera en ventas a Tiendas 1 y 3, que lideran en esta categoría.*

###3. ⭐ Calificación Promedio
**Tienda	  Calificación**
Tienda 1	 3.98
Tienda 2	 4.04
Tienda 3	 4.05
Tienda 4	 4.00

*La Tienda 4 tiene calificación intermedia, pero no destaca frente a las otras.*

🏅 La Tienda 3 presenta la mejor valoración por parte de los clientes.

### 4. 🛍️ Producto Más y Menos Vendido###
**Tienda	  Más vendido	              Cuotas	        Menos vendido	      Cuotas**
Tienda 1	Secadora de ropa	         214	          Celular ABXY	      78
Tienda 2	Iniciando en programación	 223	          Mesa de comedor	    89
Tienda 3	Bicicleta	                 191	          TV LED UHD 4K	      94
Tienda 4	Dashboards con Power BI	   196	          Armario	            88

*Tienda 4 tiene buenos números en productos más vendidos, pero sus ventas totales y facturación no acompañan.*

### 🚚 5. Costo Promedio de Envío###
Tienda	Costo Promedio Envío (CLP)
Tienda 1	$26,018.61
Tienda 2	$25,216.24
Tienda 3	$24,805.68
Tienda 4	$23,459.46

## ✅ Conclusión y Recomendación Final##
Para analisar tomaremos los sigientes datos proporcionados por el cliente:
| Tienda      | Facturación Total (CLP) | Categoría Más Vendida          | Calificación Promedio | Producto Más Vendido (cuotas)       | Producto Menos Vendido (cuotas) | Costo Envío Promedio (CLP) |
|-------------|-------------------------|-------------------------------|----------------------|------------------------------------|---------------------------------|----------------------------|
| Tienda 1    | 3,422,717,700           | Muebles (1,446 cuotas)        | 3.98                 | Secadora de ropa (214)              | Celular ABXY (78)                | 26,018.61                  |
| Tienda 2    | 3,337,189,200           | Electrónicos (1,333 cuotas)   | 4.04                 | Iniciando en programación (223)    | Mesa de comedor (89)             | 25,216.24                  |
| Tienda 3    | 3,243,816,900           | Muebles (1,408 cuotas)        | 4.05                 | Bicicleta (191)                    | TV LED UHD 4K (94)              | 24,805.68                  |
| Tienda 4    | 3,098,827,200           | Muebles (1,392 cuotas)        | 4.00                 | Dashboards con Power BI (196)      | Armario (88)                    | 23,459.46                  |


Tiene la menor calificación promedio (3.90).

Muestra facturación más baja en comparación a las demás.

Las categorías y productos que lideran las ventas en esta tienda son menos rentables que en las otras.

Su costo de envío es competitivo, pero no suficiente para compensar el bajo rendimiento global.


---
##📢 Recomendación:##
Mantener las Tiendas 1 y 3, siendo la Tienda 3 la más sólida por rendimiento general y satisfacción del cliente.

📎 Créditos y Datos
Desafío basado en datos públicos del Challenge 1 - Alura LATAM

Desarrollado en Python por
