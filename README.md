#  Challenge Alura - Data Science

Proyecto desarrollado en el **Challenge de Data Science de Alura Latam**, enfocado en el análisis de datos de ventas de diferentes tiendas para apoyar la toma de decisiones comerciales basadas en datos.

El objetivo del proyecto es analizar el desempeño de cuatro tiendas y determinar **cuál debería vender el Sr. Juan**, utilizando métricas de negocio como ingresos, satisfacción de clientes, categorías de productos y distribución geográfica de ventas.

---

#  Objetivo del Proyecto

El análisis busca responder las siguientes preguntas:

- ¿Qué tienda genera **mayores ingresos**?
- ¿Cuáles son las **categorías de productos más vendidas**?
- ¿Qué tienda tiene **mayor satisfacción de clientes**?
- ¿Cuáles son los **productos más vendidos y menos vendidos**?
- ¿Cómo se distribuyen **geográficamente las ventas**?
- ¿Qué tienda tiene **menor rendimiento general**?

---

#  Estructura del Proyecto

```
Challenge-Alura-Data-science/
│
├── datos/
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
│
├── analisis.ipynb
│
└── README.md
```

---

#  Datos Analizados

El dataset contiene información relacionada con las transacciones comerciales de cada tienda.

Variables principales analizadas:

- **Producto**
- **Categoría del Producto**
- **Precio**
- **Costo de envío**
- **Fecha de Compra**
- **Vendedor**
- **Lugar de Compra**
- **Calificación**
- **Método de pago**
- **Cantidad de cuotas**
- **Latitud (lat)**
- **Longitud (lon)**

Estas variables permitieron realizar análisis financieros, comerciales y geográficos.

---

# 📈 Análisis Realizados

## 1️ Ingresos Totales por Tienda

Se calcularon los ingresos totales sumando los valores de la columna **Precio** para cada tienda.

Resultado observado en los gráficos:

| Tienda | Nivel de ingreso |
|------|------|
| Tienda 1 | Alto |
| Tienda 2 | Alto |
| Tienda 3 | Alto |
| **Tienda 4** | **Más bajo** |

Esto permitió identificar diferencias claras en el desempeño económico.

---

## 2️ Categorías de Productos Más Vendidas

Se analizaron las categorías con mayor número de ventas utilizando conteo de frecuencia.

Principales categorías:

- Muebles
- Electrónicos
- Electrodomésticos
- Juguetes
- Deportes y diversión

Este análisis permitió identificar los **segmentos de productos que impulsan las ventas**.

---

## 3️ Calificación Promedio de Clientes

Se calculó la calificación promedio de cada tienda utilizando la columna **Calificación**.

Resultados generales:

- Todas las tiendas presentan calificaciones cercanas a **4 puntos**.
- **Tienda 3 presenta la mejor calificación promedio**.

Esto indica un **nivel de satisfacción relativamente alto en general**.

---

## 4️ Productos Más Vendidos

Se identificaron los productos más y menos vendidos mediante conteo de frecuencia de la variable **Producto**.

Este análisis permite:

- Detectar **productos estrella**
- Identificar **productos con bajo rendimiento**

---

## 5️ Análisis Geográfico de Ventas

Utilizando las coordenadas **latitud y longitud**, se generaron visualizaciones geográficas para identificar patrones espaciales de ventas.

Se utilizaron:

- **Gráficos de dispersión**
- **Mapas de calor**

Estos gráficos permiten identificar **zonas con mayor concentración de ventas**.

---

#  Visualizaciones Generadas

El análisis incluyó diferentes tipos de gráficos para facilitar la interpretación de los datos:

-  **Gráfico de barras:** ingresos por tienda  
-  **Gráfico circular:** distribución de categorías  
-  **Gráfico de barras:** calificación promedio  
-  **Gráfico de dispersión:** distribución geográfica de ventas  
-  **Mapa de calor:** concentración geográfica de ventas  

Las visualizaciones permiten comprender de forma clara los patrones presentes en los datos.

---

#  Conclusión del Análisis

Tras analizar los diferentes indicadores de desempeño se observa que:

- **Tienda 1 presenta los mayores ingresos**
- **Tienda 2 y Tienda 3 mantienen un buen rendimiento**
- **Tienda 3 tiene la mejor calificación promedio**
- **Tienda 4 presenta los menores ingresos**

Aunque la satisfacción del cliente es similar entre las tiendas, el indicador que presenta mayor diferencia es el **nivel de ingresos generados**.

---

#  Recomendación

Con base en el análisis realizado, se recomienda que el **Sr. Juan venda la Tienda 4**, ya que presenta el **menor rendimiento económico dentro del conjunto de tiendas analizadas**.

Esta decisión permitiría concentrar recursos en las tiendas con mejor desempeño y mayor capacidad de generación de ingresos.

---

# ⚙️ Tecnologías Utilizadas

- **Python**
- **Pandas**
- **Matplotlib**
- **Google Colab**

---


# 👨‍💻 Autor

Proyecto desarrollado como parte del **Challenge de Data Science de Alura Latam**.
