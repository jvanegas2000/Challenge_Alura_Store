# 🛒 Análisis de Ventas - AluraStore Latam

Este proyecto analiza los datos de ventas de cuatro tiendas diferentes para ayudar a **Señor Juan** a decidir cuál de sus tiendas vender, basándose en métricas de desempeño como facturación, calificaciones, productos más vendidos, costos de envío y análisis geográfico.

## 📊 Objetivos

- Analizar la facturación y rentabilidad de cada tienda.
- Evaluar la satisfacción de los clientes mediante calificaciones.
- Identificar los productos más y menos vendidos.
- Analizar los costos de envío y su impacto.
- Visualizar la distribución geográfica de las ventas.

## 🗂️ Archivos

- `tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv`: Datos de ventas de cada tienda.
- `AluraStoreLatam.ipynb`: Notebook con todo el análisis y visualizaciones.

## 📝 Análisis Realizados

### 1. Facturación y Rentabilidad

Se calculó la facturación total, el costo de envío y la rentabilidad de cada tienda. Se generaron tablas resumen y gráficos comparativos.

### 2. Ventas por Categoría

Se analizaron las ventas agrupadas por categoría de producto para identificar las áreas más fuertes de cada tienda.

### 3. Calificación Promedio

Se calculó la calificación promedio y la desviación estándar de cada tienda, visualizando la distribución con boxplots.

### 4. Productos Más y Menos Vendidos

Se identificaron los productos más y menos vendidos en cada tienda y de forma consolidada.

### 5. Costos de Envío

Se analizó el costo promedio de envío por tienda y su dispersión.

### 6. Análisis Geográfico

Se mapearon las ventas según latitud y longitud, mostrando la distribución geográfica y posibles oportunidades de expansión.

# Estructura del Proyecto 📁

```
AluraStoreLatam/
│
├── data/
│   ├── tienda_1.csv
│   ├── tienda_2.csv
│   ├── tienda_3.csv
│   └── tienda_4.csv
│
├── notebooks/
│   └── AluraStoreLatam.ipynb
│
├── README.md
│
└── requirements.txt
```

## Descripción de la Estructura 📋

### `/data`
Contiene los archivos CSV con los datos de ventas de cada tienda:
- `tienda_1.csv`: Datos de la primera tienda
- `tienda_2.csv`: Datos de la segunda tienda
- `tienda_3.csv`: Datos de la tercera tienda
- `tienda_4.csv`: Datos de la cuarta tienda

### `/notebooks`
Contiene los Jupyter Notebooks con todo el análisis:
- `AluraStoreLatam.ipynb`: Notebook principal con el análisis completo

### Archivos en la raíz
- `README.md`: Documentación principal del proyecto
- `requirements.txt`: Lista de dependencias y bibliotecas necesarias

## 📈 Principales Conclusiones

Tras analizar los datos de las cuatro tiendas en los aspectos de facturación, ventas por categoría, calificación promedio, productos más y menos vendidos, y costos de envío, se pueden extraer las siguientes conclusiones:

1. **Facturación total:** La Tienda 4 presenta la facturación total más baja, tanto en ventas como en ingresos por envíos, mientras que la Tienda 1 lidera en este aspecto. Las diferencias, aunque no son abismales, son consistentes y relevantes para la toma de decisiones.

2. **Ventas por categoría:** En casi todas las categorías principales (Electrónicos, Electrodomésticos, Muebles), la Tienda 4 también muestra los valores más bajos de ventas, lo que refuerza la tendencia observada en la facturación total.

3. **Calificación promedio:** Todas las tiendas tienen calificaciones promedio y medianas muy similares, con una mayoría de clientes satisfechos (mediana 5 y promedio cercano a 4). No hay diferencias significativas en la percepción del cliente que justifiquen la venta de una tienda sobre otra.

4. **Productos más y menos vendidos:** La Tienda 4 no destaca en los productos más vendidos y, al igual que en los otros puntos, muestra menor volumen en los productos populares. Esto sugiere menor rotación de inventario y menor dinamismo comercial.

5. **Envío promedio:** Los costos de envío promedio y su variabilidad son muy similares entre todas las tiendas, por lo que este factor no es determinante para la decisión.

**Recomendación:**  
Considerando todos los análisis, la **Tienda 4** es la que muestra un desempeño menor de manera consistente en facturación, ventas por categoría y rotación de productos. Dado que la satisfacción del cliente y los costos de envío son similares en todas las tiendas, vender la Tienda 4 sería la opción más lógica para el Señor Juan si busca desprenderse de la tienda menos rentable y con menor potencial de crecimiento.

> **En resumen:**  
> Se recomienda vender la Tienda 4, ya que es la que presenta el desempeño más bajo en los indicadores clave analizados.

## 🚀 Cómo ejecutar el análisis

1. Clona este repositorio.
2. Instala las dependencias necesarias (pandas, matplotlib, seaborn, geopandas, contextily, etc.).
3. Abre el notebook `AluraStoreLatam.ipynb` y ejecuta las celdas.

## 💡 Autor

Proyecto realizado por Juan Carlos Vanegas Molina para el curso de Data Science de Alura Latam.

