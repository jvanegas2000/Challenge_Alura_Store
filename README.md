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

- **Tienda 1** y **Tienda 2** presentan la mejor facturación y satisfacción del cliente.
- **Tienda 4** tiene menor facturación, menor calificación promedio y mayores costos de envío, por lo que se recomienda considerar su venta.
- Los productos de la categoría **Electrodomésticos** y **Muebles** son los más vendidos en general.
- Las ventas están concentradas en ciudades principales como Bogotá, Medellín y Cali.

## 🚀 Cómo ejecutar el análisis

1. Clona este repositorio.
2. Instala las dependencias necesarias (pandas, matplotlib, seaborn, geopandas, contextily, etc.).
3. Abre el notebook `AluraStoreLatam.ipynb` y ejecuta las celdas.

## 💡 Autor

Proyecto realizado por Juan Carlos Vanegas Molina para el curso de Data Science de Alura Latam.

